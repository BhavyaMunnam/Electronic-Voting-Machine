# **Electronic Voting Machine (EVM)**
This project is a simple Electronic Voting Machine designed using a microcontroller. The aim of this project is to understand how electronic voting works and how embedded systems can be used to automate real-world processes.
The system allows voters to cast their votes by pressing a button assigned to a candidate. Each vote is recorded accurately by the controller, and the final results are displayed on an LCD screen. This project helps in eliminating manual counting errors and makes the voting process faster and more reliable.

## **Objectives**
- To design a basic electronic voting system
- To understand microcontroller interfacing
- To demonstrate vote counting using embedded systems
- To reduce human error in vote calculation

 ## **Technologies Used**
- Embedded C
- Microcontroller (Arduino)
- Tinkercad
- Push buttons and LCD display

 ## **Components List**

 | Reference | Quantity | Component Description |
|----------|----------|----------------------|
| U1 | 1 | Arduino Uno R3 |
| U2 | 1 | MCP23008-based LCD 16×2 (I2C, Address: 0x20) |
| S1, S2, S3, S4, S5 | 5 | Push Button |
| D1 | 1 | Red LED |
| D2 | 1 | Green LED |
| R1 | 1 | 1 kΩ Resistor |

 ## **Working**

When the system is powered on, it waits for a voter input. The voter presses the button corresponding to a candidate. The microcontroller registers the vote and stores it. After voting is completed, the result button is pressed, and the total votes for each candidate are shown on the LCD.

 ## **Features**
- Simple and user-friendly design
- Accurate vote counting
- Fast result display
- Suitable for small-scale elections and academic use

## **Applications**
- College and school elections
- Student projects
- Embedded systems learning

 ## **Future Improvements**
- Adding voter authentication
- Password-protected result access
- Wireless result transmission
- Biometric verification
