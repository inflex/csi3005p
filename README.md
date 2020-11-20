# csi3005p
csi3005p - CircuitWorks CSI3005p PSU OSD for OBS

# Requirements

You will require the SDL2 development lib in linux

Your linux kernel needs to support the USBTMC protocol, most 
reasonably modern kernels already have this.

# Prerequisites 
## Build tools
	apt install git build-essential libsdl2-dev

## Source
	git clone https://github.com/inflex/csi3005p

# Build

	cd csi3005p
	make
	
# Usage
	
   
Run from the command line

	sudo ./csi3005p -p /dev/usbtmc2





