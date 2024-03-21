# SRMYouTube
[Streamer.Bot](https://streamer.bot/) Import to let Beat Saber [Song Request Manager](https://github.com/Krayn/SongRequestManager/releases) work for YouTube Live Streaming

## [YouTube Tutorial](https://youtu.be/b_5htZshHbA)

## Instructions
### You will need the following before setting this up:
- Beat Saber is installed and you’ve launched it
- You Have [Streamer.Bot](https://streamer.bot/) and you’ve connected it to YouTube (super easy if you haven’t)
- You have downloaded [Mod Assistant](https://github.com/Assistant/ModAssistant/releases/tag/v1.1.32) for Beat Saber at least. Hopefully used it before.



### Import [actions and command](https://github.com/Haunter56/SRMYouTube/blob/main/SRM4YouTubeNEW.sb) for Streamer.Bot
- There are [4 Actions and 1 command](https://github.com/Haunter56/SRMYouTube/blob/main/SRM4YouTubeNEW.sb)
- Enable the command
- Open the Action "SRM-Code" and edit the "Execute Code" Subaction. Use the "Compile" button to make sure it compiles correctly. If not, you may need to use the "Find Refs" button. (you might need to manually add Newtonsoft.Json.dll in the references tab)
 ![image](https://github.com/Haunter56/SRMYouTube/assets/107263697/37f5c22e-c4b1-444f-8cb9-31b2917ccd48)



### Set Websocket server to Auto Start in Streamer.Bot (if desired)
![image](https://github.com/Haunter56/SRMYouTube/assets/107263697/09f379e9-6c06-45cf-8045-9baf2f4849ae)

- Go to Servers/Clients > Websocket Server > Edit the SRM Server
- Check the Auto Start box
  
### Make sure websocket-sharp mod in Mod Assistant is installed
- This is found under the "Libraries" Section
  ![image](https://github.com/Haunter56/SRMYouTube/assets/107263697/3471bbdd-b7cf-4d4b-b0f0-a2190e5fb17e)


### Download [SRM](https://github.com/Krayn/SongRequestManager/releases) from Krayn
- Copy the .dll into the beat saber plugins folder
- It is found in the SongRequestManager_v2.15.15.zip file under "assets"

### Launch Beat saber
- Go to SRM settings
- Enable websocket
- Disable c(h)atCore
- Go to SRM and select "connect websocket"
- Exit and restart Beat Saber to check that it connects each time as long as Streamer.Bot is running

