# Smart-Door-Locking-System
My first IoT project in my college in the foundation lab - IoT in the first semester
Under the guidance of faculty, we learned, how to use an ESP32 microcontroller with Arduino cloud.
Components Used:
1. ESP32 Dev Module
2. PIR Sensor
3. Jumper Wire
4. Bread Board
Software used:
1. Arduino Cloud Agent
2. CP210X Driver
Using this, we create a connection between the laptop and ESP32.
Connect ESP32 with wifi for cloud connection.
These steps we learned from the reference video.
Link: https://youtu.be/gs7oFGpXdPk?feature=shared
Only for cloud connectivity. All other programs are by own and Faculty guidance.
Procedure:
1. Connect ESP32 with Wifi and Laptop.
2. Run led blink program(sample program) and check working properly.
3. Connect the components with respect pins. check the program for PIN connection
4. write the sensor program and upload it to the microcontroller
5. check no errors in the program
6. Open the serial monitor in the top-right corner of the sketch page
7. You can see ESP32 is connected with wifi and cloud connection
8. No motion Detected is printed
9. If the condition is True, Motion Detected is printed in the serial monitor, then the LED will blink.
10. In the dashboard, virtual led and message widgets are created and linked with the program.
11. The servo motor is used for door locking and opening.
12. If Motion is detected, the servo motor will rotate 180 degrees, then again come to normal position.

From this, we learned how to handle microcontrollers with Arduino cloud. This will help in future projects and PPT Presentations.
