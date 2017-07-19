# fli-birdz-twitter-bot

Basic framework forked from [molly/twitterbot_framework](https://github.com/molly/twitterbot_framework) for creating Twitter bots using Python 3 and [tweepy](http://www.tweepy.org). This goes along with her [tutorial](http://blog.mollywhite.net/twitter-bots-pt2/) on creating Twitter bots.

---

**[fli_birdz_bot](https://twitter.com/fli_birdz_bot)**

---

Python script pulls what to tweet from *facts.txt* (while also deleting that line from the file so that it doesn't get used again), authenticates connection to the twitter account and attempts to send out the tweet. Whatever occurs is written to a log file. Crontab used for scheduling daily automation.

---

Created as a fun side project so that my team has a supply of random bird facts to cheer.
