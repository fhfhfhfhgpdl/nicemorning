# nicemorning

>Let's automatically send morning greetings to your parents!  

<h3>Pushbullet</h3>  
you can sigh up <b>Pushbullet</b> at : https://www.pushbullet.com/</br>
This service allows you to send sms using API.</br>
You should copy your own API at Pushbullet's Settings.(Click <i>Create Access Token!</i>)</br></br>

<h3>Download Module</h3>  
You can Download <a herf="https://pypi.org/project/pushbullet.py/0.9.1/">pushbullet.py</a>

<pre><code>
pip install pushbullet.py
</code></pre></br></br>

<h3>If you want repeat...(and random time!)</h3>  

I wanted it to send even when my computer was off.</br>
So, I used Windows Task Scheduler.</br>

Saying hello every day at the same time is easily detected by parents.</br>
I wanted the message to be sent at random times within 7-9 in the morning.</br>
So I used this code(My Task Scheduler start at 7'):</br>
<pre><code>delay = randint(0, 7199)</br>
time.sleep(delay)</code></pre></br></br>

If you don't want repeat(&random) this work, you shouldn't need this code.</br>
<pre><code>delay = randint(0, 7199)</br>
time.sleep(delay)</code></pre></br></br>
