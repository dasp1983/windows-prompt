## About:

Commands to change Windows command prompt. For all users, or just for the local user.

## Screenshot:

![screenshot_windowsprompt](https://user-images.githubusercontent.com/83188092/118001151-bf177400-b346-11eb-8056-0425bcefd668.png)

## How-To:

#### System-Wide:

1. Open the Command Prompt as an Administrator.

![screenshot_windowsprompt2](https://user-images.githubusercontent.com/83188092/118002821-49aca300-b348-11eb-9efb-fe5c4cccdb9b.png)

2. Copy and Paste the following command.

`setx PROMPT /M $E[37;90m┌─[$E[32;92m:)$E[37;90m]-[$E[37;40m%time:~0,8%$E[37;90m]-$E[37;95m[$E[37;31m%username%$E[37;96m@$E[32;92m%computername%$E[37;95m]$E[37;90m-[$E[40;96m$p$+$E[37;90m]$_└─$g$S$E[37;40m`

3. Close the Command Prompt and restart it as an Local User.

#### Local User:

1. Open the Command Prompt as an Local User.

Press **Windows Key+R**. Type **cmd** and then click **OK**.

2. Copy and Paste the following command.

`set prompt=$E[37;90m┌─[$E[32;92m:)$E[37;90m]-[$E[37;40m%time:~0,8%$E[37;90m]-$E[37;95m[$E[37;31m%username%$E[37;96m@$E[32;92m%computername%$E[37;95m]$E[37;90m-[$E[40;96m$p$+$E[37;90m]$_└─$g$S$E[37;40m`

## Author:

Me. Information gathered from all over the internet.
