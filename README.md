# Android SDL2 Fractals

Source code:

 - the code is assembled of several pieces available on GitHub

## Dependencies

### Gradle

The project is compatible with Gradle 5 and 6.
Android build Tools are set to 28.0.0 in file settings.gradle. Make sure to download those tools via Android Studio.


### Libraries

- libSDL2_png - derrived from https://github.com/julienr/libpng-android
    - applied patch - https://github.com/julienr/libpng-android/issues/6
    - renamed to SDL2_png, because of problem with png library in API level 19 - http://georgik.rocks/sdl2-for-android-api-level-19/
- libSDL2_jpeg - derrived from https://www.libsdl.org/projects/SDL_image/libs/
    - renamed to SDL2_jpeg from jpeg, because of library name collision in Android 
    https://stackoverflow.com/questions/11613040/why-does-jpeg-decompress-create-crash-without-error-message    


## Assets
- Cuckoo Clock Sound - http://soundbible.com/1261-Cuckoo-Clock.html
- Blazed font - http://www.all-free-download.com/
