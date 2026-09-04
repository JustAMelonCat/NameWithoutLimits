# NameWithoutLimits
A simple registry file that can change your computers name without the normal limitations

To use, simply change the all values in the .reg to be your desired computer name
Example:

Windows Registry Editor Version 5.00

[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\ComputerName\ComputerName]
"ComputerName"="My Computer"

[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\ComputerName\ActiveComputerName]
"ComputerName"="My Computer"

[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\Tcpip\Parameters]
"NV Hostname"="My Computer"
"Hostname"="My Computer"

