# KALI-NETHUNTER-2024
ROOTED NETHUNTER FOR BOTH ROOTLESS AND ROOTED DEVICES

Approx 45min - hour depending on your network.

Dependicies

Download termux for droid either  via this link or via the github repository I suggest you do not download the google play store one as it has no regular updates:

 https://fdroid.org/repo/com.termux_118.apk

After termux installation open termux to set it up by following these steps (input 1by1): 
fyi yes for Everything

pkg update -y && pkg upgrade -y && pkg install x11-repo -y && apt update -y && apt full-upgrade -y 

termux-setup-storage 

pkg install git

pkg install python 

pkg install python3

pkg install wget 

pkg install curl

pkg install cmake

pkg install rust

pkg install proot

run this one more time:
pkg update -y && pkg upgrade -y

Also I reccomend this VNC apk for your desktop environment:
https://github.com/gujjwal00/avnc

Now your terminal is setup lets move onto the kali install:

(SIDE NOTE:
If install stops repeat this in your cmd line until instalation continues it gets and installs missing pkgs  
apt --fix-broken install 
if really stuckfeel free to shoot me a message)

Copy and paste (1by1):

pkg install wget openssl-tool proot -y && hash -r && wget https://<i></i>raw.githubusercontent.com/EXALAB/AnLinux-Resources/master/Scripts/Installer/Kali/kali.sh && bash kali.sh

After kali has installed start it by inputting 
./start-kali.sh

Once your cmd line changes to root@localhost:~# continue following my steps. (C&P)

wget https://<i></i>raw.githubusercontent.com/EXALAB/AnLinux-Resources/master/Scripts/DesktopEnvironment/Apt/Xfce4/de-apt-xfce4.sh --no-check-certificate && bash de-apt-xfce4.sh

Just follow the installation steps after installation carry on following my steps:

apt update -y && apt full-upgrade -y 

apt install -y kali-linux-nethunter 

Follow the installation instructions for the kali nethunter install. FYI yes for everything, for kismet put yes enter then leave blank and press enter. Remember if install stops just input on your cmd line 
apt --fix-broken install you might have to do this a couple times to install your missing packages dont worry its not broken error's it will restart itself. Also if it feels like its doing nothing leave it its configuring the packages in the background, DO NOT CLOSE TERMUX OR END THE PROCCESS YOU WILL HAVE TO REDO EVERYTHING 

Continue following my steps (C&P)

apt install apt-file

apt-file update

Run this one more time:
apt update -y && apt full-upgrade -y 

If nothing needs doing type exit then Ctrl alt z then exit x2 then enter

Restart termux and input ./start-kali.sh if nethunter was a successful install your cmd line should now say ┌──(root㉿localhost)-[~] ignore the message from kali devs as you will at this point have nethunter fully installed and setup its just an advertisement and input touch ~/.hushlogin 

Double check nothing needs doing with apt update -y && apt full-upgrade -y if not input vncserver to start the desktop then log in on your VNC apk once your in nethunter desktop go back into termux and input vncserver -kill :1 as this is what we used to create the desktop earlier and is no longer needed once logged in on a fresh desktop environment

local host = 127.0.0.1 port number will be showing 

Input what it says into your vnc server apk then when it asks for password, input the password you created earlier 

If black screen on startup input vncserver -kill
chmod +x ~/.vnc/xstartup 
vncserver 

I am on a rootless device but as you can see I have rooted nethunter. I have spent my own free time  working on this so any feedback would be much appreciated thank you.

Any questions feel free to ask.

btw you will not find a better way to install NH as kali broke the nethunter code 2023 my way the rooted way is now one of the only ways as of 2024 with 0 errors 0 bugs 0 stress I have spent hours repairing nethunter putting the Pieces together to get it working again of my own free will so Everyone can have access to a linux  distro no matter if your Device is rooted or not and best part about it it doesnt touch your main OS so enjoy my freinds

With thanks to https://github.com/EXALAB and https://github.com/gujjwal00 who without them this wouldn't be possible

~$ ZłO
![1000462856](https://github.com/user-attachments/assets/f74e8b29-a1af-45ec-8e9f-13fbfb04f92e)
![1000462857](https://github.com/user-attachments/assets/ff96bb37-c2e7-4af3-b7a6-0582b77e5606)
![1000462858](https://github.com/user-attachments/assets/88c50b30-eb34-4308-a5a7-498da84b6049)
![1000462860](https://github.com/user-attachments/assets/32ecc025-9c95-4d9b-9815-25c4264b4477)
![1000462855](https://github.com/user-attachments/assets/82163e61-a811-4ec2-9799-b036e1b5c9b1)
![1000462861](https://github.com/user-attachments/assets/9a98edde-c1e6-49bf-ac85-6951a33733c8)
![1000462862](https://github.com/user-attachments/assets/a770727a-3888-4dfb-b5d3-a89f2a93e079)
![1000462863](https://github.com/user-attachments/assets/99960030-d1a4-4a2e-a79c-ef21bce06956)
![1000462864](https://github.com/user-attachments/assets/e556e0a8-8983-483c-8843-7d7d830195ec)

