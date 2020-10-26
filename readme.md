Problem Statement
An Indian startup named 'Foodie' wants to build a conversational bot (chatbot) which can help users discover 
restaurants across several Indian cities. You have been hired as the lead data scientist for creating this product.
The main purpose of the bot is to help users discover restaurants quickly and efficiently and to provide a good 
restaurant discovery experience. 

Rasa Installation
Rasa Version     : 2.0.2
Rasa SDK Version : 2.0.0
Rasa X Version   : None
Python Version   : 3.8.5
Operating System : Linux-4.15.0-97-generic-x86_64-with-glibc2.10

Restaurant Search
Restaurant search based on the location, cuisine, budget

method for location, cuisine, budget, email etc.

Email Features 
 ask the user whether he/she wants the details of the top 10 restaurants on email. If the user replies 'yes', 
 the bot should ask for user’s email id and then send it over email. Else, just reply with a 'goodbye' message.
 
Deployment & Slack Integration
Integrated slack and fix the issue of rasa 2.0 to make the interaction with slack.
Github link of the rasa 2.0 issue: https://github.com/RasaHQ/rasa/pull/6986/files


Commands
rasa train
rasa train nlu
rasa train core
rasa run
rasa interactive
rasa shell
rasa run actions 
