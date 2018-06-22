# A-Speed-of-sound-measurer


This is a speed of sound measurer. It works for a range of temperatures. This is an arduino based simple project.
Materials:
          Hardware:
          1. Arduino UNO Board
          2. BreadBoard
          3. Ultrasonic Sensor HC-SR04
          4. Wires
          5. Ruler and a solid object.
          Software:
          1. Arduino IDE
          
This works on the formuls Speed=distance/pingtime. A ping generated from the sensor bounces off a surface at a known distance and then comes back to the sensor, where the ping time is measured using pulseIn() function, with HIGH parameter. Then we can print the speed of sound on a serial monitor.          
