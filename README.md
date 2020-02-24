# ZumoBurglarAlarm
"Programming Things" Semester 2 Assignment 2 - Zumo burglar alarm - Alexander Noble, Cranston Parker, Andrew Gill

## Kanban Board
[Click here to visit our public Kanban Board](https://trello.com/b/q4ofF3vc/zumo-burglar-alarm-project)

## Project description
The idea behind this project is to have a swarm of robots approach an intruder, almost like a buglar alarm system. By using proximity sensors near a door, we can create a detection system that, when turned on, can relay information using MQTT to other devices about an object being detected. 

Our centralized information point will be on a laptop, that will support both the MQTT pub/sub server along with the GUI. The MQTT pub/sub server will post information back and forth between the proximity sensors and the Zumo robots in order for the robots to properly chase down a burglar. The GUI will also be able to enable/disable this system with an optional password system to lock it off. Additionally, the GUI will provide a set of logs which tells the user at what time different things happened.

## Visual diagram of the project
<p align="center">
<img src="https://i.imgur.com/c0u0SMA.png" 
alt="Diagram layout" width="704" height="450" border="10" />
</p>
