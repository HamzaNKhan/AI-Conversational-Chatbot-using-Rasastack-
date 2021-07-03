# AI-Conversational-Chatbot-using-Rasastack

## Problem Statement 01
* Organizations have to provide customer service for 24/7 to their clients, for that chatbots are a very innovative feature. 
* But mostly chatbots being used aren’t dynamic; they work on the already stored set of answers which they utter when specific set of condition fulfils. 

## Problem Solution
* Our project is based to cover this flaw, This works on Artificial Intelligence and generates the answer at real time using live data.

* Using this users can actually have a conversation unlike a traditional state machine-based (or rule based) architecture that is based on coding all possible if-else 
conditions for each possible state of the conversation. For example, conversation goes like this
    * User: What is the day tomorrow?
    * AI bot: It is going to be Sunday, 3 May 2020.
    * User: what about the weather.
    * (So, when this question is posed, both should remember the context of the conversation and reply regarding tomorrow's weather.)
    * AI bot: It will be partly cloudy.

## Problem Statement 02

* With the increase of COIVD and physical lockdown it becomes very difficult for people to go out and buy the required stuff.
* So in this scenario, people rather opted to buy stuff online.
* The online seller cannot entertain much of the people at the same time.


## Problem Solution
* To counter the given problem we come up with the idea to make an Artificial based rasa chatbot which can deal number of people at same time.
* For now the chatbot is specified for buying mobile phones and mobile accessories but can be extend for other items too.
* This cannot only helps the seller in his/her business but also effective against the spread of COVID.


## Project Objectives
* To build an AI driven chat-bot which provides the user a great shopping experience.
* More interactive compare to competitive bots.
* Can handle small talks.
* To integrate the bot to the users favorite apps e.g Telegram or FB messenger.
* Due to time and resource limits we are specified it to only handle the purchasing of Mobile phones and it’s accessories.

## Project Component
* <srong> Action Server – </srong> is used to generate customs responses for chatbot. This can be used either to make an API call or query some database etc.
* <srong> Tracker Store – </srong> is used to track the current conversation.
* <srong> Lock stores – </srong> it stores the upcoming message in queue if previous text is in the processing to maintain chat order.
* <srong> File System – </srong> it contains the trained models and training data.
* <srong> I/O Channels – </srong> it is where chatbot has been deployed.
* <srong> Dialogue Policies – </srong> </srong> Sets the hyperparameter for chatbot.
* <srong> NLU pipelines – </srong> Used for external datasets or external libraries like Spacy or tensorflow etc

## Tools and Technologies
* Jupyter Lab.
* Python.
* Google console cloud.
* Docker.
* Yaml. 
* VS Code.
* PuTTY engine.
* FileZilla.
* Ubuntu. 
* Rasa. 

## Conclusion
* It provides users hassle free shopping experience.
* It is easy to use
* Can be accessed 24/7.
* Brings technological advancement in a business.
* No need to hire extra salesman hence reduction in cost.
* Unlike majority of chatbots it has memory and keep the context of chatbot.

