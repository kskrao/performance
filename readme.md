Steps to Install JMeter:
Tool Details:
Tool Name – JMeter
Version - apache-jmeter-3.0
Step 1) Install Java
Step 2) Download JMeter
Download the JMeter software from below link 	http://jmeter.apache.org/download_jmeter.cgi (Choose the Binaries file (either zip or tgz) to download)
Step 3) Installation
	Unzip the zip/tar file into the directory where you want JMeter to be installed
JMeter directories:
/bin: Contains Jmeter bat file and log file
/docs: JMeter documentation files
/extras: ant related extra files
/lib/: Contains the required Java library for JMeter
/lib/ext: contains the core jar files for JMeter and the protocols
/lib/junit: JUnit library used for JMeter
/printable_docs:
Step 4) Launch JMeter
Start JMeter in GUI Mode, run the bat file /bin/jmeter.bat to start JMeter in GUI mode as shown below:
Adding Library Files:
Procedure to install webdriver sampler plugins into JMeter:
1)Download the plugin from below link and extract the zip file:
                https://jmeter-plugins.org/?search=jpgc-webdriver
                Download Versions: 1.4.0
2)Open the extracted folder and copy all the jar files which is under the lib folder except ext folder files.
3)Go to the jmeter installation folder and paste the copied jars into lib folder(ex: C:\Data\Software\apache-jmeter-3.0\apache-jmeter-3.0\lib)
4)Go back to extracted folder and copy all the jar files which is under the ext folder
5)Go to the JMeter installation folder and paste the copied jars into ext folder (ex: C:\Data\Software\apache-jmeter-3.0\apache-jmeter-3.0\lib\ext)
6)Restart the JMeter
Please provide the proper path of chromedriver.exe, as below.
JMeter Application:
1.	To create the Thread Group:
Right click on the test plan and create thread group: Eg: POA
2.	To Create User Defined Variables
Right click on the thread group and create User Defined Variables:
eg: Locators path and its name
