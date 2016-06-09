# Pulley-Z-axis
a metal core xy printer with pulleys for the z-axis

This is an open source, 3D printer with a sheet metal frame. The intent of this design is to provide a robust mechanical design that is easy for any machine shop to manufacture. Currently, the design does require use of a breakpress and laser cutter, but all the bends are sharp 90deg, and the parts could be modified to use off the shelf (or printed) corner brackets. All individual printed parts are relatively small, and there is minimal support required. I tried to reuse parts as much as possible to reduce the unique part count.

In addition to the sheet metal frame, I have designed a hotend mount with an integrated strain gauge. My hope is that the strain gauge can be used for experimentation to provide an objective measurement that can be used to troubleshoot errors, optimize print settings, and help gain better insight into the physics of the printing process. I also hope to use the strian gauge in the auto bed leveling process in place of an induction sensor, or limit switches. 

Here is a partial to-do list:

	• Bowden tube ingress location
	• Spool holder
	• Door
	• Carrying Handles
	• Power plug mount
	• e-stop switch
	• Webcam mount
		○ LED strip mount
	• Validate Bed design
	• Switches for vaious electronics parts
		○ Rpi
		○ Main power
		○ Relays
			§ Hot end fan
			§ PrintrBoard
			§ LEDs
			§ Heated bed
	• Design strain gauge logging interface
	• Write software to emulate z-switch based on strain gauge reading
	
	If you have any interest in helping, or questions about the design please reach out through github.
