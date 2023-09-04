# Verifying your Modlist Installation with Wabbajack - by iAmMe

Sometimes modlists aren't perfectly installed - computers are fallible and there are many reasons as to why a modlist doesn't install 100% correctly *but* Wabbajack has a function built in to verify a modlist install. If you suspect that something isn't right with your install for whatever reason, you can run this to get Wabbajack to check.

So, how do we do this? First, start by opening Wabbajack and clicking the gear icon in the top right to open the settings page:

![](https://raw.githubusercontent.com/iAmMe27/WoD/main/img/WJWindow.png)

Once the settings page is open, click the `Launch Wabbajack CLI` button:

![](https://raw.githubusercontent.com/iAmMe27/WoD/main/img/WJCLI.png)

In the terminal window that opens, type in the following command: 

`cd ..`

Press Enter, then type in:

`.\wabbajack-cli.bat verify-modlist-install -m {path to your WJ folder}\3.2.0.1\downloaded_mod_lists\{modlist wabbajack file} -i "{modlist install folder path}"`

> **Remember to remove the `{ }` brackets in the command and edit those sections so that it points to your own install paths.**

Using my install of Vagabond as an example, the command would look like this for me:

`.\wabbajack-cli.bat verify-modlist-install -m C:\Wabbajack\3.2.0.1\downloaded_mod_lists\Vagabond.wabbajack -i "F:\Vagabond"`