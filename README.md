# Not So Original Prusa i3 MK2 Firmware

## General instructions

This branch originated from the latest (at the time of writing) supported Prusa firmware for MK2S (tag v3.2.3) - see http://prusa3d.com/downloads/firmware/

I have the MK42 bed attached at 90º to my MD3DP Y-axis and I had to update the bed calibration process to point to the new coordinates of the induction points.

With these changes MP3DP is able to run and print as if it's a Prusa i3 MK2S.

I also include a Platform IO configuration so code can be edited using VSCode instead of the jenky android builder -- also existing instructions with android didn't really work...

## Build instructions

### Step 1

Install VSCode and Platform IO extension

### Step 2

Open platformio.ini file using Platform IO extension

### Step 3

Build / Upload






