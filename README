Tweet Command is a shell script that shortens urls with bit.ly and opens a browser window to Twitter with the short url in a New Tweet field.  It uses some native short urls and assumes that you are already logged in to Twitter. It also requires the base58 gem; if you don't have it already, enter 'gem install base58' on the command line to install it. (A common way to shorten urls is to convert them to a base-58 string, and this gem handles the conversion.)

It came about because I can't do the math in my head to shorten a flickr url.  

# To install: 

<<<<<<< HEAD
1. Download using the download button. 
2. Cd into tweet-command:
    cd tweet-command
3. Copy it into your $PATH:

	cp ~/Downloads/tweet_command/tweet /usr/bin
or 
    cp ~/Downloads/tweet_command/tweet /usr/local/bin

# To use Tweet Command:
In a terminal window, use the command "tweet" and paste in the url to shorten.  For example:  
    tweet http://www.npr.org/blogs/alltechconsidered/2011/01/03/132631042/a-preview-of-the-2011-consumer-electronics-show   

The first time you use the tweet command, two things will happen:  First, if you don't have base 58 gem, you'll be prompted to install it.  (A common way to shorten urls is to convert them to a base-58 string, and this gem handles the conversion.)  Second, you'll be prompted to provide a bit.ly login and API key.  To find your API key, go to bit.ly, if you don't have an account then make one, sign in and navigate to user settings to find your API key.

# Troubleshooting:
If you screw up entering your bit.ly credentials, Tweet Command won't work.  If this happens, remove the file that stores your credentials and try again:

    rm ~/.bitly 

Happy tweeting!
=======
1. Navigate your command line to the Downloads folder (or whichever you'd like) and enter:

'git clone https://github.com/rachelmyers/tweet-command.git'

2. Copy the tweet program (_not_ the full tweet-command directory) into your $PATH.  For example, if you put tweet-command into your Downloads folder and have a /usr/local/bin folder, enter:

'sudo cp ~/Downloads/tweet_command/tweet /usr/local/bin'

If you don't have /usr/local/bin, replace it in the command with whichever directory houses your executable scripts.

You should now be able to open a terminal window, enter the command "tweet (longform URL)" and watch as a new browser window opens with the shortened URL ready to be tweeted.

The first time you run Tweet Command, you'll be prompted to provide a bit.ly login and API key.  To find your API key, go to bit.ly, make an account if you don't have one, sign in and navigate to user settings.

Troubleshooting:
If you screw up entering your bit.ly credentials, Tweet Command won't work.  If this happens, remove the file that stores your credentials:

rm ~/.bitly

and try again. 
>>>>>>> e47caf90aada0e0d242805afbfe428e93e1fcbd6
