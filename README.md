# Portfolio

## Introduction
The Bible Chatbot will help users feel closer to God by giving them a Bible verse of the day. The Bible verse will be saved in a text file and can be repeated until a new verse is requested. The used verses will be saved for 5 runs of the application. This will be using a device that is communicating with a Speaker and Microphone to give the user the Bible verse. This application will use Raspberry Pi, speaker, and microphone. This project can help people fill an empty void that they have from not being in God’s Word. 

## Requirements
### Non-Functional
1. User have the ability to command the chatbot to state a Bible Verse by saying "Bible"
2. User have the ability to command the chatbot to repeat the last used Bible Verse by saying "Repeat"
3. The application to be able to repeat the last used Bible Verse
4. The application to remove the oldest verse after running the application 5 times
5. Have the chatbot respond with a Bible Verse in an audio form
6. The verse to be stated back to user in the order of Book, Chapter, and Verse
### Functional
1. Chatbot respond to user with Bible Verse within 30 seconds
2. Chatbot respond to user with Error Message within 30 seconds
3. Chatbot saves used verse to "history.txt" within 30 seconds

## Technologies
Technologies that were used for this application was:
1. Python 3
2. Raspberry PI
3. Google Text-to-Speech
4. Google Speech-to-Text
5. Samson Microphone
6. Logitech Speakers
### Picture of main Hardware for the chatbot
![](Device.png)
## Diagrams

### UML Diagram
![](uml.png)
### Sequence Diagram
The Sequence Diagram shows the flow of the application. With only having one class, the application goes does a self call throughout the entirety of the application, as well as calling out to gTTS which is Google Text-to-Speech
![](SequenceDiagram.png)
### Flowchart Diagram
![](Flowchart.png)
### Logical Design Diagram
![](LogicalDesign.png)
### Physical Design Diagram
![](PhysicalDesign.png)
## Risk and Challenges
With this project there were a lot of risk and challenges that came up. 
## Outstanding Issues



