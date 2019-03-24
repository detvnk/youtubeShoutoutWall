# youtubeShoutoutWall
A shoutout wall for youtube driven by live chat when viewers type !wall

https://raw.githubusercontent.com/detvnk/youtubeShoutoutWall/master/youtubeShoutoutWall.html

Join our Discord Channel for help 
https://discord.gg/VApBfjv

# Instructions on How to Setup

1. a. First Add Nightbot to your channel: Use this link here.
https://beta.nightbot.tv/

1. b. Install the Custom Quote API system into your night bot by following these instructions
https://community.nightdev.com/t/customapi-quote-system/7871

2. a. Once you've done this you need to go to custom commands 
https://beta.nightbot.tv/commands/custom
Copy the token from the one that says !addquote. You will need this in the next command.

2. b. Create a new command called !wall (or !set your choice) and change the  permissions to everyone

2. c. --- then change the command to this  --- > 
$(urlfetch https://twitch.center/customapi/addquote?token=[your token here]&data=$(userid))

2. d. You need to change [your token here] to the token value you copied in step 2.a (note you must remove the square brackets too [])

3. The last thing you'll need is a google api key
follow these instructions
https://www.slickremix.com/docs/get-api-key-for-youtube/
https://developers.google.com/youtube/v3/getting-started

4. Insert the nightbot token value (this is not the one from 2.a but the one you'll find in !quote) and google api key in the html code and you're good to go (scroll down to script in the html file to find where to put them)
You need to open the html file in notepad editor to be able to do this.

Enjoy
