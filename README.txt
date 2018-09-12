 ________________________
|                        |
# KCL Mailman Downloader #
|________________________|

This program works in x steps
1) Double click Mailman_Downloader.exe, you should get a friendly message asking you to give the name of the mailing list. 

	For example if you wanted everybody on imsci@kcl.ac.uk, you would input 'imsci' (without the quote marks)

2) It will then ask you for the admin password for the mailinglist. This is the password you use to log into:
	https://mailman.kcl.ac.uk/mailman/admin/[your-list]/

3) Provided you've entered the username and password correctly, you should the program saving the names of all the people. 

4) Close the program by pressing Enter once it's finished. Double click on the "Output" folder and you should see a file called [your-list].txt open this, and you'll find a long list of all the email addresses on the list you requested. 

_______________________

If you run into any problems feel free to email Matt on mrallinson@kcl.ac.uk

This program was written in Python3 and converted using pyinstaller. If you want to take a look at the source-code it's available at https://github.com/mattallinson/Mailman
