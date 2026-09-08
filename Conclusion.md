# Conclusion

Responder.py : returns NTLMv2 hash

Ntlmrelayx.py : relaying captured hash from responder.py to the target machine/s , which will give u a lot of things such as : 
	- local sam hases 
	- smb interactive shell
	- executing malicious files on target machine 
	- executing commands

mitm6 : a tool advertises itself as a source of IPv6 network configuration and DNS information. As a result, Windows machines on the network may begin using DNS information influenced by the attacker. 

hashcat : a password cracking tool 

impacket-secretsdump: a tool can dump a lot of things such as ntds , sam , lsa , ...etc

crackmapexec/netexec : is a powerfull tool used for Windows and Active Directory enumeration and authentication testing. 

A passback attack a security exploit where an attacker reconfigures a network device—like a multifunction printer (MFP) or server—to point its integrated service settings (such as LDAP or SMTP) to a rogue, attacker-controlled server to capture credentials in plaintext.

psexec-msfconsole : command shell execution
psexec.py: command shell execution

smbexec.py : semi-interactive shell execution

wnuexec.py : Remote execution tools for Windows that rely only on WMI and PowerShell

powerview : active directory enumeration tool
bloodhound : active directory enumeration tool

Token Impersonation: is a Windows feature that allows a process or thread to temporarily act as another user by using that user's access token. it requiers high privileged user (local admin ,prefere to be  SYSTEM).

Kerberoasting attack:  is a post-compromise Active Directory attack where a domain user requests a Kerberos service ticket (TGS) for a service account and then attempts to crack the ticket offline to recover the service account's password.

GPP attack : is an Active Directory attack that abuses passwords stored in Group Policy Preferences.

URL File attack: A credential-capture technique that abuses Windows .url (Internet Shortcut) files to trigger automatic network authentication when the file's icon or target points to an attacker-controlled resource.


![image.png](assets/node_47_img_1.png)

