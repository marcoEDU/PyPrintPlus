# PyPrintPlus
A better way of printing logs in Python.

Want to support the development financially? Donations are always welcomed! 
[Click here to donate on Liberapay](https://liberapay.com/marcoEDU)

[<img src="http://img.shields.io/liberapay/receives/marcoEDU.svg?logo=liberapay">](https://liberapay.com/marcoEDU)

## Installation
```
pip install pyprintplus
```

## Functions

### print()

Print a message together with the current file and time (or runtime).

#### Example:
```
from pyprintplus import Log

Log().print(text='Email sent',filename='send_email.py')
```

#### Input options:
text = str
filename = str (default: None)
script_started_time = int (UNIXtime, default: None)


### show_message()

Show a message in a speech bubble, making it more engaging for real humans.

#### Example:
```
from pyprintplus import Log

Log().show_message(text='Hello! Lets setup your new website!')
```

#### Input options:
text = str


### show_messages()

Show one or multiple messages automatically in a speech bubble, one after the other, after a few seconds delay. 

#### Example:
```
from pyprintplus import Log

Log().show_messages(list_messages=['Email was sent.','What do you want to do next?'])
```

#### Input options:
list_messages = list
