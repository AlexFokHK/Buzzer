# Buzzer
A little buzzer app for running your own quizzes or game shows! Uses websockets to sent messages.

Running the app
You must be an administrator, use command sudo -i to use root account.
You'll need Node.js or Docker to run this application. For Node:

npm install
node index.js
For Docker:

docker build -t buzzer .
docker run -p 80:80 buzzer
Open http://localhost:80 in your browser to start!

How to use
The players goto the homepage (http://localhost:80/) and they can enter their name. Joining will give them a giant buzzer button!

The host heads over to /host and will be able to see everyone that buzzes in and clear the list in between questions.
