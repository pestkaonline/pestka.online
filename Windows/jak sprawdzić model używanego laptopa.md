1. w systemie [[Windows]]
	1. [[Powershell]]
		1. [[Powershell#^325b18}|uruchom powłokę Powershell]]
		2. wykonaj poniższą komendę
		``` Powershell
		Get-WmiObject -Class Win32_ComputerSystem
		```
		Przykładowy wynik
		```
		PS C:\Users\freee> Get-WmiObject -Class Win32_ComputerSystem
		
		
		Domain              : WORKGROUP
		Manufacturer        : Dell Inc.
		Model               : Latitude 5480
		Name                : DESKTOP-00000
		PrimaryOwnerName    : Dell
		TotalPhysicalMemory : 17056194560
		```

![[Pasted image 20220623234759.png]]
Powiązane: [[Windows]]