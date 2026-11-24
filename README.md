# Windows CLI Basics THM

## Objective
In this TryHackMe room my learning objectives were: 

- Use the windows command line confidently
- Navigate folders without clicking
- Find files when you only know their name
- Read files using the terminal
- Collect basic system and network information

### Skills Learned
- Navigate files and folders without clicking
- Locate files even when you didn’t know where they were
- Reveal hidden files and directories
- Read file contents directly from the terminal
- Gather basic system and network information

### Tools Used
I used different command line prompts such as:

- cd -I used this to change directories
- dir - I used this to list the contents of the current directory
- dir /a - I used this to list everything in the current directory including hidden files
- cd .. - I used this to move back to the previous directory
- cls - I used this to clear the text from the terminal
- type - I printed the contents of the file name directly into the command prompts
- whoami - I used this to print the username of the account you're currently logged into
- hostname - I used this to be able to see the computers name as it helps identify network systems
- systeminfo - I used this to learn details about the OS such as: OS name, OS version and system type
- ipconfig - I used this to show the machines network configuration mainly looking for an IPv4 address and a default gateway

## Steps
 Step 1. In this step I used the dir command to list the files and folders present in the current directory.
 
<img width="487" height="398" alt="Windows CLI basics" src="https://github.com/user-attachments/assets/9cd5b5dd-e5e4-4281-ab4f-3acbca8e020c" />

Step 2. In this step I used the dir /a command to list all the files and folders present in the current directory including hidden ones.

<img width="477" height="401" alt="Windows CLI basics 2" src="https://github.com/user-attachments/assets/0b3af75f-051d-4455-93fa-64577d8c9948" />

Step 3. In this step I practiced moving around the filesystem, so I used cd to change directory to the Documents folder and I then used cd .. to move back to the administrator folder.

<img width="473" height="157" alt="Windows CLI basics 3" src="https://github.com/user-attachments/assets/289a846c-ec52-45a8-9380-a045b600bb25" />

Step 4. I used the command dir /s task_brief.txt. The /s flag told windows to search all the subfolders starting from my current directory and I used this to show me the full path to the file I wanted.

<img width="477" height="354" alt="Windows CLI basics 4" src="https://github.com/user-attachments/assets/887d2aad-1404-4aca-9f7e-a9833c1e0087" />

Step 5. After successfully locating the file in the previous step, I then used cd followed by the path to the file I wanted, then used dir to check that the file was in fact listed there.

<img width="484" height="259" alt="Windows CLI basics 5" src="https://github.com/user-attachments/assets/25d7d085-024b-483a-942a-f4b06fb98e91" />

Step 6.  I used the type command to print the contents of the file I wanted directly into the command prompts. Using this I found the flag on TryHackMe.

<img width="458" height="137" alt="Windows CLI basics 6" src="https://github.com/user-attachments/assets/888b289c-34b1-4263-86b1-3709f2e81210" />

Step 7. I used whoami to find out the username of the account I was logged in as, I used hostname to see the name of the computer and I used ipconfig to show the machines network configuration. Using this information I was able to answer the questions on TryHackMe.

<img width="488" height="359" alt="Windows CLI basics 7" src="https://github.com/user-attachments/assets/f7416b75-fd80-41bf-a41c-55a8f678c178" />







