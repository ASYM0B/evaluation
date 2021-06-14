# ASYM0B
ASYM0B (**A** framework for **SY**ste**M**atically assessment chat**B**ots) is a framework to analyse and assess conversational agents or chatbots built in different tools. To support chatbots from different platforms, ASYM0B relies on a neutral chatbot definition called CONGA. 

This repository contains twelve chatbots (six from Dialogflow, and six from Rasa) used for an evaluation. The list below shows the content of each folder: 
- **Rasa Folder:** contains the CONGA definition of six Rasa chatbots. 
  - **concertbot:** is a simple chatbot that contains only story data. Its training phrases are defined with interactive learning. It is a predefined Rasa chatbot of the [examples directory of Rasa Core](https://github.com/RasaHQ/rasa/tree/1.10.x/examples). 
  - **formbot:** is a simple restaurant search assistant. It is a predefined Rasa chatbot of the [examples directory of Rasa Core](https://github.com/RasaHQ/rasa/tree/1.10.x/examples)
  - **moodbot:** is a simple predefined Rasa chatbot of the [examples directory of Rasa Core](https://github.com/RasaHQ/rasa/tree/1.10.x/examples).
  - **05_event_bot:** is a conference template chatbot. You can find its Rasa definition on this [link](https://github.com/cedextech/rasa-chatbot-templates)
  - **small-talk-rasa-stack:** is a chatbot with questions and answers of small talk. You can find its Rasa definition on this [link](https://github.com/rahul051296/small-talk-rasa-stack)
  - **FAQ-RASA-NLU:** is a chatbot with questions and answers with FAQ about COVID-19. You can find its Rasa definition on this [link](https://github.com/krishnaik06/FAQ-RASA-NLU)
- **Dialogflow Folder:** contains the CONGA definition of six Dialogflow chatbots.
  - **Dining-Out:** is a prebuilt Dialogflow agent to search restaurants, cafes and bars.
  - **Car:** is a prebuilt Dialogflow agent to interact with a vehicle's systems.
  - **Easter-Eggs:** is a prebuilt Dialogflow agent to answer fun questions about the meaning of life, chickens, fox sounds and how much wood does a woodchuck chuck. 
  - **bikeShop:** is a chatbot to make an appointment in a bike shop. You can find its Dialogflow definition on this [link](https://github.com/dialogflow/fulfillment-bike-shop-nodejs)
  - **mysteryAnimal:** is a chatbot to play a guessing game where the computer pretends to be an animal, and you have to guess what animal is. You can find its Dialogflow definition on this [link](https://github.com/googlecreativelab/mystery-animal)
  - **googleChallenge:** is a chatbot of FAQ of various universities and colleges. You can find its Dialogflow definition on this [link](https://github.com/singhricha2995/google_solution_challenge_2020)
