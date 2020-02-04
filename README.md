# TinderBot
Automated bot for swiping and matching in Tinder. Built using Python 2.7, ChromeDriver and Selenium

# Dependencies
1. chromedriver-
   Download from https://chromedriver.chromium.org/ 
   Place it in /usr/local/bin

2. selenium -
   Use pip to install latest selenium version.
   pip install selenium
  
  
# Setup
1. Create a secrets.py file in the same directory as the tinder_bots.py
   CONTENTS OF FILE-
   username='[your_facebook_username]'
   password='[your_facebook_password]'
   
2. After all depedencies installed run tinder_bots.py file in interactive mode -
    python -i tinder_bots.py
  Now call either of these three functions-
  a.) bot.like()
  b.) bot.dislike()
  c.) bot.auto_swipe()

# Note
 - Chrome browser should be installed already
 - Comment if any query
