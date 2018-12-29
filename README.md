# SpongeBot

Intro: 
This is a CLI twitter interface with basic options such as looking up accounts posting pictures and making new tweets, there is also a dedicated function which auto spams the spongebob meme on accounts you specify it.

BackStory:
After writing my first program in python I was eager to do something else, both for personal reasons and I need a better github to get out of the restaurant biz. Bots and the public's non understanding of what they are and how they used have always frustrated me, but who am I to complain unless I make my own. There are Twitter apis out there, but most require a certain level of programing knowledge i tired to cure this somewhat with a easy UI. This is the first program I wrote since ti83 programs in middle school with a menu. I've improved on the design since with other things I've written in python, and I’m still learning more.  But it does have a UI though it can crash with basic wrong input .

How: 
I had to spend some time learning the tweepy library, and having no prior experience with Twitter spend some time learning Twitter's lingo in gereral. This project also took about a week on and off. And there's still updates I'd like to push.

Using it.:
Before you can use this you MUST have a Twitter account with developer api, you can enter the keys in the source or change them in program. The program itself has it own functions accessible via navigation menu. 
The functions with descriptions are as listed


1. Get a users  data
2. Get a users last tweet
3. Tweet a new status
4. Tweet with Media
5. SpongeBot
6. SpongeBot Auto Mode
7. Log in/ Change Twitter account

You will also be greeted with a hello (yourname) which is determined by your account set in the source, if you don't have the account keys already in the source you be greeted as “NOT LOGGED IN”  which is one reason why option 7.Login / Change twitter account exists.

Each screen show the program Banner and the current Time overhead

1.Get User Data
To get user data we will be prompted for a screen name. Its important you don't use an @ symbol. So instead of looking up  “@DEFCON” you can just type “Defcon” (case does not matter and I have had fun just typing random letters). What will return is the Screen Name, Name, Follower count, and Description. 

2.Get users last tweet
Using the same input syntax from before, this will return the specified users last tweet along with the id # of that tweet.

3.Tweet new Status
Simply enter the tweet you want to tweet and you'll see with a success message below if it tweets successfully. If you leave the option blank you'll just return to the home screen.

5. Tweet with Media
This allows you to tweet with an image. All jpegs in the current working directory will be listed, you'll be prompted for the name of the image file you want to use. If you'd rather not use an image and just tweet, leave the prompt blank and press enter. Whether you've put an image file or not you'll be asked what you'd like to tweet alongside you image. If you didn't specify an image file before and enter no text for the tweet you'll be returned home, otherwise you should see a success message at the bottom of the screen

5. SpongeBot
So this is where things get interesting, this function of the program was originally my reason create this whole thing. Thanks to my buddy Judson joking about the spongebob meme and his coworker the night before, I was inspired to have the idea for a way to automate the process of making this meme. This option will prompt you for the user you wish to mock with the. Once again make sure you don't use the @ symbol. Below will be printed the original text off the last tweet of that user, along with the rearranged text of that tweet. This will both tweeted and replied to. You'll see a success message at the bottom of the screen if it works.

6.Sponge Bot Auto Mode
This is a version of the original SpongeBot but will continually monitor set accounts at specified intervals of time indefinitely. Each time the bot scans for new tweets it will let you know and at what time. It will also post all the info of each new tweet and reply it creates. To stop the bot simply press CTRL + C and you'll be taken to the home screen.

7. Log in / Change Twitter account
If haven't set up your twitter api in the source this part MUST be done first! If your account is properly connected you should not see the “ NOT LOGGED IN” in the greeting at the top of the page. The changing in program of accounts can be very useful in management several different bot campaigns. NOTE: you must have a developer Twitter account for anything in this program to work. Making a developer account  is a very easy 15 minute thing to do. https://developer.twitter.com/en/apps



Bugs:
Yes I know there are alot of menu crashes, but this is my first menued program in python so i'm working out the kings albeit slowly. Hopefully I’ll polish this er.. thing

Points for improvements:
Having a command line arguments for SpongeBot auto will def make it easier to implement a multi user bot army.

Adding features like inbox and send messages

Live feed

An auto picture and status updater at time sets for non spongebob memes, for people who want to have constant “scripted live updates”


Programed By:
Duncan Andrews
2018
For my buddies
www.dalliance.site
https://twitter.com/SpongeBotNews
