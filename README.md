# NotTheFrontDoor

What we in the security world would call a 'Backdoor'.

This backdoor is used to gain access to, execute commands, download and upload files in both directions (from server to target and vice versa)

Only things needed are your Kali Linux machine which will be used as your server for the server.py file and a target machine which will be used to run the backdoor.py file.

Insert the IP Address of your Kali Linux machine in both requisite parts of the backdoor.py and server.py when you open/fork the repo. 

You will need to convert the backdoor.py file into an executable(.exe) file and that can be done via pyinstaller or any type of converter of your choosing. 

If you use pyinstaller run the command 'pyinstaller backdoor.py --onefile --noconsole' in the directory that your backdoor.py file is in on target machine and the .exe file will be in a folder named 'dist' 

Run the file on target and listen on Kali Linux by executing the command 'python3 server.py' in Kali terminal. 

DISCLAIMER: THIS PROGRAM IS ONLY FOR TESTING AND EDUCATIONAL PURPOSES AND WAS CREATED IN GOOD FAITH. ANY MALICIOUS USE OF THIS PROGRAM WILL NOT HOLD THE CREATOR RESPONSIBLE. ANY ACTION YOU TAKE WHEN USING THIS PROGRAM IS STRICTLY AT YOUR OWN RISK. 

