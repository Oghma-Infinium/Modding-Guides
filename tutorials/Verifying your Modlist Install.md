# Verifying your Modlist Installation with Wabbajack - by iAmMe

## Introduction

Sometimes modlists aren't perfectly installed - computers are fallible and there are many reasons as to why a modlist doesn't install 100% correctly *but* Wabbajack has a function built in to verify a modlist install. If you suspect that something isn't right with your install for whatever reason, you can run this to get Wabbajack to check.

## Opening the Wabbajack Terminal

So, how do we do this? First, start by opening Wabbajack and clicking the gear icon in the top right to open the settings page:

![](https://raw.githubusercontent.com/iAmMe27/WoD/main/img/WJWindow.png)

Once the settings page is open, click the `Launch Wabbajack CLI` button:

![](https://raw.githubusercontent.com/iAmMe27/WoD/main/img/WJCLI.png)

## Configuring the Terminal

In the terminal window that opens, you'll need to follow these steps precisely:

1. Highlight the directory path before the `>` symbol, but **make sure you do not include the `>` symbol**. Then copy that directory by pressing `Ctrl+C` on your keyboard

2. Type in the follwing: `cd` *(Do not press enter yet!)*

3. Press space on your keyboard, then press `Ctrl+V`

4. Type in `\cli` at the end of the directory you pasted, then press `Enter` on your keyboard

If you've done the following steps above correctly, the terminal should now have `\cli` attached to the end of the directory before the `>` symbol.

In case you're a visual learner, GIF example is below:

![](https://raw.githubusercontent.com/Oghma-Infinium/Modding-Guides/main/images/WJVerify%20Example.gif)

## Verifying the Modlist

After you've done the following steps above, you'll need to type in the command below:

`wabbajack-cli verify-modlist-install -m {path to your WJ folder}\3.4.1.0\downloaded_mod_lists\{modlist wabbajack file} -i "{modlist install folder path}"`

> **Remember to remove the `{ }` brackets in the command and edit those sections so that it points to your own install paths!**

I recommend copy-pasting the above command into a notepad program, then filling out the bracketed sections on said Notepad to accomadate your directories, and copy-pasting the command back into the terminal.

Using my Vagabond install as an example, the command would look like this for me:

`wabbajack-cli verify-modlist-install -m F:\Wabbajack\3.4.1.0\downloaded_mod_lists\WakingDreams_@@_vagabond.wabbajack -i "F:\Vagabond"`