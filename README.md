Moodle "Castle" theme repository
===============================

Castle is Moodle's theme that makes online environments more clean and intuitive for learners and educators. Its intuitive layout is optimised for online learning, focusing on the things that matter - your learning activities and content.

Castle is built on Boostrap4 and Mustache templates.

Documentation
=============

You can see the theme documentation on: https://github.com/adlnet/castle-moodle

Developed and maintained by
===========================
ADL 
 


Installation
------------

**First way** How To Install Moodle Theme (From Drop Down Selection)

- You can change your moodle theme to our custom Theme easily via Moodle.

Step 1- Log into Moodle
Step 2- Click on Administration
Step 3- Click on Appearance
Step 4- Click on Themes
Step 5- Click on Theme Selectors
Step 6- Click on CustomMoodleTheme and click APPLY.
You should now see your moodle theme applied globally throughout the application for you

**Second way** How To Install Moodle Theme via ZIP (Option A- Uploading From Zip via FTP)

- Download the zip file of the theme
- Extract to its own named folder
- Using your FTP program, upload this folder to the /theme folder of your Moodle installation
- Ensure the new theme folder and its contents are readable by the webserver. Change the Read and Write permissions for the files and folder. Incorrect permissions may prevent display of the newly installed theme.
- Go to Site administration > Notifications to see if the new theme requires any decisions or updating of Moodle code.

**Third way** How To Install Moodle Theme via ZIP (Option B- Directly From Moodle)

Any custom theme is seen as a plugin on Moodle. So, the following instructions apply.

- Go to the Moodle plugins directory, select your current Moodle version, then choose a plugin with a Download button and download the ZIP file.
- Login to your Moodle site as an admin and go to Administration > Site administration > Plugins > Install plugins.
- Upload the ZIP file. You should only be prompted to add extra details (in the Show more section) if your plugin is not automatically detected.
- If your target directory is not writeable, you will see a warning message.
Check the plugin validation report