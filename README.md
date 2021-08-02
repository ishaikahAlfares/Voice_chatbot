# merge watson assistant with speech to text and text to speech
i did this by using flask
* install al the following requirements:
* ibm-watson==4.0.1
Flask==1.1.1
python-dotenv==0.10.3
flask-cors==3.0.8
flask-socketio==4.2.1
* colne this folder watson-voice-bot from https://github.com/IBM/watson-voice-bot .
* create a skill in watson assistant and upload watson-voice-bot folder in that skill.
* create env file and add the credentials of all of the services.
* add the name of the chatbot in assistant_setup.py and the path of json file of the chatbot on your computer.
* run the app and open http://localhost:5000 on your browser to use the chatbot.
