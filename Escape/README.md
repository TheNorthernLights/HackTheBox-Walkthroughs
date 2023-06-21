Hack The Box Walkthrough - Escape

Escape - https://app.hackthebox.com/machines/531

Escape is a standalone Active Directory machine which simulates gaining admin access to a Domain Controller. 

Initial Foothold exploits a clear text password for MSSQL account from which we can listen to events and crack the SQL_SVC hash.

Once we have gained an initial shell, we can then search the log files and other users. We can see that a user has tried to login and the password is yet again in clear text.

Once we have logged-in as this user, basic enumeration shows that we can exploit an Active Directory Certificate Services to gain admin privileges.

We can download and execute the PreCompiled binary and gain access to the admin user by logging-in via the NTLM Hash.
