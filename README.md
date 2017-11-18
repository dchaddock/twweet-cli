# twweet-cli
Tweet right from your cli without even opening your browser.

[![Join the chat at https://gitter.im/twweet-cli/Lobby](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/twweet-cli/Lobby)

<!-- [![Build Status](https://travis-ci.org/CruiseDevice/twweet-cli.svg?branch=master)](https://travis-ci.org/CruiseDevice/twweet-cli) -->

**Requires Python 3.x**

## Features
* Tweet from the command line without opening the browser
* Change authentication tokens for Twitter app
* Get your tweets
* Get tweets of any user by providing the username
* Get tweets of a particular hashtag by providing the same
* Get trending topics on Twitter
* Get tweets in your timeline
* Get your follower list and their respective username
<br />

## Before installing
Before installing twweet-cli, make sure that:
* Python 3.x is installed
* pip is installed (pip3 for Linux users)
* You have a Twitter account and have created a Twitter "app" with the following keys generated (navigate to https://apps.twitter.com/ to create an app)
  * Consumer key (API key)
  * Consumer secret (API secret)
  * Access token
  * Access toekn secret
<br />

## Installation
To install twweet-cli, build the software from source using the following steps.

### Linux
<pre>git clone https://github.com/CruiseDevice/twweet-cli.git
cd twweet-cli
pip3 install -r requirements.txt
python3 setup.py install</pre>

### Windows 
<pre>git clone https://github.com/CruiseDevice/twweet-cli.git
cd twweet-cli
pip3 install -r requirements.txt
python3 setup.py install</pre>
<br />

## Usage
To run twweet-cli, type the command `twweet-cli` in your terminal.

Options:
* `twweet`: post a tweet
* `get`: get different types of information from Twitter (menu will be displayed with further options)
* `edit`: change your OAuth credentials (set up at install time)
* `99`: quit the application
<br />

## Contributing
To contribute, have a look at the open issues and [join the Gitter](https://gitter.im/twweet-cli/Lobby).
<br />
