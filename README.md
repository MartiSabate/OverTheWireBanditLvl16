# OverTheWireBanditLvl16

This is the level 16 automatic solution script for Over The Wire Bandit Linux challenge!

This script will first scan for open ports in the range from 31000 to 32000.

When an open port is found, it will attempt to send the password from the user bandit16 found in /etc/bandit_pass/bandit16 through an SSL client and store the response in a file named <PORT_NUMBER>.txt

It is expected to receive a private RSA key that will allow you to access to the next level as the user bandit17

![image (95)](https://github.com/user-attachments/assets/4e675564-80df-430e-9de3-1652ff06513b)
