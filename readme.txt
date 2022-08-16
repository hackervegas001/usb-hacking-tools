####################################
Enterprise Manager PassView v1.00
Copyright (c) 2002 - 2006 Nir Sofer

Web site: http://www.nirsoft.net
####################################

Description
===========
Enterprise Manager is a graphical tool that allows you to easily configure and manage
your SQL Server. If you connect your SQL Server by using the SQL Server authentication,
and you don't select the "Always prompt for login name and password" option, the password
and the user-name are stored on your Registry.

This utility enumerates all servers registered in your Enterprise Manager, and reveals
the user-names and the passwords, if they are stored on your computer.
It supports the Enterprise Manager of SQL Server 7.0 and SQL Server 2000. 


Known Limitations
=================
*This utility can show the Enterprise Manager passwords of the current logged-on user. 
 It cannot show the passwords of other users.
*The password of your SQL-Server can be revealed only if you use the SQL Server
authentication, and the "Always prompt for login name and password" is not checked.

License
=======
This utility is released as freeware.
Do not use this utility for illegal activity, and do not use it for getting a password
of SQL-Server that is not yours.
If you distribute this utility, you must include the executable file and the readme file
in the distribution package, without any modification !

 
Disclaimer
==========
The software is provided "AS IS" without any warranty, either expressed or implied,
including, but not limited to, the implied warranties of merchantability and fitness
for a particular purpose. The author will not be liable for any special, incidental,
consequential or indirect damages due to loss of data or any other reason. 
 

Using Enterprise Manager PassView
=================================
This utility is a standalone executable, and it doesn't require any installation process
or additional DLL files. In order to use it, extract the executable file (empv.exe) to 
any folder your want, and run it.

After you run this utility, you'll get a window with 6 columns containing information 
about your SQL Servers. All registered servers are listed in this window, but the 
user-name and passwords are shown only if they're stored in the Registry.
You can also save the servers list into a text file, by selecting the "Save To Text File"
from the File menu.


Feedback
========
If you have any problem, suggestion, comment, or you found a bug in my utility, 
you can send a message to nirsofer@yahoo.com

