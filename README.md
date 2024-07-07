# Electronic-circuit
### Connecting and programming an electronic circuit containing 6 servo motors using the (Tinkercad) simulation program.
# Electronic circuit programming code:
    
    #include <Servo.h>

    Servo myServo1, myServo2, myServo3, myServo4, myServo5, myServo6;

    void setup() {
    myServo1.attach(13);
    myServo2.attach(12);
    myServo3.attach(11);
    myServo4.attach(10);
    myServo5.attach(8);
    myServo6.attach(7);
    }

    void loop() {
    // Move all servos from 0 to 90 degrees
    for (int pos = 0; pos <= 90; pos += 1) {
    myServo1.write(pos);
    myServo2.write(pos);
    myServo3.write(pos);
    myServo4.write(pos);
    myServo5.write(pos);
    myServo6.write(pos);
    delay(15);
    }

    // Move all servos from 90 to 0 degrees
    for (int pos = 90; pos >= 0; pos -= 1) {
    myServo1.write(pos);
    myServo2.write(pos);
    myServo3.write(pos);
    myServo4.write(pos);
    myServo5.write(pos);
    myServo6.write(pos);
    delay(15);
     }

    delay(2000); // Delay before repeating
    }
# Before operation :
![Screenshot 2024-07-08 005656](https://github.com/sarah-Ahmed-99/Electronic-circuit/assets/174282340/50d98dfd-7b69-46c6-87f8-4b132ae9ee8b)

# After operation :
![Screenshot 2024-07-08 013842](https://github.com/sarah-Ahmed-99/Electronic-circuit/assets/174282340/cadc29bd-d522-42dd-ac39-76c1958fd43d)


