###### (This is the documentation for SDL3, which is under heavy development and the API is changing! [SDL2](https://wiki.libsdl.org/SDL2/) is the current stable version!)
# SDL_AtomicSetPointer

Set a pointer to a value atomically.

## Header File

Defined in [<SDL3/SDL_atomic.h>](https://github.com/libsdl-org/SDL/blob/main/include/SDL3/SDL_atomic.h)

## Syntax

```c
void * SDL_AtomicSetPointer(void **a, void *v);
```

## Function Parameters

|         |       |                            |
| ------- | ----- | -------------------------- |
| void ** | **a** | a pointer to a pointer.    |
| void *  | **v** | the desired pointer value. |

## Return Value

(void *) Returns the previous value of the pointer.

## Remarks

***Note: If you don't know what this function is for, you shouldn't use
it!***

## Thread Safety

It is safe to call this function from any thread.

## Version

This function is available since SDL 3.0.0.

## See Also

- [SDL_AtomicCompareAndSwapPointer](SDL_AtomicCompareAndSwapPointer)
- [SDL_AtomicGetPointer](SDL_AtomicGetPointer)

----
[CategoryAPI](CategoryAPI), [CategoryAPIFunction](CategoryAPIFunction), [CategoryAtomic](CategoryAtomic)
