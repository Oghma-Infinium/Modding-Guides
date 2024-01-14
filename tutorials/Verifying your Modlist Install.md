# Verifying your Modlist Installation with Wabbajack - by iAmMe

## Introduction

Sometimes modlists aren't perfectly installed - computers are fallible and there are many reasons as to why a modlist doesn't install 100% correctly *but* Wabbajack has a function built in to verify a modlist install. If you suspect that something isn't right with your install for whatever reason, you can run this to get Wabbajack to check.

## Opening the Wabbajack Terminal

So, how do we do this? First, start by opening Wabbajack and clicking the gear icon in the top right to open the settings page:

![](https://raw.githubusercontent.com/iAmMe27/WoD/main/img/WJWindow.png)

Once the settings page is open, click the `Launch Wabbajack CLI` button:

![](https://raw.githubusercontent.com/iAmMe27/WoD/main/img/WJCLI.png)

## Verifying the Modlist

In the terminal window that opens, type in the following command:

`cd cli`

Press Enter, then type in:

`wabbajack-cli verify-modlist-install -m {path to your WJ folder}\3.4.2.0\downloaded_mod_lists\{modlist wabbajack file} -i "{modlist install folder path}"`

> **Remember to remove the `{ }` brackets in the command and edit those sections so that it points to your own install paths!**

I recommend copy-pasting the above command into a notepad program, then filling out the bracketed sections on said notepad to accommodate your directories, and copy-pasting the command back into the terminal.

Using my Vagabond install as an example, the command would look like this for me:

`wabbajack-cli verify-modlist-install -m F:\Wabbajack\3.4.2.0\downloaded_mod_lists\WakingDreams_@@_vagabond.wabbajack -i "F:\Vagabond"`
