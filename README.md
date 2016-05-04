# midhe
An online synthesizer experience.

DEMO: http://sesosa.com/midhe/login.php

————
Recap
————

midhe is a a virtual, in-browser, midi keyboard with selectable sounds and styles.

During the requirements/design phase of development, we mapped out and researched what 
technologies were needed for our application. We then came up with a cohesive style-guide, 
including fonts/patterns/colors/etc.

————
Testing
————

Our course of action for testing midhe was fairly straightforward. Apart from usual development 
testing, when the application was in its final stages we did performance tests. Consisting firstly 
of using midhe to its fullest extent: testing all functions (volume control, instrument changes and 
database retrieval, on-screen keyboard interactivity, etc), testing the application in unconventional 
(clicking things that aren’t intended to be clickable, hitting keys that are not intended to be pressed), 
and database stress tests. 


————
Deployment
————

We deployed midhe a personal website (http://sesosa.com) running on a web server that supports phpmyadmin 
and mysql. We had some user verification issues, but only because the company who hosts us changed their name servers.

————
Lessons Learned
————

One serious challenge we encountered was changing the audio files for each synth. After struggling with it for a while, 
we decided to have separate instances of the keyboard so that loading the audio files in would only need to happen 
once per instrument. We’ve also learned that time management is key.


