# ESP32-Traffic-Lights
This repository shows traffic lights using esp32.

# Hardware Requirements
- Esp32
- 3 Led lights

# Wires Connection 
- Connect GND of esp32 with led 1 , 2 , 3 c's.
- Connect esp : 16 with the red led 'A'.
- Connect esp : 17 with the green led 'A'.
- Connect esp : 18 with the yellow led 'A'.

![connection](https://github.com/user-attachments/assets/b7a6daff-a1d5-4915-b198-4a36c188b258)

# Code

#define RED_LED 16

#define GREEN_LED 17

#define YELLOW_LED 18

void setup() {

  pinMode(RED_LED , OUTPUT);
  
  pinMode(GREEN_LED , OUTPUT);
  
  pinMode(YELLOW_LED , OUTPUT);
}

void loop() {

digitalWrite(RED_LED , HIGH);

delay(1000);

digitalWrite(RED_LED , LOW);

digitalWrite(GREEN_LED , HIGH);

delay(1000);

digitalWrite(GREEN_LED , LOW);

digitalWrite(YELLOW_LED , HIGH);

delay(1000);

digitalWrite(YELLOW_LED , LOW);
}

# Simulation Running 


https://github.com/user-attachments/assets/0a2e2bcb-8791-493d-80a6-b920bd3602e2

