# FestFish
Grab cam shots from target's phone front camera or PC webcam just sending a link.It is a upgraded version of
CamPhish(Victim must have to click on "allow camera" otherwise it will not work)
![festfish](https://1.bp.blogspot.com/-uVofOBCdEpo/XslVa6WsfTI/AAAAAAAAABA/nRxlr3RAJHkd6KMDsXrE-OYBm9wK6gWtACLcBGAsYHQ/s1600/festfish.png)

# What is Festfish
<p>FestFish is techniques to take cam shots of target's phone fornt camera or PC webcam. FestFish Hosts a fake website on in built PHP server and uses ngrok & serveo to generate a link which we will forward to the target, which can be used on over internet. website asks for camera permission and if the target allows it, this tool grab camshots of target's device</p>

## Features
<p>In this tool I added two automatic webpage templates for engaged target on webpage to get more picture of cam</p>
<ul>
  <li>Festival Wishing</li>
  <li>Live YouTube TV</li>
</ul>
<p>simply enter festival name or youtube's video ID</p>
# Installing and requirements
<p>This tool require PHP for webserver, SSH or serveo link. First run following command on your terminal</p>

```
apt-get -y install php openssh git wget
```

## Installing in (Kali Linux/Termux):

```
git clone https://github.com/onlyhacker/festfish
cd festFish
bash festfish.sh
```
## This Tool Tested On :
<ul>
  <li>Kali Linux</li>
  <li>Termux</li>
  <li>MacOS</li>
  <li>Ubuntu</li>
  <li>Perrot Sec OS</li>
</ul>


