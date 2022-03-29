# nicemorning
***
>####Let's automatically send morning greetings to your parents!

###Pushbullet
you can sigh up **Pushbullet** at : [Pushbullet](https://www.pushbullet.com/, "go to Pushbullet")
This service allows you to send sms using API.
You should copy your own API at Pushbullet's Settings.(Click *Create Access Token!*)

###Download Module
You can Download [pushbullet.py](https://pypi.org/project/pushbullet.py/0.9.1/, "See version") Module
'''python
pip install pushbullet.py
'''

###If you want repeat...(and random time!)

I wanted it to send even when my computer was off.
So, I used Windows Task Scheduler.

Saying hello every day at the same time is easily detected by parents.
I wanted the message to be sent at random times within 7-9 in the morning.
So I used this code(My Task Scheduler start at 7'):
'''python
delay = randint(0, 7199)
time.sleep(delay)
'''

If you don't want repeat(&random) this work, you shouldn't need this code.
'''python
delay = randint(0, 7199)
time.sleep(delay)
'''
