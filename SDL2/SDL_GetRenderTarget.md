###### (This is the legacy documentation for stable SDL2, the current stable version; [SDL3](https://wiki.libsdl.org/SDL3/) is the current development version.)
# SDL_GetRenderTarget

Get the current render target.

## Header File

Defined in [SDL_render.h](https://github.com/libsdl-org/SDL/blob/SDL2/include/SDL_render.h)

## Syntax

```c
SDL_Texture * SDL_GetRenderTarget(SDL_Renderer *renderer);

```

## Function Parameters

|                  |                       |
| ---------------- | --------------------- |
| **renderer**     | the rendering context |

## Return Value

Returns the current render target or NULL for the default render target.

## Remarks

The default render target is the window for which the renderer was created,
and is reported a NULL here.

## Version

This function is available since SDL 2.0.0.

## See Also

- [SDL_SetRenderTarget](SDL_SetRenderTarget)

----
[CategoryAPI](CategoryAPI), [CategoryAPIFunction](CategoryAPIFunction)

