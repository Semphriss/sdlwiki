###### (This is the legacy documentation for stable SDL2, the current stable version; [SDL3](https://wiki.libsdl.org/SDL3/) is the current development version.)
# SDL_BlendOperation

The blend operation used when combining source and destination pixel components

## Header File

Defined in [SDL_blendmode.h](https://github.com/libsdl-org/SDL/blob/SDL2/include/SDL_blendmode.h)

## Syntax

```c
typedef enum SDL_BlendOperation
{
    SDL_BLENDOPERATION_ADD              = 0x1,  /**< dst + src: supported by all renderers */
    SDL_BLENDOPERATION_SUBTRACT         = 0x2,  /**< src - dst : supported by D3D9, D3D11, OpenGL, OpenGLES */
    SDL_BLENDOPERATION_REV_SUBTRACT     = 0x3,  /**< dst - src : supported by D3D9, D3D11, OpenGL, OpenGLES */
    SDL_BLENDOPERATION_MINIMUM          = 0x4,  /**< min(dst, src) : supported by D3D9, D3D11 */
    SDL_BLENDOPERATION_MAXIMUM          = 0x5   /**< max(dst, src) : supported by D3D9, D3D11 */
} SDL_BlendOperation;
```

----
[CategoryAPI](CategoryAPI), [CategoryAPIEnum](CategoryAPIEnum), [CategoryEnum](CategoryEnum), [CategoryRender](CategoryRender)

<!-- #Actually from the SDL_blendmode.h header which does not have it's own category in this wiki. -->


