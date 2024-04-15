###### (This is the documentation for SDL3, which is under heavy development and the API is changing! [SDL2](https://wiki.libsdl.org/SDL2/) is the current stable version!)
# SDL_SensorType

The different sensors defined by SDL

## Header File

Defined in [SDL_sensor.h](https://github.com/libsdl-org/SDL/blob/main/include/SDL3/SDL_sensor.h), but apps should use `#include <SDL3/SDL.h>`

## Syntax

```c
typedef enum SDL_SensorType
{
    SDL_SENSOR_INVALID = -1,    /**< Returned for an invalid sensor */
    SDL_SENSOR_UNKNOWN,         /**< Unknown sensor type */
    SDL_SENSOR_ACCEL,           /**< Accelerometer */
    SDL_SENSOR_GYRO,            /**< Gyroscope */
    SDL_SENSOR_ACCEL_L,         /**< Accelerometer for left Joy-Con controller and Wii nunchuk */
    SDL_SENSOR_GYRO_L,          /**< Gyroscope for left Joy-Con controller */
    SDL_SENSOR_ACCEL_R,         /**< Accelerometer for right Joy-Con controller */
    SDL_SENSOR_GYRO_R           /**< Gyroscope for right Joy-Con controller */
} SDL_SensorType;
```

## Remarks

Additional sensors may be available, using platform dependent semantics.

Hare are the additional Android sensors:
https://developer.android.com/reference/android/hardware/SensorEvent.html#values

----
[CategoryAPI](CategoryAPI), [CategoryAPIEnum](CategoryAPIEnum)
