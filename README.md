# CPRTPizzaBots
- For the same day start and submit competition, designed an Arduino-based robotic system to navigate an obstacle course through real-time line detection and path tracking.
- Utilized the parts at our disposal; this year, that was a colour sensor, DC motors, and paper plates and popsicle sticks for the frame, to create a closed feedback loop that could complete the competition challenge while carrying a load of pizza slices.

# Algorithm and Procedure
1. Calibrate RGB values on the colour sensor: program Arduino to calibrate the colour sensor with Red, Green, and Blue backgrounds with close and far measurements in order to determine how to sense the colour black (colour of tape)
2. Program vehicle motion: forward, reverse, turn right (left wheel faster than right wheel), and turn left (right wheel faster than left wheel).
3. Use the sensor data as input to determine vehicle motion: Performing a sweeping motion with the front of the vehicle, where the sensor is attached, to determine where the tape is and therefore which direction to move forward. Sweeping will occur due to the left wheel being set to a higher duty cycle for faster speed forward and then in reverse until black tape is detected. Then, it will re-adjust to be parallel to the detected tape and move forward to that spot before repeating.
4. Hopefully success and victory!

# Results

Placed third in the competition for farthest distance travelled in the obstacle course. Unfortunately, we were not able to finish the implementation of the ideas from the Algorithm and Procedure section, but outside-the-box thinking resulted in a last-minute solution with breadboard and wiring that achieved the fastest top speed in the competition.

# Future Implementations

Thinking forward to next year, improvements could definitely be made to task division and time management. Already, the group has begun brainstorming for how to improve our design, algorithms, and strategies to perform even better next year!
