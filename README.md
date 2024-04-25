# Robotarna_KiCad_Library
Library for KiCad with part what we sometime want to us in a Robotárna project.

There are several libraries of symbols and footprints, in which there are always parts of a given category, e.g. wirelessModules or DcDcConverters.

Last version is for KiCad 8.0

## 3D models path
It is not possible to specify relative path to 3D model file in KiCad (only absolut path is possible).
Workaround is to set environment variable with path to the library.

So to make 3D models working, set `RKL_DIR` environment variable to `Robotarna_KiCad_Library` directory inside Your clone of this repository.
