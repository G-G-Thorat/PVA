# RaspBerry-pi-Based-Help-Desk-ChatBot
A chatbot server application which can be deployed on a LAN environment as a Help desk Bot

PROBLEM THAT I TRIED TO SOLVE :-

This is a very common problem most of us faces everyday that is getting support or instructions for something that we want to use or we have to do or something for which we need help. Now i will give you an example as what exactly i want to do with what i have made, recently our college hold a tech symposium and there were a lot of events that were going on now we had spot registration that was going on and there were many many students who were coming to attend various different events now the problem was some  were clear with what they had to attend and how much they need to pay for the specific event but not everyone and we had limited poeple on the helpdesk so it was difficult to manage and it wasted a lot of time now from this i got an idea that why not put bots indtead of humans on this help desk to manage queries as those queres were very general and can be answeered by a bot. So i searched the internet as how i can do this and found some ideas and i implemented one of these. Now this chatbot is simple to implement and can be used easily as well.

Technical Description:-

THE APP-

Here i have used the Mit App Inventor 2 Platform to create a simple chat application which can be installed on the users mobile and as a basic version the user just need to put the ip address of the server in order to get connected. As soon as the user gets connected to the server he or she just need to speak up the wuery they have the app is having a google NLP processing which will convert the voice to text and send it to the server.The server will then reply with your answeer.

THE SERVER-

To get through with the scaleability and ease of deployment as well as cost effectiveness i have used the Raspberry Pi as a server we just need to connect our pi to the LAN and run the server Code that is written in python and we are done with it. For this basic version we also need to know the ip address of the pi to get connected to it through the mobile app. As pi can handel a lot of request and as it will be deployed in a LAN environement its very simple and easy to use it and we can just power up the pi any time and the server is up for use. It also contains a module which can capture the queries that are not there in its dataset and then the human operators can go through and just answeer those quesries and add them to the database. 

HOW TO DEPLOY:-

1. Copy the python code in your raspberry pi desktop.

2.Make necessary changes to the queries according to your needs.

3.Run the python code from your pi shell.

4.Note down the IP address of your Pi.

5.Install the application n your android mobile phone.

6.put the IP address of pi and click on connect.

7.Your are ready to chat.
