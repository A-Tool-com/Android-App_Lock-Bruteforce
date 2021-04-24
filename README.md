# Android BruteForce using ABD & Shell Scripting 
#        (4 Digit PIN ONLY)

It is a simple shell script that brute force any app lock screen  (When USB DEBUGGING is enable) its uses ADB tools FOR BruteForce
TO use this 1st you Have to Install the adb Driver in linux to install that you can type the following Command on terminal
(apt-get -y install android-tools-adb android-tools-fastboot)
This will Download all the necessary File required to do bruteforce
once you download adb tools now you only need to enable (usb DEBUGGING) on victims phone

STEP'S :-

Connect victim (usb debugging enable) phone on your laptop using usb cable then type adb devices in terminal 
that will show devies is offline to bring that online disconnect usb from android phone then reconnect usb cable
now again type (adb devices on a terminal) handshake will prompt on a android device click ok now you are good to go when victim will lock the screen you only have to plug usb cable to a victim phone run the Brute.sh file brute force will start

Steps to install

1. git clone https://github.com/A-Tool-com/Android-App_Lock-Bruteforce.git
2. chmod +x Brute.sh
3. connect to the victim device(USB DEBUGGING is enable)
4. ./Brute.sh
5. Bruteforce has started
