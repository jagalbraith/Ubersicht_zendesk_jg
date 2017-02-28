# Ubersicht_zendesk_jg

CURRENT VERSION: 1.2

What you should edit to get it working:

# 1. zendesk account and some tickets created.
Create your zendesk account if you haven't already.
This widget uses the tags field of the ticket to separate the tickets by location.
I used the tags work and home. You can remove this feature to get all tickets and not use
tags if you want, you would do that in fetch_tickets.py

In fetch_tickets.py you will notice your username, password and subdomain. Put your stuff from
zendesk in there and get it updated so the API call works.

# 2. Path
You may need the full path in the command: of the coffeescript file.

# 3. IP addresses to determine where you are. 
At work we have 10.5 and at home I have 10.1.112.
You may have something different at home like 192.168.1 and 172.16. at work. Just get your IP and change those for
the right spots and you will be only showed tickets for the location you are at.
You can add as many locations as you want. Once you give your ticket the right tag, it goes there.
I used tags because Assigned group wasn't in the JSON when I coded this. If that changes in the
future, please update this. That would be one less step on the ticketing side.

# 4. Python libraries
You will need the python requests library installed. sudo pip install requests


# 5. Desktop location
You change this in the style block by changing left, right, top, and bottom. Play with it will you like where your widget is sitting. :-)

# Questions?
If you have questions, email jagalbraith@icloud.com. My name is John. I will try and help.
Also, this was the first thing I ever did in coffee and I used a different script
as a template and learning tool. If you have suggestions, let me know.



