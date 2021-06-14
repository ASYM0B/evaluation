# ASYM0B
ASYM0B (**A** framework for **SY**ste**M**atically assessment chat**B**ots) is a framework to analyze and assess conversational agents or chatbots built in different tools. To support chatbots from different platforms, ASYMOB relies on the a neutral chatbot definition called CONGA. 

This repository contains a twelve chatbots (six Dialogflow, and six Rasa) used for an evaluation. The list below shows the container of each folder: 
- **Rasa Folder:** contains the CONGA definition of six Rasa chatbots. 
  - **concertbot:** is a simple chatbot that contains only story data. Its training phrases is defined interactive learning. It is a predifine Rasa chatbot of the [examples directory of Rasa Core](https://github.com/RasaHQ/rasa/tree/1.10.x/examples). 
  - **formbot:** is a simple restaurant search assistant. It is a predifine Rasa chatbot of the [examples directory of Rasa Core](https://github.com/RasaHQ/rasa/tree/1.10.x/examples)
  - **moodbot:** is a simple predifine Rasa chatbot of the [examples directory of Rasa Core](https://github.com/RasaHQ/rasa/tree/1.10.x/examples).
  - **05_event_bot:** is a template of a chatbot to inform about a conference. You can find its Rasa definition in Github in this [link](https://github.com/cedextech/rasa-chatbot-templates)
  - **small-talk-rasa-stack:** is a chatbot with questions and answers of small talk. You can find its Rasa definition in Github in this [link](https://github.com/rahul051296/small-talk-rasa-stack)
  - **FAQ-RASA-NLU:** is a chatbot with questions and answers with FAQ about COVID-19. You can find its Rasa definition in Github in this [link](https://github.com/krishnaik06/FAQ-RASA-NLU)
- **Dialogflow Folder:** ontains the CONGA definition of six Dialogflow chatbots.
  - **Dining-Out:** is a prebuilt Dialogflow agent to search restaurants, cafes and bars.
  - **Car:** is a prebuilt Dialogflow agent to Interact with a vehicle's systems.
  - **Easter-Eggs:** is a prebuilt Dialogflow agent to answer fun questions about meaning of life, chickens, fox sounds and how much wood does a woodchuck chuck. 
  - **bikeShop:** is a chatbot to make an appointment in a bike shop. You can find its Dialogflow definition in Github in this [link](https://github.com/dialogflow/fulfillment-bike-shop-nodejs)
  - **mysteryAnimal:** is a chatbot to play a guessing game where the computer pretends to be an animal, and you have to guess what it is. You can find its Dialogflow definition in Github in this [link](https://github.com/googlecreativelab/mystery-animal)
  - **googleChallenge:** is a chatbot of FAQ of various universities and colleges. You can find its Dialogflow definition in Github in this [link](https://github.com/singhricha2995/google_solution_challenge_2020)
