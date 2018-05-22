# The Logo Recognizer

The Logo Recognizer is simple program that by using image processing algorithms localizes and recognizes sample logo.

In this project I use logo of some big supermarket chain that has its shops in many of European countries.

## Purpose

This implementation is project for my Digital Image Processing class and it is for better understanding image procesing and recognition.

## Platforms

This parser has been used only on Linux, but
it probably can works on any other platform as well.

### Build
```
git clone https://github.com/BartekkPL/logo-recognizer.git
cd logo-recognizer/
mkdir build
cd build/
cmake ..
make
```

And after these steps you have builded executable ready to use.

You can find it at **logo-recognizer/build/logo-recognizer**.

## Usage

``` bash
logo-recognizer <image_path>
```

## License

LOGO-RECOGNIZER is released under [Apache License](https://opensource.org/licenses/Apache-2.0).