# boodoo_ebooks

A turn-key, beginner-friendly, ready-to-deploy implementation of a traditional \_ebooks bot using Mispy's [twitter_ebooks](https://github.com/mispy/twitter_ebooks) library.

## Usage

Create your [Twitter app](https://apps.twitter.com) and generate access tokens with *Read, Write and Direct Messages* privileges.

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/BooDoo/ebooks_example/tree/deploy)

Put your BOT_NAME, SOURCE_USERNAME, and API secrets into Heroku Config Vars using the web dashboard.

Scale your app to 1 dyno using the Heroku web dashboard.

Bob's your uncle.

## Default Behavior
Tweets once on startup.  
Has 80% chance of tweeting every 2 hours.  
Responds to mentions/DMs  
Favorites tweets that it likes.

## Special Features
- **BLACKLIST**: accounts to not interact with  
- **BANNED_TERMS**: words or phrases to obscure/censor  
- DM commands (tweet, follow, unfollow, block, mention...)  
- Follower parity (periodically compares following/followers and follows/unfollows as needed)  
- Want something else? Create an [issue](https://github.com/BooDoo/ebooks_example/issues). No promises.

## TODO:
- Support full archive (via CSV uploaded elsewhere)  

# DISCLAIMER:
I'm making this because I wrote a two-part tutorial for an older version of the twitter_ebooks gem and my mentions turned into a tech support hellscape for months.  
Please [create issues](https://github.com/BooDoo/ebooks_example/issues) if you have trouble. 🙏 Please do not tweet at me. 🙏
