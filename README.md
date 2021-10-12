# Keylogger
just a basic keylogger free to use , its in python but if you wish to use it for windows you can but you will need to convert the python file to exe file.

to do that heres what you need to do step by step 


Step 1: 
Install the library pyinstaller. 
Type below command in the command prompt. (be sure cmd is in adminstrator mode) 

pip install pyinstaller

Step 2: 
Go into the directory where your ‘.py’ file is located. 

C:\Users\'your username'\AppData\Local\Programs\Python\Python37\Scripts

or wherever it maybe in your drives

Step 3: 
Press the shift⇧ button and simultaneously right-click at the same location. You will get the drop down menu

Step 4: 
Click on ‘Open PowerShell window here’. 


Step 5: 
Type the command given below in that PowerShell window.  

pyinstaller --onefile -w 'Keylogger.py'




In case of any errors

The correction while typing the above command:  

.\pyinstaller --onefile -w 'Keylogger.py'

For any missing package:
pyinstaller --hidden-import 'package_name' --onefile 'Keylogger.py'




Step 6: 
After typing the command ‘Hit the Enter’. 
It may take some time to finish the process.




Step 7: 
See the directory, there will be changes 

‘build’ folder and ‘Keylogger.spec’  or it maybe '1.spec', is of no use. You can delete these if you want, it will not affect your ‘.exe’ file. 




Step 8: 
Open ‘dist’ folder above. Here you will get your ‘.exe’ file.



Right-click on the file and check the properties. it will confirm it is in fact exe :)













