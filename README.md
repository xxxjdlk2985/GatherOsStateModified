gatherosstatemodified.exe file used to activate Windows 10/11 permanently for free.

Steps:
1.Right click on the file gatherosstatemodified.exe, go to properties and set the compatibility mode to Windows XP SP3.
2. Open Windows Powershell as Administration and enter the below command:

$value = (Get-ItemProperty HKLM:\SYSTEM\CurrentControlSet\Control\ProductOptions).OSProductPfn

path:\to\gatherosstatemodified.exe /c Pfn=$value`;PKeyIID=703977068648967916672893815045129414520161831634327680443048245

clipup -v -o -altto C:\Files\

slmgr /ato

