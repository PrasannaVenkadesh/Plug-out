Plug-out
========

> Plug-out is a python script which when executed will display notification when laptop's battery charge gets full. The idea is to save electricity from being wasted. Once the Charge is full, Please plug-out the power cable. Go Green.

Why Plug-out?
-------------

> Both Gnome 3 and Ubuntu's Unity battery indicators, doesn't show or Pop-up a notification in workspace when battery charge gets full. But notifies when battery is about to exhaust. To bring attention to users about battery has been charged fully.

How to use?
------------

####1. Download, Extract & Navigate
* Download either tar or zip file.
* Extract them into a folder.
* Use Terminal and navigate to the extracted folder.

####2. Issue Executable Permission
* In order to run this script, you need to issue permission for the file to execute. Use the below code to issue executable permission for all users and groups.

		chmod a+x Plug-out

* If that doesn't works, try with 'sudo' like this

		sudo chmod a+x Plug-out

####3. Don't wait, Run.

	./Plug-out

###### A Github page with Screenshots is getting ready, Check screenshots before using.

> Note : This script can be added to System startup applications, so that you need not run everytime. Everytime when you start your system, it runs in background and displays notification whenever charge gets full. Notification will be repeated every minute, until Unplugging the cable from laptop.
