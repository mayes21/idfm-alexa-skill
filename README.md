# IDFM API
Ile De France Mobilite - API

# ASK SDK

### SOME CONCEPTS
- _invocation phrase_ is the name Alexa uses to identify the skill I request.
- _utterance_ is a user's spoken request, these spoken requests can invoke a skill, provide inputs for a skill, confirm an action for Alexa, and so on. 
- _prompt_ text that you have Alexa speak to the user to ask for information
- _intent_ represents an action that fulfills a user's spoken request. Intents can optionally have arguments called slots.
- _slots_ are input values provided in a user's spoken request.

### ASK SDK CODE
- _can_handle()_ function is where you define what requests the handler responds to. 
- _handle()_ function returns a response to the user.
- _speak()_ function tells response_builder to speak the value of speak_output to the user.
- _ask()_ function used when the skill is waiting for a reponse from the user.
- _response_ statement sends the response.

