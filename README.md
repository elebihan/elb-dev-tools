# (Personal) Development Tools

This project provides a collection of small tools that had/have their use when
developing some projects.

## Dependencies

- [Meson](http://mesonbuild.com/)
- [Ninja](https://ninja-build.org/) (version 1.7 or newer)

## Installing from source

To configure and build the project, execute:

```
mkdir build
meson . build
ninja -C build
```

To install the tools to system directories, execute:

```
ninja -C build install
```
