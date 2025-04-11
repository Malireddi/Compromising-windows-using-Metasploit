## Compromising-windows-using-Metasploit
Compromising windows using Metasploit

## AIM:
To Compromise windows using Metasploit .

```
Register Number : 212223100037
Name: Nandyala Malyadri Reddy
```

# Design Steps: 
1. Install kali linux either in partition or virtual box or in live mode.
2. Investigate on the various categories of tools as follows.
3. Open terminal and try execute kali linux commands.

# Execution Steps and it's Output:
## Step1: Identify the Attacker's IP Address
Determine the IP address of the attacker's system.
![image](https://github.com/user-attachments/assets/ed0f8e14-c32d-419f-8a83-4381ae8d4fef)

## Step2:Launch the Metasploit Console
Invoke the msfconsole

![image](https://github.com/user-attachments/assets/e004c283-21ad-40d8-b1be-c02f83270270)

## Step3:Generate Payload Using msfvenom
Execute the following command to generate a Windows Meterpreter reverse shell payload.exe 
![image](https://github.com/user-attachments/assets/51d91a4a-8597-49f4-bc9b-fb35f6527ff7)

## Step4: SetUp an HTTP Server
Run the Python command to establish an HTTP server  for file distribution.

![image](https://github.com/user-attachments/assets/de463728-5598-46d1-89cc-2bbeb6150724)
## Step5: Distribute the Payload
Share the .exe file with the target system via any medium or the HTTP server. Once the victim downloads and executes the file,the exploit is triggered.
![image](https://github.com/user-attachments/assets/10db3dd9-2df0-427c-a556-e05e7b37da03)

## Step6: Establish a Connection
On Kali linux, reopen the terminal and invoke "msfconsole".Follow the necessary steps to establish a connection with the victim's device.
![image](https://github.com/user-attachments/assets/82e286cc-733e-4af3-91e9-db056ec953f9)

## Step7:List Commands
Use the help command to list available operations.

![image](https://github.com/user-attachments/assets/6e31ca21-f0f7-4ab9-b4ab-887d5a77dae0)
## Step8:
For example,the "key_scan" command captures the victim's screen and saves it in the attacker's home directory.

![Screenshot 2025-04-07 114811](https://github.com/user-attachments/assets/43a6c14c-460a-4b77-be81-ec20a46f66c6)


## RESULT:
The Metasploit framework is  used to compromise windows and is examined successfully.
