# PowerView

<?xml version="1.0" encoding="UTF-8"?>
<node><rich_text justification="left"></rich_text><rich_text>



</rich_text><rich_text justification="left"></rich_text><rich_text>




</rich_text><rich_text justification="left"></rich_text><rich_text>




</rich_text><rich_text justification="left"></rich_text><rich_text>




</rich_text><rich_text justification="left"></rich_text><rich_text>


</rich_text><rich_text justification="left"></rich_text><rich_text>


</rich_text><rich_text justification="left"></rich_text><rich_text>


</rich_text><rich_text justification="left"></rich_text><rich_text>





</rich_text><rich_text justification="left"></rich_text><rich_text>


</rich_text><rich_text justification="left"></rich_text><rich_text>



</rich_text><rich_text justification="left"></rich_text><rich_text>



</rich_text><rich_text justification="left"></rich_text><rich_text>


</rich_text><rich_text justification="left"></rich_text><rich_text>


</rich_text></node>



![image.png](assets/node_36_img_1.png)


![image.png](assets/node_36_img_2.png)


![image.png](assets/node_36_img_3.png)


![image.png](assets/node_36_img_4.png)


![image.png](assets/node_36_img_5.png)


![image.png](assets/node_36_img_6.png)


![image.png](assets/node_36_img_7.png)


![image.png](assets/node_36_img_8.png)


![image.png](assets/node_36_img_9.png)


![image.png](assets/node_36_img_10.png)


![image.png](assets/node_36_img_11.png)


![image.png](assets/node_36_img_12.png)


![image.png](assets/node_36_img_13.png)

## commands

<?xml version="1.0" encoding="UTF-8"?>
<node><rich_text>commands:

Get-NetDomain
Get-NetDomainController
Get-DomainPolicy
(Get-DomainPolicy)."system access"
Get-NetUser

Get-NetUser | select cn
Get-NetUser | select samaccountname
Get-NetUser | select description

Get-UserProperty 
Get-UserProperty -Properties pwdlastset
Get-UserProperty -Properties logoncount
Get-UserProperty -Properties badpwdcount

Get-NetComputer
Get-NetComputer -FullData
Get-NetComputer -FullData | select OperatingSystem

Get-NetGroup -GroupName "Domain Admins"
Get-NetGroup -GroupName *admin*


Get-NetGroupMember -GroupName "Domain Admins"

Invoke-ShareFinder

Get-NetGPO
</rich_text></node>



