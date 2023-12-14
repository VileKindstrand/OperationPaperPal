# OperationPaperPal
 Automatisk toalettpappersrulle

Constants and Variables:
Button Pins: buttonPinTwo is assigned to pin 2 for a button, and buttonStateTwo stores the button state.
Ultrasonic Sensor Pins: trigPin and echoPin are used for an ultrasonic sensor to measure distance.
Stepper Motor Pins: Pins motorUppNedPin1 through motorUppNedPin4 control the stepper motor.
Speed and Lookup Table: motorSpeed sets the speed of the stepper motor, and lookup is an array defining the stepper motor sequence.
Setup Function:
Initialization: The setup() function initializes pins for buttons, ultrasonic sensor, and stepper motor.
Loop Function:
Button Check: Checks if the button (buttonPinTwo) is pressed. If true, it triggers the motor to rotate until an obstacle is detected by the ultrasonic sensor.
SensorThing Function: Measures the distance using the ultrasonic sensor and prints it to the Serial Monitor.
Other Functions:
SensorThing Function: Measures the distance using the ultrasonic sensor and prints it to the Serial Monitor.
Fram and Bak Functions: Control the stepper motor to rotate in a forward or backward direction.
ActuallySpins Function: Calls either fram or bak function to actually make the motor spin.
SetOutputUppNed Function: Sets the output for the stepper motor based on a given sequence.
Additional Note:
The code seems to increment the wipe_count variable by 2 whenever the button is pressed.
If you have any specific questions about the code or if you need assistance with a particular aspect, feel free to ask!