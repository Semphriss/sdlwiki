###### (This is the documentation for SDL3, which is under heavy development and the API is changing! [SDL2](https://wiki.libsdl.org/SDL2/) is the current stable version!)
# SDL_ResetKeyboard

Clear the state of the keyboard.

## Header File

Defined in [<SDL3/SDL_keyboard.h>](https://github.com/libsdl-org/SDL/blob/main/include/SDL3/SDL_keyboard.h)

## Syntax

```c
void SDL_ResetKeyboard(void);

```

## Remarks

This function will generate key up events for all pressed keys.

## Version

This function is available since SDL 3.0.0.

## See Also

- [SDL_GetKeyboardState](SDL_GetKeyboardState)

----
[CategoryAPI](CategoryAPI), [CategoryAPIFunction](CategoryAPIFunction)

