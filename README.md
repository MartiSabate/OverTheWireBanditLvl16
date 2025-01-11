# OverTheWireBanditLvl16

This is the level 16 automatic solution script for Over The Wire Bandit Linux challenge! 

The goal of this script is to retrieve an SSH private key for the user bandit17.

The script will first scan for open ports from 31000 to 32000.

When an open port is found, it will attempt to send the password from the user bandit16 found in /etc/bandit_pass/bandit16 through an SSL client and store the response in a file named <PORT_NUMBER>.txt

It is expected to receive a private RSA key that will allow you to access to the next level as the user bandit17


![image (96)](https://github.com/user-attachments/assets/50b99e3f-354c-474f-937c-e49953d68a55)
