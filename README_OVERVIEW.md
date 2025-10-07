# __VOICE ASSISSTANT__
The code mentioned is a python script for a voice command assisstant.
### HOW IT WORKS:
You as a user have to speak a specific text, like "" in the mentioned code to wake the assisstant up.Later you can ask any questions regarding anything and it answers to that in system voice.
### LOGIC APPLIED:
The whole thing is a combination of some very simple steps,let us dive to each of the step-  
__-Way of Output__  
We make a function (_speak_) to enable us to use our system's voice tool,we use a python module(_pyttsx3_) to do so,now this fucntion can be called whenever we want to let the system speak.  What it does is that it just
uses the inbuilt functions of the module to let our system speak whatever taxt we pass to it.  
__-Processing Input__  
We make a function (_listen_) and use another python module (_speech_recognization_) to accept voice from the user,the input voice we store in a variable (_iniital_text_) and then we use if else to use that input voice accorind to our usecase.  
