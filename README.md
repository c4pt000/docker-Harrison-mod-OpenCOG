# docker-Harrison-mod-OpenCOG


# docker quickstart
```
docker run -it --rm -e DISPLAY=$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix --device /dev/snd c4pt/harrison-current

# to load the bot
root@7e947bfa0aa0:/# harrison
```
<br>
* has to be the only audio stream using alsa or pulseaudio if something else is using the audio resources such as vlc or youtube audio
<br>
* the bot will have errors with no audio via alsa or pulseaudio mapping
<br>
<br>
<br>
<br>
* ALSA lib pcm_dmix.c:1108:(snd_pcm_dmix_open) unable to open slave
<br>
* aplay: main:828: audio open error: Device or resource busy

# Sophia-bot

template build design is garbage from too many variables inter mixing into disconnected logical meanings to an extent,
(too many chefs spoil the soup -< 
template -> x template -> x template -> z template -z

zzzxxzxzxzxzxzxzxxzxzxzxzxxzxzxzx

^^ end result of mixing too many different style templates

^
my opinion

templates needed to be seperate concepts and possibly allowable by end user to install as mods or expansionability


who ever OpenCOG project originally was 



* 11-24-2019
# * recommended don't use unless you can edit based on my realizations in the last few days Tanya-Kate 
https://github.com/c4pt000/docker-Tanya-Kate-mod-OpenCOG

FB might or might not fix i am leaving this here indefinitely, --> ARC


 fo shizzle removal


todo
* fix time and date errors based on docker remote server NTP out of location time zone

*
   sh deploy.sh
   
   cd HarrisonF-TTS-hanbot

   python run_server.py &
  
   sh 2nd_Sophia-client.sh 
   
   for offline or online execution of last image
   
   start.sh
   
   <p align="center"><img src="https://i.imgur.com/VQwdZLF.png" width="400" </p>

 

# * launch with harrison command
$ harrison




