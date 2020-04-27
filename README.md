# Lobot
Lobot is a low-cost robotics platform that is designed to allow users to get to a point where they have a simple robot they can drive around remotely as quickly and cheaply as possible. The project is currently under heavy development but I thought I'd put something up to see if people are interested in the project (i.e. if it's worth my while continuing to develop it). Please bear with me it the documentation isn't great and functionality is a bit limited, this is my first open source project and I'm working on improving it whenever I get time.

Currently there is a demo Arduino application that allows the user to connect to Lobot via bluetooth and dirve it around by sending single letter commands:
- 'f' drives Lobot forward
- 'b' drives backwards
- 'l' turns left
- 'r' turns right
- Any other character will stop Lobot

The Arduino application also includes a WiFi over-the-air updater. Just set your WiFi network ID and key in the Arduino code. 
