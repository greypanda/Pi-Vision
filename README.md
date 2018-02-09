What is Pi Vision?

	Pi Vision is a Graphical User Interface for the Raspberry Pi Camera.
	It allows you to control the camera functions through the camera's
	native camera apps. It also displays the terminal commands sent. 

	The project was developed using Lazarus FPC and has been released 
	as open source. It is what you make of it.

	The incentive of Pi Vision is to allow for easy use of the 
	Raspberry Pi camera while also serving as an instructional tool. 
	Employed commands are relayed to the user. This assists novice users 
	in understanding the command structure.

	While Pi Vision is specificaly built for the ARM based Raspberry Pi, 
	binaries have also been provided for Windows, OSX and 
	Debian Linux. These are, however, only intended to review the 
	application.

It Still Runs!

	Here it is, 2018. I compiled this on the rpi3 and it works! 
	
	Why are we changing it?
	
	The current application is defined as a camera for a microscope. In this case, an Olympus CKX53.
	The basic microscope is not cheap, but not extravagant. The problem is that a supported camera
	will set you back several hundred ( or thousand ) bucks. So with a Raspberry Pi 3, a seven inch
	touchscreen, and a camera fitted with a CS mount, we can have a working system for a little over 
	a hundred bucks.
	
	Now for the software. Although Raspbian comes fitted with several camera utilities, they are
	command line only and don't really suit the needs of the microscope users. They only need a couple
	of things to get the job done:
	
		* The ability to preview the picture through the microscope lens for focusing and positioning.
		* A simple GUI that controls the camera in a non-intrusive way.
		* The ability to take a picture and save it on a USB flash drive.
		* Once defined, the destination drive should be remembered and pictures should be timestamped.
		
	So we can remove ( or at least hide ) most of the controls and just concentrate on taking pictures.
	
		
	
	
Where is the Install document?

	See the directory named "source" for the install.

Why won't Pi Vision app run on the Raspberry?

	You need to set its Permissions first.

	In order to run your apps independently from the Lazarus IDE you will 
	first need to set permissions. Right-click on the app and select Properties 
	from the drop-down. Select the Permissions tab from the Properties menu.
	There is a small check-box called "Make this file executable". Check this, 
	close the window and click on the app to run it.
 
Copyright

	Pi Vision Copyright 2013 B.J.Rao

	This program is free software; you can redistribute it and/or
	modify it under the terms of the GNU General Public License version 2
	as published by the Free Software Foundation.

	This program is distributed in the hope that it will be useful,
	but WITHOUT ANY WARRANTY; without even the implied warranty of
	MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
	GNU General Public License for more details.

	You should have received a copy of the GNU General Public License
	along with this program; if not, write to the:

	Free Software Foundation, Inc., 
	51 Franklin Street, Fifth Floor, 
	Boston, MA  02110-1301, USA.

Trademarks

	All trademarks are the property of their respective owners
	- Raspberry Pi is a trademark owned by the Raspberry Pi Foundation
