###### (This is the legacy documentation for stable SDL2, the current stable version; [SDL3](https://wiki.libsdl.org/SDL3/) is the current development version.)
# SDL_GetWindowMouseRect

Get the mouse confinement rectangle of a window.

## Header File

Defined in [SDL_video.h](https://github.com/libsdl-org/SDL/blob/SDL2/include/SDL_video.h)

## Syntax

```c
const SDL_Rect * SDL_GetWindowMouseRect(SDL_Window * window);

```

## Function Parameters

|                |                     |
| -------------- | ------------------- |
| **window**     | The window to query |

## Return Value

Returns A pointer to the mouse confinement rectangle of a window, or NULL
if there isn't one.

## Version

This function is available since SDL 2.0.18.

## See Also

- [SDL_SetWindowMouseRect](SDL_SetWindowMouseRect)

----
[CategoryAPI](CategoryAPI), [CategoryAPIFunction](CategoryAPIFunction)

