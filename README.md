# multi-text-classification

Installed python3.9.7

create a virtualenv: `python3.9.7 -m venv .emailvenv`
activate: `source .emailven/bin/activate`
install: `pip install -r requirements.txt`

To see the live loss and accuracy during training or later with tensorboard.
1. cd email_classification 
2. run this command `tensorboard --logdir logs/fit`
3. open the then given localhost in the browser `localhost:number`