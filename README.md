# RASAChatBot


pip install rasa
pip install spacy

python -m spacy download en
python -m spacy download en_core_web_md
python -m spacy link en_core_web_md en

python -m rasa init

rasa train
rasa shell

ngrok http 5005

rasa run
rasa run actions