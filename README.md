# Garmin Applications
This is an informational page for my Garmin Projects

My Garmin Developer page can be found [here](https://apps.garmin.com/en-US/developer/d44894eb-c47f-4268-b66c-05665213045d/apps)

Launched Applications
-
### Applications
* [GPS Metrics App](https://github.com/GriffW/Garmin-Applications#gps-metrics-app)					
* [Stopwatch + Timer](https://github.com/GriffW/Garmin-Applications#stopwatch--timer)						

### Data Fields
* [Acceleration Field](https://github.com/GriffW/Garmin-Applications#acceleration-field)					
* [Bike Average Pace Field](https://github.com/GriffW/Garmin-Applications#bike-average-pace-field)			
* [Bike Pace Field](https://github.com/GriffW/Garmin-Applications#bike-pace-field)					
* [One Field](https://github.com/GriffW/Garmin-Applications#one-field) 	
* [Pace Histogram](https://github.com/GriffW/Garmin-Applications#pace-histogram)

### Watch Faces
* [Modern Digital](https://github.com/GriffW/Garmin-Applications#modern-digital)					
* [Simple Info Analog](https://github.com/GriffW/Garmin-Applications#simple-info-analog)					
* [Simple Info Face](https://github.com/GriffW/Garmin-Applications#simple-info-face)
* [Tach Face](https://github.com/GriffW/Garmin-Applications#tach-face)

### Widgets	
* [GPS Metrics](https://github.com/GriffW/Garmin-Applications#gps-metrics)
* [Run Log](https://github.com/GriffW/Garmin-Applications#run-log)
* [Orientate](https://github.com/GriffW/Garmin-Applications#orientate)				


Work Status
-
### Work In Progress
 * Unnamed data screen
 * Simple Info Face Version 1.2.0
	* [ ] Connect IQ 2.0 always on hand implemented

### Work Completed
* Bike Pace Fields 1.1.0
	> This update will change the units of the pace based on the device settings
* Stopwatch + Timer Version 2.0.0
	> This update is done from scratch, adding new features and a whole lot of new supported devices
	* [x] Major Changes Implemented
	* [x] FR 630 Supported Added
	* [x] Fenix 3 Series Supported Added
	* [x] Fenix Chronos/5S Series Supported Added
	* [x] Fenix 5/5X Series Supported Added	
	
# Applications
GPS Metrics App
-
[Store Link](https://apps.garmin.com/en-US/apps/e3d33aa5-7d07-4670-a754-9ad7de50562e)

### Application Info
GPS Metrics shows you, at a glance, your current direction, track (movement heading), speed, g-force, and Coordinates. 
  
All measures are accessed from the same screen. 
The units of altitude, coordinates, and speed can be chosen. 
There is a quick unit charger, as well as the option to show the UTC time instead of the local time. Degrees and compass direction can be swapped out for mils instead.
These options are configurable from inside of the app using the menu button (some watches menu's are accessed by holding the the up button).
 - The elevation options are: meters (m), feet (ft), and miles (mi). 
 - The coord options are: degree (DEG), degree minutes (DEG MIN), degree minutes seconds (DEG MIN SEC), and military grid reference system(MGRS) 
 - The speed options are: meters per second (m/s), kilometers per hour (km/h), miles per hour (mph), knots (knots), and mach number (mach). 
 - The select button functions as a unit changer. It can switch through all of the units of a specific field (altitude, coords, or speed). 
 - The "g force" only takes into account acceleration in the direction of your heading. The actual g force you might be experiencing might be higher. 
  
I have published an widget version of this widget than can be found here: 
https://apps.garmin.com/en-US/apps/42155349-ebb2-45c3-930e-51bbea912fa6 
  
#### Layout
- Cardinal Direction (Top Right) 
- Track (Top Right)  
- Altitude (Top Left) 
- Speed (Bottom Left) 
- Acceleration (Bottom Right) 
- GPS Coordinates (Middle) 
- Time (Top) 
  
### Version History
Version 2.1.4 - 6/20/2018
- [Added] Support for Fenix 5+ series

Version 2.1.3 - 6/18/2018
- [Fixed] Properly added support for Mils in the menu

Version 2.1.2 - 6/17/2018
- [Added] mils as an alternative to degrees+direction
- [Fixed] UTC not accounting for half hour time zone changes

Version 2.1.1 - 3/9/2018
- [Removed] VA3 support, it was added by accident

Version 2.1.0 - 2/17/2018
- [Added] support for D2 Charlie, Descent Mk1, and FR645
- [Modified] Reverted back to getting altitude and heading from GPS exclusivly
- [Modified] Significant code refactorization
- [Modified] Minor UI changes

Version 2.0.2 - 7/16/2017
- [Added] FR935 support

Version 2.0.1 - 6/19/2017
- [Fixed] no Fenix heading data 

Version 2.0.0 - 6/15/2017
- [Modified] Entire UI 
- [Added] unit changer
- [Removed] coords screen
- [Added] mach number speed unit
- [Added] UTC time option
- [Added] full Fenix support (1.0 and 2.0 models)
- Decreased memory usage by ~40%

Version 1.0.0 - 5/23/2016
- Initial Release 


Stopwatch + Timer
-
[Store Link](https://apps.garmin.com/en-US/apps/e31d8308-674a-403b-813f-298ce28c9eab)

### Application Info
Stopwatch + Timer gives you both tools in one functional package. 

#### Stopwatch
- The Stopwatch face has a precision of a tenth of second.
- The Laps view has a precision of milliseconds.
- The Lap view can bee seen even if the stopwatch is currently running.
- The watch stores 80 laps. All of which can be saved to the watch, and viewed in the laps screen by pressing the enter button
- On a new lap, a screen is shown for a short time that only shows the lap time and lap number. This can be turned off.
- Shows current clock time.

#### Stopwatch Controls
- Enter: Starts and stops stopwatch
- Back: Clears stopwatch, or closes the app if stopwatch is cleared and paused
- Down: laps stopwatch or switches to timer if the stopwatch is paused.
- Up: Switches to laps view

#### Timer
- Two timers can be run simultaneously
- Stopwatch can be run while timers are active. But there is currently no timer done alert if you are on a different page than the timer.
- The timer has a maximum duration of 24 hours and 59 minutes.
- The smallest increment is a second.
- the display shows the time remaining down to the second.
- Shows current clock time.

#### Timer Controls
- Enter: Pauses or starts selected timer
- Back: Clears timer, or closes the app if both timers are cleared and paused
- Down: Switches between timer
- Up: Switches back to timer

#### Laps
- Shows current laps and elapsed time on the stopwatch
- Saved laps are accessed on this page by pressing the enter/select button

#### Laps Controls
- Enter: Switches between saved and current laps
- Back: Returns back to stopwatch screen
- Down: Increments page number
- Up: Decrements page number

#### Menu
- Save Laps: on clicking this option the watch's laps will be send to Garmin Connect and can be found under Applications to Stopwatch + Timer to Settings.
- Accent Color: The accent color (default: white) can be changed through out the app to any of the other supported colors, except black. The reason that full color customization is not supported is because: In this app readability is more important than customization.
- Tones: Tones can be turned on or off here for the whole app.
- Vibrations: Vibrations can be turned on or off here for the whole app.
- Lap Screen: The lap screen that shows on a new lap can be turned off here. It might what to be turn off if laps need to be taken in quick succession.
- Power Mode: There are 4 power modes introduced. These help save battery if absolute immediate precision is not required. The record of time is still accurate. The stopwatch, and timer are still percise and correct. But they don't update as frequently. If you want to update the display manually: you can press any button, but the backlight button.
	- Normal [P0]: This behaves the exact same as the app has in the past. The real changes are in the following states.
	- Low Power [P1]: The stopwatch now updates every second, as opposed to every tenth of a second. The time recorded is still accurate to the millisecond.
	- Ultra Low Power [P2]: The stopwatch and timer now updates every minute. The timer still ends at the original time set.
	- Endurance [P3]: The stopwatch does not update until a button is pressed. The timer does not update, but still ends at the original time set.

- Device Info: Shows phone connection status, notification count, do not disturb status, alarm count, the current CIQ SDK  version number, and the current battery level. This screen updates when the enter button is pressed.

### Version History
Version 2.1.3 - 5/26/2018
- [Fixed] Timer starts too early

Version 2.1.2 - 5/26/2018
- [Fixed] Resuming a paused timer doesnt always works

Version 2.1.1 - 12/26/2017
- [Modified] Endurance behavior on timer. The timer behavies like the stopwatch now. The screen never updates on its own. It only updates when the timer is complete. 

Version 2.1.0 - 11/24/2017
- [Added] Power states. Check description for full info 
- [Added] Device Info. Allows you to check things such as battery, and phone status, without having to leave the app.

Version 2.0.1 - 10/11/2017
- [Fixed] Main Menu ailgnment issues on larger watches Fenix 5(x), etc...
- [Modifed] App Icon changes

Version 2.0.0 - 9/24/2017
- [Modified] Rewrote entire app from ground up
- [Added] Support for 2 timers
- [Added] Select seconds for timers
- [Modified] Controls layout
- [Modified] Laps are saved to device and can be accessed from laps menu
- [Added] Support for Fenix 3 family
- [Added] Support for Fenix 5 family

Version 1.2.5 - 12/26/2016
- Fixed crash on changing some settings

Version 1.2.4 - 12/15/2016
- Corrected button icons on 735XT

Version 1.2.3 - 12/15/2016
- Added support for 80 Laps
- Reduce memory usage
- Improved stability

Version 1.2.2 - 6/27/2016
- fixed crash on lap time being over an hour

Version 1.2.1 - 6/13/2016
- fixed an issue with changing the display type when hours is not 0

Version 1.2.0 - 6/12/2016
- Possible fix for the crash on startup issue. I won't know if it's fixed if I dont hear from you guys
- Added support for FR735XT
- A couple FR630 interface changes
- Timer now remembers last time set
- Added confirmation screen for exporting laps
- Added date and time to export screen

Version 1.1.0 - 4/22/2016
- Overhauled entire Input handling system. This was to address the limited support of the FR630. The FR630 experience is much more intuitive now. 

Version 1.0.0 - 4/22/2016
- Initial Release 


# Data Fields
Acceleration Field
-
[Store Link](https://apps.garmin.com/en-US/apps/b1d5b4a6-92dd-4e9e-b945-cf8f34db179c)

### Application Info
This field shows the acceleration in your current direction of travel. The actual acceleration will probably be higher, since I can only measure acceleration in one dimension. The field shows the coefficient of  the acceleration of gravity (g). Which is 9.81m/s^2 or 32.2 ft/s^2. So a 1.54g represents an acceleration of 1.54 times the acceleration of gravity. 

### Version History
Version 1.1.0 - 12/5/17
- [Added] support for a lot of devices
- [Modified] put unit "g" in data field, previously in label

Version 1.0.0 - 4/11/16
- Initial Launch

Bike Average Pace Field
-
[Store Link](https://apps.garmin.com/en-US/apps/5bcd8fd2-b151-421f-bb7b-d1bb6b1e65f1)

### Application Info
This field shows the average pace. This is the same as the pace metrics in Run mode, except that it does not round to a factor of 5. These pace metrics are not option in the Bike mode, so this field along with my Bike Pace Field(https://apps.garmin.com/en-US/apps/37f82059-0260-4750-b260-e2d6dbf491a3), makes these metrics available outside of Run mode. 

### Version History
Version 1.1.0 - 9/23/16
- Supports metric units
- Supports all Connect IQ devices at this time

Version 1.0 - 5/24/16
- Initial Launch


Bike Pace Field
-
[Store Link](https://apps.garmin.com/en-US/apps/37f82059-0260-4750-b260-e2d6dbf491a3)

### Application Info
This field shows the pace. This is the same as the pace metrics in Run mode, except that it does not round to a factor of 5. These pace metrics are not option in the Bike mode, so this field along with my Bike Average Pace Field(https://apps.garmin.com/en-US/apps/5bcd8fd2-b151-421f-bb7b-d1bb6b1e65f1), makes these metrics available outside of Run mode. 

### Version History
Version 1.1.0 - 9/23/16
- Supports metric units
- Supports all Connect IQ devices at this time

Version 1.0 - 5/25/16
- Initial Launch
 
 
One Field
-
[Store Link](https://apps.garmin.com/en-US/apps/33528a69-baf9-45ff-9a8a-8bb32bd391a3)

### Application Info
One Field allows for more fields that Garmin allows by default.
One Field is comprised of the following things:
- GPS Signal Indicator
- Local Time
- Current Cardinal Direction
- 6 or 3 Custom fields
- Steps
- Total Activity Timer
- Current Battery Percentage
- Bar

#### Custom Fields
| **Field** | **Field Label** |
| -- | -- |
| Distance | (distance unit) |
| Current Lap Distance | (distance unit) |
| Immediate Pace | IP |
| Average Pace | P |
| Current Lap Pace | P |
| Immediate Speed | S |
| Average Speed | AS |
| Max Speed | MS |
| Current Lap Time | lap |
| Last Lap Time	| LL |
| Immediate Heart Rate | HR |
| Average Heart Rate | AHR |
| Elevation | (elevation unit) |
| Calories | cal |
| Laps | lap|

#### Other Options
Invert Colors: Inverts the colors of the whole field.
Only 3 Fields: Changes the layout of the screen to only show 3 fields instead of 6.
Speed units: The 3 speed units supported are m/s, kph, and mph.
Bar: The bar can either reflect how much battery is left, or the current step goal progress.

#### Notes
Laps created in Garmin workouts do not work.
This is a Garmin issue: https://forums.garmin.com/showthread.php?359067-Datafield-OnTimerLap-with-workout-file#post901539
Every data field (not app, data field) that handles lap metrics will also have this issue

### Version History
Version 1.0 - 4/11/16
- Initial Launch


Pace Histogram
-
[Store Link](https://apps.garmin.com/en-US/apps/5da3c791-c577-4778-a49f-fcb9a9b7fe77)

### Application Info
Pace histogram allows you to see a live histogram of pace, during an activity, over a certain period.

This graphical information is usually only seen in Garmin Connect, after the completion of an activity. Now you can see how your pace is changing with great accuracy over a certain interval.
The default interval, or resolution, is 1 mile.
This can be reconfigured as any integer, miles or kilometers.
This histogram stores 50 points of data, regardless of the resolution chosen. There is some smoothing done on the incoming pace data to eliminate large pace spikes.
The upper and lower y bounds of the histogram are set by the fastest and slowest pace in the 50 points currently  show in the histogram. 

### Options
* Distance Scope: The histogram will show you the pace data for the last x miles or kilometers.
* Distance Units: This defines what units are to be used with the distance scope above. Feel free to mix and match metric and imperial. It doesn't matter which are the system units.
* Show Min/Max: This option will show the min and max pace that the graph is constrained by.

#### Notes
Changes cannot be made to [Distance Scope] and [Distance Units] settings during an activity. To have the data field reflect the new settings, exit out of the activity screen completely, and relaunch.

### Version History
Version 1.0.0 - 12/27/2017
- [Note] Initial Release


# Watch Face
Modern Digital
-
[Store Link](https://apps.garmin.com/en-US/apps/6f8a64a8-754f-4cfd-bf6c-0e6d8a13784e)

### Application Info
#### Features
- Time: Shows current time. 12 hour, 24 hour, and leading zero formats supported. [Color customizable]
- AM/PM Seconds: AM/PM is show while in 12 hour mode. This can be disabled in 12 hour mode This is also where seconds will be show if they are enabled in the settings, and the watch is active (on some devices).* [Color customizable] [Always-On feature]
- Date: Shows current date with 3 formats. [Day of Week] [Month] [Date], [Day of Week] [Date] [Month], [Date] [Day of Week] [Month], [Day of Week] [Date], [Date] [Day of Week]. [Color customizable]
- Steps: Shows current steps, can be disabled in the settings. [Color customizable]
- Battery: Shows current battery as a percentage, can be disabled in the settings. [Color customizable]
- Bars: There are 2 customizable bars on this watch face. Each can be controlled independently with the choices of hiding the bar, showing steps progress, showing battery, or showing the move bar. [Color customizable]
- Bluetooth Icon: This Icon changes from gray to white (or black in the cause of a white primary color) and is surrounded by the accent color, when the watch is connected to a phone.
- Do not disturb icon: This icon will be shown when do not disturb is active (only supported on Fenix 2.0 devices). When active, this status is alwasy shown over notifications
- Notification Icon: This Icon changes from gray to white (or black in the cause of a white primary color) and is surrounded by the accent color, when there are notifications on the connected device.
- Alarm Icon: This Icon changes from gray to white (or black in the cause of a white primary color) and is surrounded by the accent color, when there are alarms active on the watch.
- Background: The default background is black carbon fiber, but can be removed in the settings, for plain black. 
- Seconds Bar: This bars show a graphical view of the current seconds, which can be disabled in the settings, and is off by default. [Color customizable] [Always-On feature]
- Primary Color: This color makes up the outlining of the two rounded rectangles and the color of the various status icons. [Color customizable]
- Secondary Color: This color makes up the outlining of the two customizable bars. [Color customizable]

#### ATTENTION

****The seconds will only display if the watch is active. Active is when the watch is gestured to be looked at (the exact same way the wrist-turn backlight option works), or when the watch face is switched to. Active means that your watch face updates every second as opposed to every minute. For this reason the seconds are only displayed when active. Otherwise if the seconds are left up that info will be inaccurate. This is the only fluid way to show seconds. I do think that it would make a lot of sense to have button presses/backlight also trigger the active mode, but this is out of my hands. So please do not email me and ask why seconds won't stay on.****


### Version History
Version 1.1.0 - 10/17/2017
- [Added] Support for Fenix 2.0 Devices
- [Added] Always on seconds, and seconds bar for supported devices (Fenix 2.0 Devices)
- [Added] Do not disturb icon, for supported devices (Fenix 2.0 Devices)
- [Added] Option to disable AM/PM label for 12hr formats
- [Added] 2 new date formats: "Jan 01", "01 Jan"
- [Modified] Slight restructuring of status icon area

Version 1.0.3 - 4/5/2017
- [Fixed] Date formats properly added

Version 1.0.2 - 3/22/2017
- [Modified] Changed default color scheme

Version 1.0.1 - 3/22/2017
- [Removed] Fenix Chronos support removed since it only has 32kB of memory for the watch face. 50% of the rest of the fenix line

Version 1.0.0 - 3/22/2017
- Initial Launch


Simple Info Analog
-
[Store Link](https://apps.garmin.com/en-US/apps/a2cf87c3-3782-4860-bcbf-7863683b5336)

### Application Info
This watch face contains 2 base styles:
- Digital Analog
- Performance Analog

The Digital Analog is the most customizable style.
- The top holds the status bar, which shows Bluetooth, notification, and alarm status.
- There are 2 bars on either side of the watch that can be turned off, or show step progress, move bar, or battery status. The colors of these bars can be changed. 
- The color of these bars can also change if its value is under 20% of the step goal or battery life.
- Icons for the step goal, or batter can be turned too.
- The battery and step labels can be turned off, and their color can be changed.
- The date (Date format: [Day of Week] [Month] [Date]) sits below, and the color can be changed.
- Alternate formats are [Day of Week] [Month] [Date], [Day of Week] [Date] [Month], [Date] [Day of Week] [Month], [Day of Week] [Date], [Date] [Day of Week].

The Performance Analog takes a lot of points from the new Cadillac Cluster, and integrates it into this style.
- The top holds the status bar, which shows Bluetooth, notification, and alarm status.
- On the sides are 2 gauges. What they display cannot be changed, and they can be turned off. Their colors can be changed.
- The battery and step labels can be turned off, and their color can be changed.
- The date (Date format: [Day of Week] [month] [date]) sits below, and the color can be changed.

The watch hand color can also be changed, and the second hand color can be changed or disabled.

More info can be found here: https://github.com/GriffW/Garmin-Applications#simple-info-analog

#### ATTENTION
- There are plans to add the new always on second hand (FOR SUPPORTED DEVICES). It will take more time than expected to implement this feature, it is not in this 1.1.0 patch.

- ****The seconds will only display if the watch is active. Active is when the watch is gestured to be looked at (the exact same way the wrist-turn backlight option works), or when the watchface is switched to. Active means that your watch face updates every second as opposed to every minute. For this reason the seconds are only displayed when active. Otherwise if the seconds are left up that info will be inaccurate. This is the only fluid way to show seconds. I do think that it would make a lot of sense to have button presses/backlight also trigger the active mode, but this is out of my hands. So please do not email me and ask why seconds won't stay on.****


### Version History
Version 2.0.3 - 9/9/2018
- [Fixed] issue with last second hand artifact
- [Fixed] notification misalignment with no alarms active

Version 2.0.2 - 6/23/2018
- [Fixed] Date, battery, and steps clipping on VA3
- [Added] Support for VA3M and F5+ series

Version 2.0.1 - 5/5/2018
- [Fixed] Issue where minutes hands would not be shown during specific times.
- [Fixed] Issue where Black VA3 devices did not display elements correctly
- [Fixed] Reduced memory usage drastically to fix rare instances of memory crashes

Version 2.0.0 - 4/29/2018
- [Added] Support for 1Hz always on second hand (for supported devices)
- [Modified] Drastically reduced watchface app size
- [Modified] Rewritten entire watchface
- [Added] Support for VA3
- [Added] Support for FR645(M)
- [Added] Support for Descent MK1
- [Added] Two new date formats: [Day of Week] [Date], [Date] [Day of Week].

Version 1.1.1 - 7/18/2017
- [Modified] Background system: The app size is much larger than it was in 1.1.0, but this allows for much smoother performance of loading and unloading of the face, on 1.0 devices (FR230, Fenix 3, etc.). Connect IQ 2.0 devices should not be affected by this change, besides the larger download size.

Version 1.1.0 - 7/9/2017
- [Note] There are plans to add the new always on second hand (FOR SUPPORTED DEVICES). It will take more time than expected to implement this feature, it is not in this 1.1.0 patch.
- [Added] Support for Fenix 5 & 5X 
- [Added] Support for Fenix 5S & Chronos
- [Added] Support for Forerunner 935
- [Removed] Face image, drawn entirely on device
- [Modified] Fenix 1.0 fonts used
- [Added] Full hand coloring
- [Added] Invert option
- [Added] Bar Icon option
- [Added] Low percentage bar color (less than 20%)
- [Added] Option to disable gauges on performance face
- [Modified] Moved some coord calculations off onUpdate(), should improve battery life

Version 1.0.2 - 3/18/2017
- [Fixed] Right steps bar wraps around at low step count
- [New Feature] Added multiple date formats

Version 1.0.1 - 8/17/2016
- [Fixed] Performance style step gauge resets after step goal
- [Fixed] Typo in settings

Version 1.0.0 - 8/7/2016
- Initial Launch


Simple Info Face
-
[Store Link](https://apps.garmin.com/en-US/apps/91014c51-68a9-49b0-b3b3-00db139cfd9b#0)

### Application Info
Features:
- 12/24 hour support with accented hour color
- Date format: Day of Week, Month, Date; Day of Week, Date, Month; Date, Day of Week, Month
- Shows Seconds*
- Battery and percent icon, color changes with charge
- Bluetooth icon, blue when connected, gray when not
- Alarm icon, displayed when there is an alarm active
- Notification icon, displays number of notifications at a glance
- Shows Steps
- Shows Move Bar OR Steps to goal progress
- Hour, Minute, AM/PM, Date, Seconds, Steps, and Bar color can all be independently changed through the settings.

#### Notes

- *The seconds will only display if the watch is active. Active is when the watch is gestured to be looked at (the exact same way the wrist-turn backlight option works), or when the watchface is switched to. Active means that your watch face updates every second as opposed to every minute. For this reason the seconds are only displayed when active. Otherwise if the seconds are left up that info will be inaccurate. This is the only fluid way to show seconds. I do think that it would make a lot of sense to have button presses/backlight also trigger the active mode, but this is out of my hands.

- I probably wont be adding a move bar, it doesn't really fit into the style.


### Version History
Version 1.3.2 - 3/18/2017
- [New Feature] Added multiple date formats

Version 1.3.1 - 6/12/2016
- Added Seamless Steps Mode

Version 1.3.0 - 6/12/2016
- Added missing pink and purple color selections
- Added move bar (only one bar supported at a time)
- Added steps to goal progress bar (only one bar supported at a time)
- Added support for: FR735XT
- Changed location of time when using 24 Hour time format

Version 1.2.1 - 4/4/2016
- Status icons off center, Fixed
- Date off center, Fixed

Version 1.2.0 - 3/26/2016
- Blue and Dark Blue were labeled incorrectly, actually fixed now, for real this time
- Added Optional Seconds to watchface
- Seconds color and Seconds option added to the Options menu
- Resized AM/PM label

Version 1.1.2 - 3/15/2016
- Blue and Dark Blue were labeled incorrectly, Fixed

Version 1.1 - 3/15/2016
- Changed to layout, loads quicker
- Icons more uniformly spaced
- Added steps
- Hour, Minute, AM/PM, Date, and Steps color can all be independently changed through the settings.
- Steps can be hidden through the settings

Version 1.0 - 3/7/2016
- Initial Launch


Tach Face
-
[Store Link](https://apps.garmin.com/en-US/apps/2dc815d7-9243-4345-8c9e-dc8b13ef6cc8)

### Application Info
Top Tach:
- Shows visual display of seconds
- redline style can be disabled to allow for a single color
- the gray background can be disabled
- the tach color can be changed

Date:
- The date (Date format: [Day of Week] [Month] [Date]) sits below, and the color can be changed.
- Alternate formats are [Day of Week] [Month] [Date], [Day of Week] [Date] [Month], [Date] [Day of Week] [Month], [Day of Week] [Date], [Date] [Day of Week].

More info can be found here: https://github.com/GriffW/Garmin-Applications#tach-face

HR:
- This value can be hidden, and the color can be changed

AM/PM:
- This value can be hidden, and the color can be changed

Status Icons:
- The color can be changed

Battery Bar:
- The color can be changed of the bar and the battery value
- The color of the bar below 20% can also be changed

Steps Bar:
- The color can be changed of the bar and the steps count
- The color of the bar below 20% can also be changed

### Version History
Version 1.0.0 - 5/19/2016
- Initial Launch


# Widgets
GPS Metrics
-
[Store Link](https://apps.garmin.com/en-US/apps/42155349-ebb2-45c3-930e-51bbea912fa6)

### Application Info
GPS Metrics shows you, at a glance, your current direction, track (movement heading), speed, g-force, and Coordinates. 
  
All measures are accessed from the same screen. 
The units of altitude, coordinates, and speed can be chosen. 
There is a quick unit charger, as well as the option to show the UTC time instead of the local time. Degrees and compass direction can be swapped out for mils instead.
These options are configurable from inside of the app using the menu button (some watches menu's are accessed by holding the the up button).
 - The elevation options are: meters (m), feet (ft), and miles (mi). 
 - The coord options are: degree (DEG), degree minutes (DEG MIN), degree minutes seconds (DEG MIN SEC), and military grid reference system(MGRS) 
 - The speed options are: meters per second (m/s), kilometers per hour (km/h), miles per hour (mph), knots (knots), and mach number (mach). 
 - The select button functions as a unit changer. It can switch through all of the units of a specific field (altitude, coords, or speed). 
 - The "g force" only takes into account acceleration in the direction of your heading. The actual g force you might be experiencing might be higher. 
  
I have published an app version of this widget than can be found here: 
https://apps.garmin.com/en-US/apps/e3d33aa5-7d07-4670-a754-9ad7de50562e 

#### Layout
- Cardinal Direction (Top Right) 
- Track (Top Right) 
- Altitude (Top Left) 
- Speed (Bottom Left) 
- Acceleration (Bottom Right) 
- GPS Coordinates (Middle) 
- Time (Top) 

### Version History
Version 2.1.4 - 6/20/2018
- [Added] Support for Fenix 5+ series

Version 2.1.3 - 6/18/2018
- [Fixed] Crash on tones toggle

Version 2.1.2 - 6/18/2018
- [Fixed] Properly added support for Mils in the menu

Version 2.1.1 - 6/17/2018
- [Added] mils as an alternative to degrees+direction
- [Fixed] UTC not accounting for half hour time zone changes
- [Added] Brought menu from the app version to the widget version

Version 2.1.0 - 2/17/2018
- [Added] support for D2 Charlie, Descent Mk1, and FR645
- [Modified] Reverted back to getting altitude and heading from GPS exclusivly
- [Modified] Significant code refactorization
- [Modified] Minor UI changes

Version 2.0.1 - 6/19/2017
- [Fixed] no Fenix heading data 

Version 2.0.0 - 6/15/2017
- [Modified] Entire UI 
- [Added] unit changer
- [Removed] coords screen
- [Added] mach number speed unit
- [Added] UTC time option
- [Added] full Fenix support (1.0 and 2.0 models)
- Decreased memory usage by ~40%

Version 1.1.8.2 - 9/28/2016 
- Added 735XT support (Again) 
  
Version 1.1.7 - 9/19/2016 
- Added 735XT support 
  
Version 1.1.6 - 5/22/2016 
- Widget now stable 
  
Version 1.1.0 - 5/22/2016 
- Removed current coordinates system 
- Added new screen accessed by the select button that show coordinates 
- Added Knots 
  
Version 1.0.0 - 4/4/2016 
- Initial Release

Run Log
-
[Store Link](https://apps.garmin.com/en-US/apps/14435ee9-1bd2-4625-8ad1-946e3d72bfc6)

### Application Info
Ever wanted to take a look at your historical run data on your watch?
Run log allows you to view information about all saved runs on your watch.
Take a look at how much you are running in the scope of a week, a month, or even a year.
Change the view mode in the menu.

Run Log can show you your current weekly and monthly mileage in the glace view.
The glace view will update automatically as your run.

### Version History
Version 1.0.0 - 08/11/23
- initial release
  
Orientate
-
[Store Link]()

### Application Info
Ever wanted an attitude indicator on your wrist? Or wanted to better understand the terrain that you find yourself in.
Orientate formats your watch's sensors into an intuitive format, pioneered by the aviation world, bringing a type of attitude indicator to your wrist.
You can find your current pitch and roll value, or discern where the horizon if you find yourself update down or in a precarious position.

### Version History
Version 1.0.0 - 11/20/23
- initial release
