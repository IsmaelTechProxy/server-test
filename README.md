# EaglerCraftX Server

## Credits
Original Project: Lax1Dude
<br>
Original Server Fork: EcoliEater87
<br>
## Setup Guide
Welcome to the EaglercraftX server project! Here is how you can setup your very own eaglercraft server:
<br>
<br>
First, go to the top of the repo and click on code > codespaces > create codespace
<br>
now you have your own free server instance to host eaglercraft. Next you need to run the setup commands:
<br>
<br>
create 2 terminal tabs:
<br>
<br>
do this before too but this is specific to my anarchy server: `sudo apk update` after that do this `sudo apk add open jdk8`
<br>
<br>
first tab: `cd server && sudo java -jar server.jar`
<br>
<br>
second tab: `cd bungee && sudo java -jar bungee.jar`
<br>
<br>
Now go to the ports area and forward (and make public) ports `25565` and `8081`
<br>
Your eaglercraft server is setup!
