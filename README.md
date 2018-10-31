# Tensorflow Chatbot
Tensorflow Chatbot by Rishab Shama.

## Link

[Rishab Bot](https://rishabbot.herokuapp.com/)

## Screen UI

![hh](https://github.com/rishab-sharma/chatbot_tensor/blob/master/Screen%20Shot%202017-12-03%20at%202.06.50%20PM.png)

Overview
============
This is the full code for  Amazing Tensorflow Chatbot  model to train a
chatbot on a AIML open-source dataset. The bot holds a fun conversation and its just been trained for sometime.


Dependencies
============
* numpy
* scipy 
* six
* tensorflow (https://www.tensorflow.org/versions/r0.12/get_started/os_setup.html)

Use [pip](https://pypi.python.org/pypi/pip) to install any missing dependencies


Usage
===========

To train the bot, edit the `seq2seq.ini` file so that mode is set to train like so

`mode = train`

then run the code like so

``python execute.py``

To test the bot during or after training, edit the `seq2seq.ini` file so that mode is set to test like so

`mode = test`

then run the code like so

``python execute.py``

