# Get the a Simple cyberpunk Login Screen for SLiM Display Manager

# Themes of SLiM Display Manager

SLiM Display Manager is a simple login manager which, because of its simplicity, makes it much faster than normal login managers that are loaded with lots of settings.

If you don't need so many settings in your login manager and you are looking for simplicity and speed, use SLiM Display Manager for a more fluid login with elegant themes like this ;)

---

## How to install the SLiM Display Manager?

SLiM Display Manager is in the repositories of all most Linux distributions, you only need to execute some commands; So, open your application menu, find the terminal and type.

- For Debian/Ubuntu users and derivatives:
  - "sudo apt install slim"

- For Arch Linux and derivatives:
  - "sudo pacman -S slim"

- For OpenSuse and derivatives:
  - "sudo zypper install slim"

- For Fedora and derivatives:
  - "sudo yum install slim"

---

Now, at the end of the installation a message will appear inside the terminal, the message asks for authorization to switch between the current Display Manager, GDM, LightDM, SDDM, etc..., and SLiM, so choose SLiM with the arrow keys and press enter.

If that does not happen, or you want to return to the previous Display Manager, you can run the following command to reappear the window inside the terminal and move between the installed Display Manager.

The command is: **"sudo dpkg-reconfigure slim"** (or GDM, SDDM, etc, It depends on the Display Manager you are currently using.)

---

## Exporting themes to the slim path

To apply a third-party theme, you just have to download the theme of your liking (you can review the ones I've done and use them xD) then extract and move the themes in the following path: ***/usr/share/slim/themes.***

Keep in mind that you need to open the file manager in root mode, for that, you just have to run this command in the terminal: **"sudo nautilus"** (or the file manager you are using), put your password and the file manager will appear with super user permissions, then you can search for the path and move the folders of themes to the path mentioned above.

---

### Applying and configuring the themes.

Now that you have exported the themes to the SLiM themes folder, you need to configure a file to display the theme of your choice as a Display Manager.
So, go back to the terminal and run the command: **"sudo gedit /etc/slim.conf"** (or use your favorite text editor) press ***"ctrl + f"*** to find the specific line you need to modify, so type: ***"current_theme"*** in the search box, and change the name of the theme that is in use to the name of the theme you want to use. for example: ***"current_theme Catalina"***

---

**And that's it, now restart your computer and enjoy the new theme applied.
Don't forget to vote if you liked my work, your vote is important.**

# ENJOY IT!!


## Extras

- To change Desktop Sessions just press **"F1"**

- If you can take a screenshot just press the key **"F11"**

- Note: You can't use the cursor in SLiM Display Manager; so if you want to "shutdown or reboot", in the login screen, you need to **type "halt" or "reboot" in the username box and then write the root password,** and it's done, so the icons below the screen in some themes are just decoration for more better looking.
