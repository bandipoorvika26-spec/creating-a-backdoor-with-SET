
# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:
## OUTPUT

<img width="1042" height="882" alt="Screenshot 2026-08-25 141441" src="https://github.com/user-attachments/assets/8f34040c-a860-4868-af51-4ac200323e90" />



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT




It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="946" height="688" alt="Screenshot 2026-08-25 141500" src="https://github.com/user-attachments/assets/b7d18b12-e828-4f23-80f5-8b61642a0136" />


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="822" height="295" alt="Screenshot 2026-08-25 141515" src="https://github.com/user-attachments/assets/0eca5f15-eba9-44e8-ba8c-a439347a9a78" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT
<img width="775" height="397" alt="Screenshot 2026-08-25 141529" src="https://github.com/user-attachments/assets/3bc5ecae-b76b-4d60-b7e7-f2370c7c820d" />




It shows the following screen in which the option Google can be selected:
## OUTPUT


<img width="971" height="426" alt="Screenshot 2026-08-25 141752" src="https://github.com/user-attachments/assets/efdb4cc7-9988-44d1-adb8-4d53167a2be9" />



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT





In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

<img width="1257" height="781" alt="image" src="https://github.com/user-attachments/assets/871ae2ab-8fae-47f7-b7ca-8311a0030dfe" />


SET logs the information regarding the Google credentials:
## OUTPUT
<img width="1596" height="437" alt="image" src="https://github.com/user-attachments/assets/7ebc15cd-1a7b-49cb-98a3-ca323c2bf8d8" />




SET logs the information in the xml file under /root/.set directory:
## OUTPUT

<img width="1600" height="630" alt="image" src="https://github.com/user-attachments/assets/3847225f-3276-422a-97a0-44f70866277c" />











## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
