# CamHack
Grab cam shots from target's Mobile phone (or PC or IOS) front camera by just wishing them or showing them any YouTube video.
![cheese](https://drive.google.com/uc?export=view&id=1JfeCw8ukW0b2jONaRYXj0Rl34e-h1pL7)

# What is CamHack?
<p>CamHack is techniques to take cam shots of target's phone fornt camera or PC webcam. CamHack Hosts a fake website on in built PHP server and uses ngrok & serveo to generate a link which we will forward to the target, which can be used on over internet. website asks for camera permission and if the target allows it, this tool grab camshots of target's device</p>

## Features
<p>In this tool I added two automatic webpage templates for engaging target on webpage to get more picture of cam</p>
<ul>
  <li>Festival Wishing</li>
  <li>Live YouTube TV</li>
</ul>
<p>simply enter festival name or youtube's video ID</p>

## This Tool Tested On :
<ul>
  <li>Kali Linux</li>
  <li>Termux</li>
  <li>MacOS</li>
  <li>Ubuntu</li>
  <li>Perrot Sec OS</li>
</ul>

# Installing and requirements
<p>This tool require PHP for webserver, SSH or serveo link. First run following command on your terminal</p>

```
apt-get -y install php openssh git wget
```
## [FOR ANDROID USERS]How to use NGROK? on Termux :
<p>If you are using termux and have good internet speed then simply turn Your Mobile Hotspot ON and at the time of choosing tunnel use option 1, that's it.</p>
<p>And for serveo nothing to do just use option 2 at the time of choosing tunneling service.</p>

## Installing (Kali Linux/Termux):

```
git clone https://github.com/GeAr368/CamHack
cd CamHack
bash camhack.sh
```
### Video Demo
[![How to control android camera](https://youtu.be/0JoeMyT9K_k)](https://youtu.be/0JoeMyT9K_k)
#### For More Video subcribe <a href="http://youtube.com/Muqeevirus">MuqeeVirus YouTube Channel</a>
<p>CamHack is created to help in penetration testing and it's not responsible for any misuse or illegal purposes.</p>
<p>CamHack s inspired by https://github.com/thelinuxchoice/ Big thanks to @thelinuxchoice</p>
