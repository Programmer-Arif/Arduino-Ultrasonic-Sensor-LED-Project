# Arduino-Ultrasonic-Sensor-LED-Project
Arduino and Ultrasonic Sensor project with LEDs to measure the distance of objects like scale.

<h2>Description</h2>

This is an Arduino project using an HC-SR04 Ultrasonic Sensor and LEDs to measure the distance of objects, similar to a scale. When an object comes close to the HC-SR04 ultrasonic sensor, it indicates the distance using LEDs.

<h2>Requirements</h2>
<ul>
    <li><b>Arduino Uno Board</b></li>
    <li><b>HC-SR04 Ultrasonic Sensor</b></li>
    <li><b>Range:</b> 2cm to 400cm</li>
    <li><b>Operating Voltage:</b> 5V</li>
    <li><b>Measuring Angle:</b> 30 degrees</li>
    <li><b>Breadboard</li></b>
    <li><b>Jumper Wires</li></b>
    <li><b>7 x LEDs</li></b>
    <li><b>7 x 220Ω Resistors</li></b>
</ul>

<h2>Functionality</h2>

When the red LED is ON - the object's distance is 50cm.

When the yellow LED is ON - the object's distance is 4cm.

<h2>Features</h2>

The Arduino Ultrasonic Sensor LED project functions as a scale to measure an object's distance.

The measurement range can be extended by modifying the Arduino code.

The HC-SR04 sensor includes an ultrasonic transmitter and receiver module to accurately detect objects.

<h2>How It Works</h2>

The HC-SR04 Ultrasonic Sensor emits ultrasonic waves.

The waves reflect off an object and return to the sensor.

The time taken for the waves to return is used to calculate the distance.

The LEDs light up based on the measured distance.

<h2>Installation & Usage</h2>

Connect the components as per the circuit diagram.

Upload the Arduino code to the Arduino Uno Board.

Place an object in front of the sensor and observe the LED indicators.

<h2>Customization</h2>

Modify the threshold values in the Arduino code to change when the LEDs turn on.

Extend the range of the sensor by adjusting the code logic.
