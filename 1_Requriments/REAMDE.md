# About Wiper Control System
# Abstrat
For this project, we have used the STM32F4xx-discovery board to display the vehicle filter control system. Most car wires are controlled by a DC motor, however because the STM32F4xx-discovery does not have an engine, we test using LEDs in this application. For example, wiper control system. The STM32F4xx-discovery board has four LEDs and a Push Button. The colors of these LEDs are orange, green, red and blue. Current limit resistance connects four user LEDs to PD12, PD13, PD14, and PD15 PORTD pins on the Recovery board. To activate the push button with the STM32F407VG controller, GPIO PINs will be set as digital input pins. When you press and hold the user button for two seconds, Red When the ignition key is set to ACC, the LED turns on. In addition, the LEDs flash, indicating that the wipers are on.

## Discription
* A wiper speed control framework for a car wiper controls the functional speed of a wiper as per downpour conditions. The control framework incorporates a downpour sensor recognizing precipitation conditions to deliver . a simple sign having a plentifulness relying on the identified downpour conditions.
---
## Identifying Features
* It shall on the engine when the button is pressed once.
* It shall off the engine when the button is pressed twice.
* It shall turn on the wiper when the buttun is pressed 3 times.
* It shall turn off the wiper when the buttun is pressed 4 times.
---
## 5W's & 1H
### What
* Wiper control systen for car.
### Where 
* Out side a car.
### when 
* when we want to clean the front mirror.
### who 
* People who have the car and drive the car.
### Why
* For cleaning the dust particles or water drops.
### How
* Using multiple pushes on a button.
---
## SWOT Analysis
### Strength
* It is easy to clean the dust particles on the mirror.
* Manages all the commands with one button automically.
* Encryption in data.
---
### Weakness
* While driving the car it causes distubance.
* Wait for curtain time after every command to press new command.
* It is sensitive.
---
### Opportunites
* Can be used where we need to send secure commands to car.
* The scope the system is very use full in the car.
* It is very less in the cost.
---
### Threats
* When new commnd is given with out completing the current command it will not take current command.
---
## High Level Requrements
| ID | High Level Requriments | Status |
|----|-------------------------| ------|
| HLR1 | It shall on the engine | Implemented |
| HLR2 | It shall off the engine | Implemented |
| HLR3 | It shall turn on the wiper | Implemented |
| HLR4 | It shall turn off the wiper | Implemented |
---
## Low Level Requeiments
| ID | Low Level Requriments | Status |
|----|-----------------------|--------|
| LLR1 | If user button pressed once red led will be on | Implemented |
| LLR2 | If user button pressed twice red led will be off | Implemented|
| LLR3 | If user button pressed 3 times blue-green-orange led's will be on in clock wise manner | Implemented |
| LLR4 | If user button pressed 4 times orange-green-blue led's will be on in anticlock wise manner | implemented |
