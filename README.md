WhereArtThou
============


```
I stopped by your place/office, but you weren't there. 
Let me see if you'll be back soon. 
I'll leave you a short message if you won't be back in a while.
```


Where Art Thou? is:

* light weight
* static (client side only-no server code!)
* single page
* secure.

**It was built in 5 hours for practicing security rules on a smaller scale. Therefore, the style/build quality is severly limited.**

Curious to find out how this was made possible? Check 'Hacking this page' below!


Copyright (c) Regal Disclaimer 2014 All Rights Reserved.
Contact: regaldisclaimer@gmail.com for all usage permissions


#Hacking this page

Please try to compromise the security of Where's Waldo! This includes replacing legitimate updates/messages with troll messages, spamming multiple messages, XSS, bypassing authentication, or anything else you can think of to threaten the normal use of the website!

As you can see, the front-end of the page comprises of an `index.html` file, styled with `index.css`. 
The page uses [Firebase](https://www.firebase.com) for its database, which gives you a lot of opportunity of hacking. 
You will also find a `rules.json` file in the repository, which is a copy of the firebase security rule that is used. 
This is the only line of defense that stops you from trying to change what is written on the database, and all the code is open to you here! 

Now that all the code is open for you to play around, good luck hacking/breaking!

p.s. The code in this repository was written without planning and in a hurry. Therefore, it is poorly organized and commented. Sorry!


#Wall of Fame

This section recognizes those who were able to successfully compromise the security of Where's Waldo! They have also been awarded for their success and sharing how they managed to achieve such a feat!

* friendlyrobot: 9/5/14: username vulnerability noted, et al
* 
