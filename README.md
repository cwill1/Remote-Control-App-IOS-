# Remote-Control-App-IOS-

1. Creates a two-screen version of the mock remote control app in Programming
Assignment #4. The first screen is similar to the app in Programming Assignment #4.
The second screen is a mock remote control for a DVR. The screens should be similar
to the ones below.

2. The TV remote control portion functions similarly to a standard remote control.
3. The DVR remote control mimics the usual functions of a simple DVR remote control.

a. The power switch will turn “My DVR” on and off. When the power is off, all
other controls on the remote are disabled.
b. The DVR is always in one of the following states, exclusively (i.e., never in two or
more states simultaneously):
• Stopped
• Playing
• Paused
• Fast forwarding
• Fast rewinding
• Recording
Each of the above state is entered when the corresponding button is pressed.
When the power is turned on, the DVR will be in the Stopped state.
c. The “Play” button will start or resume normal playing. Pausing, fast forwarding
or rewinding is only possible when the DVR is in the Playing state.
d. The “Record” button will start recording. Recording can only start when the
DVR is in the Stopped state. Playing, pausing, fast forwarding or rewinding is not
possible when the DVR is in the Recording state.
e. The “Stop” button will stop any operation.
4. When a button is pressed while the DVR is in a state 

4. When a button is pressed while the DVR is in a state where the requested operation is
not possible, an action sheet will popup with an appropriate warning message. The
action sheet will offer two options:
a. Cancel the requested operation, and the DVR will remain in the current state.
b. Force the requested operation by stopping the current operation first. If this
option is selected, an alert will popup confirming that the current operation has
been stopped and the requested operation proceeds.
5. The toolbar at the bottom contains a button to switch between the TV and DVR
modes. The transition between the TV remote screen and the DVR remote screen
should be animated. The text on the switch button changes depending on
whether the current screen is TV or DVR remote. 

![alt text](https://github.com/cwill1/Remote-Control-App-IOS-/blob/master/remotescreen.png)
![alt text](https://github.com/cwill1/Remote-Control-App-IOS-/blob/master/vcrscreenpng.png)
![alt text](https://github.com/cwill1/Remote-Control-App-IOS-/blob/master/programscreen.png)
