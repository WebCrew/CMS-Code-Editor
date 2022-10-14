# CMS-T-Editor


Thats a simple but awesome code editor with integrated file manager based on ACE and Emmet which you can use to run as ...

First I ask you to give my a STAR here at my Repository - would be very nice - thank you :)

1. a basic code editor to edit a project online. 
2. or to load the editor into the Themes folder of a CMS or Forum Script and then use it as a CMS / Forum Theme & Style Editor.



## Note:

You seem to be someone with a creative streak or an interesting hobby. Start to meet more people like you which maybe share the same creative hobbies or interests as you. Give a new platform a chance and register now at https://net-twin.de its free and awesome. More to come!


## About CMS Theme Editor
###### Name: CMS-T-Editor
###### Version: 0.0.5
###### PHP Version: 8.1 ready
###### No Database required
###### Author:  Andreas Holzer / @WebCrew / https://github.com/WebCrew
###### Description: Thats a code editor with integrated file manager based on ACE and Emmet which you can use to code or edit a project online - or and that was the main reason for the project, to load the editor into the Themes folder of a CMS or Forum Script and then use it as a CMS / Forum Theme Editor.



## Requirements

	1. A FTP Programm like FileZilla To Upload the Editor Folder and Files into Your CMS / Forum Theme Folder. Or to upload it on 
	Your Server to use it as a online Web-Editor with File Manager.
	2. Best Use with Firefox Browser, as in Chrome it will (maybe) give some error (to prevent xss attack) while saving a file 
	which has js in it (Google policies).



## Some Features Of The Editor

If you know the ACE editor and also have an idea of Emmet, then you already know many of the possibilities that the editor offers 
because it is based on these systems. 



#### With The File Manager You Can ...

	1. rename a file
	2. delete a file
	3. upload a file
	4. edit a file
	5. create a folder
	6. delete a folder
	7. rename a folder



#### With The Text Editor You Can ...

	1. edit a file
	2. save a file
	3. searcg, find and replace
	4. list the directory
	5. open and close dir in sidebar
	6. rename of a file
	7. select document type
	8. select font size
	9. select theme
	10. Clt + S (save enabled)
	11. open folder icon
	12. set editor according to document type (php, css, script, html, text, sass, less)
	13. cookie for font and theme
	14. make use of lots of keyboard shortcuts (press clt+alt+h to view keyboard shortcuts)
	15. Emmet enabled (cheatcode: https://docs.emmet.io/cheat-sheet/)



#### Miscellaneous

	1. login page comes with session
	2. logout
	3. set working directory
	4. reset working directory



## How To Use

	1. Use as a Default Web-Editor: Unzip my Editor Files and upload all Files on your Server. Now run 
	https://yourdomain/cms-t-editor.php and login with the password: password
	2. Use as a CMS / Forum Theme Editor: unzip my Editor Files then upload all files with a FTP Programm into the Theme 
	Folder of Your CMS or Forum. Depending on which CMS or which forum you use, you still have to integrate the following: Ask the 
	developer how to create a menu link in the CMS backend called for example "Theme Editor". Also ask the developer what to do so 
	that the cms-t-editor.php page with the link you created and the Editor will be displayed in the CMS backend. Now You see the 
	ditors Login Form. Loginn with the default password: password. Thats it.
	3. Note again, the login Password is: password
	5. steps to change the password:
	   - convert your new password in md5 hash (You can us: https://www.md5hashgenerator.com/)
	   - find the below code in cms-t-editor.php  (its around line 126)
           - if(md5($_POST['password']) == '5f4dcc3b5aa765d61d8327deb882cf99'){
           - replace **5f4dcc3b5aa765d61d8327deb882cf99** with your new hash


	   
## Whats next on the ToDo list

    1. I wanted to integrate TogetherJs to give the editor a collaborative feature - to work in a team. Unfortunately, TogetherJS is 
    no longer active and the community servers often have failures. So far there is no really good alternative - maybe you have one? 
    In any case, I'll keep an eye on that.

    2. Another thing is that I want to integrate a simple image editor, also for .svg files. I already have one on my harddrive.



## Screenshots

<a href="https://net-twin.de">
    <img src="https://github.com/WebCrew/All-purpose-CMS-theme-editor/blob/main/screens/login.png?raw=true" alt="Screenshot Login"
         title="Editor - Login View" align="left" />
</a>

<a href="https://net-twin.de">
    <img src="https://github.com/WebCrew/All-purpose-CMS-theme-editor/blob/main/screens/editor.png?raw=true" alt="Screenshot Editor"
         title="Editor View" align="left" />
</a>

***


## Special Thanks to:

Special Thanks to ACE, Emmet, Fontawesome and Google Fonts. 



## LICENSE

AGPL V3
Copyright (C) 2020/2022 by WebCrew / Andreas Holzer
