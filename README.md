## Learning to write a Raytracer

As i'm a curios person and currently learning OpenGL, I was pretty interested in hhow to write a Raytracer and how it generally works. Therefore I picked the Guide "Ray Tracing in One Weekend"

### Commands

I have a build/Release and Debug folder. Release is a more optimized Image than the Debug.

```shell
# Configure and build release binaries under `build/Release`
$ cmake -B build/Release -DCMAKE_BUILD_TYPE=Release
$ cmake --build build/Release

# Configure and build debug binaries under `build/Debug`
$ cmake -B build/Debug -DCMAKE_BUILD_TYPE=Debug
$ cmake --build build/Debug
```

You can run the programs by executing the binaries placed in the build directory:

```shell
    $ build\Debug\inOneWeekend > image.ppm
```

or, run the optimized version (if you compiled with the release configuration):

```shell
    $ build\Release\inOneWeekend > image.ppm
```
