## Exercise 3:VSFTPD Backdoor Exploitation
## Procedure: I selected the exploit/unix/ftp/vsftpd_234_backdoor module,target IP to 192.168.56.101 and ran the exploit
## Result: A command shell was successfully obtained. The whoami and id commands confirmed root access
![Exercise 3 Root Shell](https://raw.githubusercontent.com/omotolamariam70-byte/Metasploit-Hands-On-Lab/6c5826bfbf9ff96c432d2b05e8a250a1d4becd41/Exercise3_Root_shell.png)

 ## Exercise 4: Samba Usermap Script Exploitation
## Procedure: I Selected the `exploit/multi/samba/usermap_script` module and configured the target IP address as `192.168.56.101`. Then, I ran the exploit against the Metasploitable2 virtual machine.
## Result:** A command shell was successfully obtained. The `whoami` and `id` commands confirmed that the session had root privileges
![Exercise 4 Root Shell](Exercise4_Root_Shell.png)
