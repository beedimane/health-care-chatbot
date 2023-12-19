static
Add files via upload
last year
templates
Add files via upload
last year
README.md
Add files via upload
last year
app.py
Add files via upload
last year
chat.py
Add files via upload
last year
intents.json# health-care-chatbot
Initial Setup:
This repo currently contains the starter files.

Clone repo and create a virtual environment

$ cd Virtual-Assistant-using-AI
$ python3 -m venv venv
$ . venv/bin/activate
Install dependencies

$ (venv) pip install Flask torch torchvision nltk
Install nltk package

$ (venv) python
>>> import nltk
>>> nltk.download('punkt')
Modify intents.json with different intents and responses for your Chatbot
>>> Run

$ (venv) python train.py
This will dump data.pth file. And then run the following command to test it in the console.

$ (venv) python chat.py
To start the Flask app:
Run the app.py (after downloading all required libraries)

Credits:
This repo was used for the frontend code: https://github.com/hitchcliff/front-end-chatjs


