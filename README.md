# A bot to make reservation in restaurants
Use of rasa_nlu and rasa_core to train a model which attempts to book table in resturants. Trained on imaginary dataset, so all expected outcome might not happen. The training data and training stories can be found inside data directory as data.json and stories.md

## This repo uses python version 3.6.0 
### (Optional) Setup venv

```bash
python -m venv ./.venv/chat_bot
source .venv/chat_bot/bin/activate
```
## Installation
Installation of the dependencies 
```bash
pip install -r requirements.txt
```
Run the model
```bash
python dialogue_management_model.py
```
Play with the chat_bot :)
