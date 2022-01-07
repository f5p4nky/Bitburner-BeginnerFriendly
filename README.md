# Bitburner Scripts (Netscript 1.0)

Bitburner is a programming-based incremental game. Players can write scripts in Javascript to automate gameplay, learn skills, play minigames, solve puzzles and more. 
The best part ? The game is still work-in-progess !

Ever want to start programming but do not where to start ? Well you can start by playing the game.  

The game are playable on both Steam and Web Browser
- Bitburner on [Steam](https://store.steampowered.com/app/1812820/Bitburner/).
- Bitburner on [Web Browser](https://danielyxie.github.io/bitburner/).

## Quick Note 

As of now, all my scripts are for NS1 only. You can change it the way it works. This is just me doing it without having any Javascript background. Don't hate me for this!
I haven't start meddling with NS2 yet. Will post NS2 script in the future (Hopefully! XD)

And no. I have not completed the fl1ght.exe milestone yet. 

## How to get this into your game 

Well its easy. Either you copy paste the whole code and paste it in the game (first you have to create a file first) or, 
run the wget command to download it straight to the game like this: 

```wget https://raw.githubusercontent.com/f5p4nky/Bitburner-BeginnerFriendly/main/README.md readme.txt```

**For the scripts, make sure you view it raw before using the wget command**

## Info on my NS1 Scripts 

I currently use 8 scripts for the game as shown above. I constantly changing my code in the game to make the game as smooth and efficient as possible. 

### pawnauto.script 
  - I run this script whenever i install new augmentation or want to change my target who i want to hack (But you need to kill all running script first)
### early-hack-template.script
  - This script can be found in the Bitburner Docs. This is where the magic happens
  - If you do plan to change this to your liking, do update the fileSize variable in the pawnauto.script. Give it the correct file size to it. 
### buyhacknet.script
  - Same explanation as above on how i got this script, this is to automatically buy the hacknet node
### purchase-server.script
  - Same explanation as above on how i got this script, this is to automatically purchase server with 8GB Ram
### grow.script
  - I run this script on home server to grow money on the attacking server. Can also give alot of threads to the script to grow money efficiently (If you have enough RAMs)
### weaken.script
  - Same explaination as above but its for weakining the machine
### checkserverlevel.script
  - This script is to check the machine levels, sometimes every reset the level will change(?). So i use this to check if i have to re arrange the server in the pawnauto.script 
### runscriptonserver.script
  - I run this script to start running the script in my pserv after i kill all running scripts 

## Guide on how to play the game with my script 

1) Run the ```pawnauto.script``` while passing the argument as n00dles, so that the script will hack n00dles first. Do not need thread for this script.
2) Once your hacking level hit >= 10, stop any script that is running and re-run ```pawnauto.script``` but this time pass the argument as joesguns. Now just let the game play by itself.
3) Run the ```purchase-server.script```. This will buy all the 8GB Server for you the moment you have money for it. 
4) Create a program such like ```BruteSSH.exe``` or ```FTPCrack.exe``` once its available to you so that you can progress in the game. 
5) Once you ```purchase-server.script``` finish running and you have 25 8GB Servers, you can now run the ```buyhacknet.script``` while passing the the argument number of 10. 10 means = 10 hacknet. The game will buy for you 10 hacknet. For now just start small but once you progress the game, you can buy more than 10.

### My tip is that: 

- Focus clearing 1 faction at a time. Once you bought everything in the faction (Except NeuroFlux Governor), you can proceed with the installation of the augmentation.
- Buy TOR router so that you can buy the exploit there. Its a time saver, unless you dont mind waiting.

## Conclusion

I have never found an incremental game something like this. I thought i just gonna play it for a few hours and call it quit. But no, the game got me hook. It might be because of the cybertheme/hacking kind of vibe and ALSO, a programming game. Even tho i play it using NS1 script, it still felt like i did something, like i learn something. If you want to get your feet wet on starting programming, i would say go for this. Give it a try. 

## Other Resources

**Bitburner Official Documentation and Github**
- [Bitburner Docs](https://bitburner.readthedocs.io/en/latest/index.html)
- [Bitburner Github](https://github.com/danielyxie/bitburner)

**Communities**
- [Bitburner Reddit](https://www.reddit.com/r/Bitburner/)
- [Bitburner Discord](https://discord.gg/beGhWtcSdX)


