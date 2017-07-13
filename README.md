Oculus360ImagePlayer
==================

Example code for displaying an equirectangular map on the Oculus Rift. It can be used in VR applications.

# Notes

It assumes that your equirectangular map is a 1-plane 24-bit bitmap with power-of-two (POT) dimentions. It uses `oglplus::images::Image` class to load the equirectangulr map. The bitmap in the repository is taken from [here](https://commons.wikimedia.org/wiki/File:Afterglow_of_a_sunset.jpg). Its copyright should be watched.

# Instructions for building (all platforms)

## Checking out 

	git clone https://github.com/jherico/OculusMinimalExample.git 

## Creating project files

	cd OculusMinimalExample
	mkdir build && cd build
	cmake ..
	cmake -G "Visual Studio 12 2013 Win64"

Will show you a list of supported generators on your platform.

## Building

Open Visual Studio and open the `OculusMinimalExample.sln` solution in the from the `OculusMinimalExample/build` directory

Right click on the `OculusMinimalExample` and choose `Set as StartUp Project`. 

Press `F5` or click on the `Local Windows Debugger` toolbar button
