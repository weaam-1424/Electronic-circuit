# Electronic-circuit
### Connecting and programming an electronic circuit containing 6 servo motors using the (Tinkercad) simulation program.

### Electronic circuit programming code(text):

```
// C++ code
//
#include <Servo.h>

Servo servo_12;

Servo servo_11;

Servo servo_10;

Servo servo_9;

Servo servo_8;

Servo servo_7;

void setup()
{
  servo_12.attach(12, 500, 2500);
  servo_11.attach(11, 500, 2500);
  servo_10.attach(10, 500, 2500);
  servo_9.attach(9, 500, 2500);
  servo_8.attach(8, 500, 2500);
  servo_7.attach(7, 500, 2500);
}

void loop()
{
  servo_12.write(90);
  servo_11.write(90);
  servo_10.write(90);
  servo_9.write(90);
  servo_8.write(90);
  servo_7.write(90);
  delay(10); // Delay a little bit to improve simulation performance
}
```
### Electronic circuit programming code(blocks):

<img width="554" alt="كود برمجة الدائره 1" src="https://github.com/weaam-1424/Electronic-circuit/assets/173771361/a14e52ac-f5c4-44c8-ab70-b17a7272520d">


#### Before operation :
<img width="775" alt="الدائره الكهربائيه1" src="https://github.com/weaam-1424/Electronic-circuit/assets/173771361/89507c0a-accb-486f-bed2-7c81a6b213f1">


#### After operation :
<img width="758" alt="تشغيل الدائره " src="https://github.com/weaam-1424/Electronic-circuit/assets/173771361/6559bf89-19f1-4083-b807-618e9e17c60d">


#### Click to enter the tinkercar website :
[](https://www.tinkercad.com/things/0zCNwiskymx-electronic-circuit) 
(https://www.tinkercad.com/things/0zCNwiskymx-electronic-circuit)
