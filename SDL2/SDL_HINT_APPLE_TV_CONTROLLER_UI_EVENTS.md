###### (This is the legacy documentation for stable SDL2, the current stable version; [SDL3](https://wiki.libsdl.org/SDL3/) is the current development version.)
# SDL_HINT_APPLE_TV_CONTROLLER_UI_EVENTS

A variable controlling whether controllers used with the Apple TV generate UI events.

## Header File

Defined in [SDL_hints.h](https://github.com/libsdl-org/SDL/blob/SDL2/include/SDL_hints.h)

## Syntax

```c
#define SDL_HINT_APPLE_TV_CONTROLLER_UI_EVENTS "SDL_APPLE_TV_CONTROLLER_UI_EVENTS"
```

## Remarks

When UI events are generated by controller input, the app will be
backgrounded when the Apple TV remote's menu button is pressed, and when
the pause or B buttons on gamepads are pressed.

More information about properly making use of controllers for the Apple TV
can be found here:
https://developer.apple.com/tvos/human-interface-guidelines/remote-and-controllers/

This variable can be set to the following values:

- "0": Controller input does not generate UI events (the default).
- "1": Controller input generates UI events.

----
[CategoryAPI](CategoryAPI), [CategoryAPIMacro](CategoryAPIMacro), [CategoryDefine](CategoryDefine), [CategoryHints](CategoryHints)


