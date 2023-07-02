# K40 Whisperer 0.64 TURBO

My fork of [K40 Whisperer](https://www.scorchworks.com/K40whisperer/k40whisperer.html) software by [Scorchworks](https://www.scorchworks.com/) with lot of UI additions and improvements focused on usability on touch screens.

![screenshot](https://github.com/AfBu/k40whisperer_turbo/blob/main/screenshot.png?raw=true)

## Main improvements:
* All UI elements on main screen has been scaled up to be pressed easily with finger.
* All buttons have different colors to make them more recognizable.
* Jog step/Speed/Passes inputs are accompanied with plus/minus buttons to easily change values.
* Laser movement (jog) is now possible in three step lengts (step * 1/10/20).
* Frame button will in sequence visit all border corners of current design. Great for checking design alignment.
* Added "Turbo" menu on right side of main screen
  * Fast Plot - disables rendering of vector data, speeding up refresh time on slower computer by significant amount.
  * Fullscreen - quickly toggle fullscreen mode
  * Advanced settings - quickly show/hide advanced settings
  * XY Store - stores current laser position in "Move to" inputs
  * XY Restore - restores position from which last laser operation was started
  * 5 slot system for settings presets
    * Load/Save button - switches mode of Slot button operation. If set to "Save" mode, pressing Slot button will save app configuration to that slot. If in "Load" mode, pressing Slot button will restore previously saved settings.
    * 1-5 Slot buttons - pressing will Load/Save settings to/from that slot number.
    * "D" Slot button - will Save/Load settings to/from default settings file loaded at startup.
   
All new icons were drawn by me, all are licensed as "public domain".

## Running / Installation
Please refer to original website/readme files how to run/package this software. I am not planning to release binary packages or installers.
