# Table of content
1. About the wiper control system

    1. Description
    2. Identifying features
    3. 5W's & 1H
    4. S.W.O.T analysis
   
   
2. Requirements
     
     1. High level requriments
     2. low level requriments
 
3. Architecture

     1. Behavioural Diagram
     
           1. High Level Flow Chart Behavioural Diagram
           2. Low Level Flow Chart Behavioural Diagram
          
     2. Structural Diagram
     
4. Test plan and output
 
     1. High level test plan 
     2. loe level test plan
     3. sample outputs
     
# 1. About the wiper control system

   ##  Description
   * A wiper speed control framework for a car wiper controls the functional speed of a wiper as per downpour conditions. The control framework incorporates a downpour sensor (30) recognizing precipitation conditions to deliver . a simple sign having a plentifulness relying on the identified downpour conditions.
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
# 2. Requriments
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


  # 3. Architecture
## Behavioral Diagram
---
### High Level Flow Chart Behavioral Diagram
![2022-05-13](https://user-images.githubusercontent.com/101561930/168257272-8767bece-b4de-4dac-8e9b-45a160fc1fca.png)

### Low Level Flow Chart Behavioral Diagram

![2022-05-13 (1)](https://user-images.githubusercontent.com/101561930/168257463-708bef3d-cd6e-4210-8efc-d0c8cbabdf41.png)
-----
# Structural Diagram
![2022-05-13 (2)](https://user-images.githubusercontent.com/101561930/168257753-331aaeaf-170f-44f2-8bd7-3d63267e88c3.png)

# 4.  Test plan and Output
### Test plan is created and verified
## HIGH LEVEL TEST PLAN / Integrated test plan
| Test id | Description | Input | Expected output | Actual output |
|---------|-------------|-------|-----------------|---------------|
| 01 | Engine on | user button press once | car engine should on | car engine will on |
| 02 | Engine off | user button press twice | car engine should off | car engine will off |
| 03 | wiper on | user button press three times | car wipers should on | car wipers will on |
| 04 | wiper off | user button press four times | car wipers should off | car wipers will off |

## LOW LEVEL TEST PLAN
| Test id | Description | Input | Expected Output | Actual Output | Passed/Not |
|---------|-------------|-------|-----------------|---------------|------------|
| 01 | check for engine on | user button press once | red led should on | red led will on | passed |
| 02 | check for engine off | user button press twice | red led should off | red led will off | passed |
| 03 | check for wiper on | user button press three times | blue-green-orange led's should on in clock wise manner | blue-green-orange led's will on in clock wise manner | passed |
| 04 | check for wiper off | user button press four times | orange-green-blue led's should on in anti-clock wise manner | orange-green-blue led's will on in anti-clock wise manner | passed |

## Sample output
![1](https://user-images.githubusercontent.com/101561930/168250187-bac20481-ca0b-4207-9d56-3627ab6d4dd6.png)
![2](https://user-images.githubusercontent.com/101561930/168250277-ff4a650b-d51d-4245-8afe-ca0f260d605d.png)
![3](https://user-images.githubusercontent.com/101561930/168250349-1136fe18-d634-48de-8eb9-975f152ca806.png)
![4](https://user-images.githubusercontent.com/101561930/168250429-c3bba028-edc4-42e1-bc83-311165c06687.png)

   
   
     
  


