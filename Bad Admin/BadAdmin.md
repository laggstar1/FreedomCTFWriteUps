# Needle Phobia

Website: https://webexploit.freedomctf.org/_/sqli1/login

Question: The admin is hiding information from their employees, login as an admin to find what has been hidden.

Hint: None

## Website 
Option 1:
    Put admin' -- for the username and password.

!['Option 1'](./Option1.png)

Option 2:
    Put admin' and 1=1 -- for the username and password.

!['Option 2'](./Option2.png)

Then the website will return the flag, flag{Oh_Wow_you_learnt_smth}.

!['Flag'](./Flag.png)