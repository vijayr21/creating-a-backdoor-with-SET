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
The command `sudo setoolkit` in the prompt gives menu with set prompt:  
## OUTPUT:  
<img src="https://github.com/user-attachments/assets/deb7b61f-d18d-462b-a829-a5aaa3ea241c" width=600>

The command `sudo setoolkit` in the prompt gives menu with set prompt. Select menu 1 for Social Engineering Attacks.  
It displays the following menu and select 2 for Website Attack Vectors:  
## OUTPUT:  
<img src="https://github.com/user-attachments/assets/73ad3a4c-03e5-4bb1-993b-5b60c7591458" width=600>

The website Attack Vectors displays the following menu. In this menu, 3 for Credential Harvester Attack Method is selected:  
## OUTPUT:  
<img src="https://github.com/user-attachments/assets/10d04651-ca85-41f4-83d9-168ebba93108" width=600>

The Credential Harvester Attack Method displays the following menu. In this menu, 1 for Web Templates is selected:  
## OUTPUT:  
<img src="https://github.com/user-attachments/assets/84e9d98c-d6a4-4968-b048-13e2e0782d53" width=600>

The Credential Harvester Attack Method displays the following menu. In this menu, 1 for Web Templates is selected.  
It shows the following screen in which the IP address of the attacker needs to be given (default value):  
## OUTPUT:  
<img src="https://github.com/user-attachments/assets/e95c8b4b-7fcf-4f07-af23-03e38596c054" width=600>

It shows the following screen in which the option Google can be selected:  
## OUTPUT:  
<img src="https://github.com/user-attachments/assets/18a611da-b225-4b2f-b8ca-bd24d98de46d" width=600>

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:  
## OUTPUT:  
<img src="https://github.com/user-attachments/assets/c4577e78-b273-4955-a582-1c9302289934" width=600>

In Windows IE, on giving the URL `http://192.168.1.2`, the fake Google page is displayed. The victim can enter the username and password.  
## OUTPUT:  
<img src="https://github.com/user-attachments/assets/9c6ef595-8656-479e-95c4-1bd90710e750" width=600>

SET logs the information regarding the Google credentials:  
## OUTPUT:  
<img src="https://github.com/user-attachments/assets/aed6f0c2-6c9e-44a2-a35a-dcbe20bce335" width=600>

SET logs the information in the XML file under `/root/.set` directory:  
## OUTPUT:  
<img src="https://github.com/user-attachments/assets/19d58cdd-74d6-4467-ad0c-1b676701fc82" width=600>

## RESULT:
The Social Engineering Toolkit (SET) is used to create a backdoor and is examined successfully.
