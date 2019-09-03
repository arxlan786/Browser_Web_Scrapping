# Auto hide.me VPN Personal Account Python Script

## How is my program related to hide.me? 

What this script does is that it automates the boring and recurring task of making a free account on [HideME](https://hide.me).
It does so in following 5 simple steps:

1. It goes to [HideME](https://hide.me) homepage and clicks on yellow 'Download' button which opens the next page in which there are two plans listed.
2. This script chooses the free plan. 
3. It makes a disposable email address from [EmailFake](https://emailfake.com) and provides this email to [HideME](https://hide.me) for sign up.
4. [HideME](https://hide.me) sends a confirmation email to that disposable address. 
5. This scripts recieves the confirmation email from [HideME](https://hide.me) and click on 'Activate account' button.

With these 5 simple steps you have a new hide.me account.  

Username and password of the new account will be shown on the console.

I have also converted this python script into an .exe for more ease. So to make your hideme account with just one click you can directly use the autohideme.exe file in 'HideMe' folder. Or you can always run the script if you don't wan to run the exe. 

## NOTE

1. More robust error handling in case of faults in internet conectivity.
2. If temp email is blocked by hide.me then this script fails. So ideally it should generate a new temp email and retry. 

This script is tested on Python 3.7.3 (Windows 10)
Feel free to experiment with it. 
