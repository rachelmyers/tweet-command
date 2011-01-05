Tweet Command is a shell script that shortens urls with bit.ly and opens a browser window to Twitter with the short url in a New Tweet field.  It uses some native short urls and assumes that you are already logged in to Twitter. It also requires the base58 gem; if you don't have it already, enter 'gem install base58' on the command line to install it. (A common way to shorten urls is to convert them to a base-58 string, and this gem handles the conversion.)

It came about because I can't do the math in my head to shorten a flickr url.  

# To install: 

Download using the download button and cd into tweet-command:

    cd tweet-command

Copy it into your $PATH:

	cp ~/Downloads/tweet_command/tweet /usr/bin
or
 
    cp ~/Downloads/tweet_command/tweet /usr/local/bin

# To use Tweet Command:
In a terminal window, use the command "tweet" and paste in the url to shorten
   
    tweet http://www.flickr.com/photos/timoni/3301539341/in/set-72157624522829161/
The first time you use the tweet command, two things will happen:  First, if you don't have base 58 gem, you'll be prompted to install it.  (A common way to shorten urls is to convert them to a base-58 string, and this gem handles the conversion.)  Second, you'll be prompted to provide a bit.ly login and API key.  To find your API key, go to bit.ly, if you don't have an account then make one, sign in and navigate to user settings to find your API key.

# Troubleshooting:
If you screw up entering your bit.ly credentials, Tweet Command won't work.  If this happens, remove the file that stores your credentials and try again:

    rm ~/.bitly 

Happy tweeting!