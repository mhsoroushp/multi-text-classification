# multi-text-classification

Installed python3.9.7

create a virtualenv: `python3.9.7 -m venv .textenv`
activate: `source .textenv/bin/activate`
pip install tensorflow[and-cuda]==2.18
install: `pip install -r requirements.txt`

To see the live loss and accuracy during training or later with tensorboard.
1. cd email_classification 
2. run this command `tensorboard --logdir logs/fit`
3. open the then given localhost in the browser `localhost:number`