+Title = OS X Installation

What follows is a detailed step-by-step guide to install all Azul3D dependencies on a Mac OS X platform. For other platforms please see the [installation page](/doc/install).

* [Install Go](#install-go)
* [Install XCode](#install-xcode)
* [Dependencies](#dependencies)
* [Install Azul3D](#install-azul3d)

## Install Go

Install the latest version of Go from [here](http://golang.org/doc/install).

Note: *Azul3D requires at least Go version 1.3*

Set the environment variable `GOPATH`, for example to `/home/joe/godev`.

## Install XCode

XCode must be installed from the [App Store](https://itunes.apple.com/us/app/xcode/id497799835?mt=12).

## Dependencies

[Homebrew](http://brew.sh/) is used to install the dependencies. To install homebrew run in a terminal:

```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Then to install the FreeType library:

```
brew install freetype
```

Git:

```
brew install git
```

And [Git LFS](https://git-lfs.github.com/) or else you will be missing critical
files. To install it run:

```
brew install git-lfs
git lfs install
```

## Install Azul3D

At this point, *you've successfully installed the dependencies*!

Follow the rest of the instructions on the [installation page](/doc/install).
