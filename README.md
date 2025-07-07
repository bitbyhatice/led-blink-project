# led-blink-project
My first Arduino project: blinking an LED using pin 8.

# Arduino LED Blink Project 💡

This is my first Arduino project as an Electrical & Electronics Engineering student.

I connected an LED to pin 8 and made it blink every second using basic C code in the Arduino IDE.

## 🧠 What I Learned
- Using `pinMode()` and `digitalWrite()`
- Understanding `setup()` and `loop()` structure
- Building a basic circuit on breadboard
- Uploading code to Arduino Uno

## 🔌 Circuit
- 1 x LED
- 1 x 320Ω resistor
- Arduino Uno
- Breadboard and jumper wires
![circuit](https://github.com/user-attachments/assets/7f95b0a3-993a-4397-87fd-cb547a98fc2c)


## 🧾 Code

```c
void setup() {
  pinMode(8, OUTPUT);
}

void loop() {
  digitalWrite(8, HIGH);
  delay(500);
  digitalWrite(8, LOW);
  delay(500);
}
