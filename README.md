# Ferienakademie 2019, course 5

This is the Git repository for the course 5 "[Let's Play! Simulated Physics for Games](https://www.ferienakademie.de/kurse-2019/kurs-5/)" of the Ferienakademie 2019 in Sarntal.

## Build

The main dependencies are:
* [SDL2](https://www.libsdl.org/): Library for "low-level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D" (Debian package `libsdl2-dev`)
* [SLD2_image](https://www.libsdl.org/projects/SDL_image/): Image file loading library (`libsdl2-image-dev`)

Other dependencies you might need later are:
* [SDL2_ttf](https://www.libsdl.org/projects/SDL_ttf/): TrueType Fonts (`libsdl2-ttf-dev`)
* [SDL2_mixer](https://www.libsdl.org/projects/SDL_mixer/): Audio mixer (`libsdl2-mixer-dev`)
* [SDL2_gfx](https://www.libsdl.org/): Antialised drawing routines ruch as lines, circles, or polygons (`libsdl2-gfx-dev`)
* [Bullet physics](https://pybullet.org/wordpress/): Physics engine (`libbullet-dev`)

With all the dependencies installed, simply do:

```bash
make
```

## Run

Run the executable from the parent directory (where `data/` is located):

```bash
build/fa_2019_release
```

## Documentation

Have a look into the `doc/` directory, where you can find:
* The document [project.pdf](doc/project.pdf) describing the structure of the framework
* The file [kinect.txt](doc/kinect.txt) with instructions on setting up Kinect
