# Intro about gTalk Bot

## (Only Rasa) How i can run it another port, when the default port (5002) is busy?  
```bash
rasa run -m models --enable-api --cors “*” --debug -p 5004
```

## (Rasa X) Run it on different server 
```bash
rasa x --debug --enable-api --cors "*" --port 5007 --rasa-x-port 5008
```