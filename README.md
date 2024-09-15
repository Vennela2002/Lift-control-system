# Lift-control-system
# Introduction
IR-based lift control system uses infrared sensors to detect user inputs, such as hand gestures or button presses, to control the operation of a lift or elevator. When a person approaches or interacts with the system, the IR sensors send signals to the control unit, which processes the input and activates the lift accordingly. This system can enhance convenience, reduce physical contact, and improve hygiene, particularly in public settings.
# Methodology
The lift mechanism is inspired by a 3D printer, using a threaded rod, cylindrical rod, and two ball bearings, with a 3D printed connecting component.
The rods are driven by a stepper motor, controlled by a stepper motor driver.
A microcontroller manages the motor and LEDs.
IR sensors are installed on each floor to detect users; the lift moves to the requested floor while a person is detected.
If no person is detected, the lift proceeds to the nearest floor.
A servo motor operates the lift door, mounted on a rack and pinion system; the door remains closed if no person is detected after arrival.
Push buttons are placed on a horizontal dashboard separately from the lift, allowing users to call the lift and select floors.
# Conclusion
By using PIR sensors instead of IR sensors, we can improve energy conservation by automatically controlling the lift's light and fan based on motion detection. These sensors will turn the light and fan on or off as needed, enhancing efficiency. All these components can be integrated into the lift control system for seamless operation.
