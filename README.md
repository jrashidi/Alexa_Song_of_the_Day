# Alexa_Song_of_the_Day

Quick tutorial on how to make an Alexa Song of the Day

VUI -> Utterances -> Intent -> Response

Voice User Interface:
The voice interface is the Alexa or Echo hardware. You will activate the applications by saying "Alexa, open {app}".

Utterances:
Utterances are what you say once the application is open. For example, "What's the new song today?", "Play Song", 
"What artist is this by?".

Intent: 
An intent is where you map an utterance to. Each intent can have multiple utterances. For example, "What's the new song today?" 
and "Play Song" can both map to the PlaySongIntent. 

Response:
Each utterances will will map to an intent and depending on the intent will give a desired response. The response is considered
the backend of the system. In the response you may fetch information from a database or from an api depending on what is needed
for the application. 



