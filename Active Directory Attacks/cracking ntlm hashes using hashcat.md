# cracking ntlm hashes using hashcat

Administrator:500:aad3b435b51404eeaad3b435b51404ee:31d6cfe0d16ae931b73c59d7e0c089c0:::
Frank Castel:1001:aad3b435b51404eeaad3b435b51404ee:2faf5f4a6e588f18f1f84616da5ba9a7:::
Alice:1001:aad3b435b51404eeaad3b435b51404ee:4039730e1bf6e10dd01eaac983db4d7c:::


hashcat.exe -m 1000 &lt;targetFile&gt; &lt;passwordlist&gt; -O







notice that administrator's password is blank means password for administrator disabled


![image.png](assets/node_46_img_1.png)


![image.png](assets/node_46_img_2.png)


![image.png](assets/node_46_img_3.png)

