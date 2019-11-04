# Send-message-to-FB-friend-using-Python

The power of Python comes because of the large number of modules it has. This time we are going to use one of those. Everyone of
us, one time or another, has a wish of messaging (or spamming -.-) our Facebook friend. This is a program which can do something 
similar. So without further delay, let’s jump right in.

## fbchat Installation:

sudo pip install fbchat

In case you get the error: ** make sure the development packages of libxml2 and libxslt are installed **

## In Ubuntu, installing following packages might help:

sudo apt-get install python-dev libxml2-dev libxslt1-dev zlib1g-dev

## Program explanation:
The program can be broken down into several steps:

### Step – 1: 
   Getting the user credentials

This part is very easy. Using raw_input() and getpass() we can get the username and password. There are some things to keep in mind in this step.

    Your facebook account should have a username. You can check that (or set that) by going to your general settings.
    We are not using raw_input to get password because as soon as the characters (or even the password length) is out, we have got a security breach.

Step – 2: Entering the facebook friend’s name
Now that we have signed in, we can enter the number of friends we want to send the message to and for each of those friends, we can enter the custom message.

Step – 3: Spamming *evil*

    Caution – I am not responsible for extensive usage of the program which can get you banned from facebook or getting blocked by your friend. Get your own list of guinea pigs!

Because of some reason, if you want to send the same message several times, you can use a simple for loop. Nothing difficult about that 😉

## What you can try out now?

    Send message to a group chat.
    Instead of text only, send images as well.
    Create your own ‘desktop’ messenger.

## Facebook hack – Send blank message
Using the normal facebook chat or messenger, it is not possible to send a blank message unless you are aware about the alt+0173 trick. But, with this program you can send blank messages as well!! All you have to do is enter a blank message. That is, when the program asks for the message to be sent, just press enter and voila!! Your friend will be receiving a series of blank messages…
