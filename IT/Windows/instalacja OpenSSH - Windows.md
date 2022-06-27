1. [[PowerShell#^fb7174|Uruchom powłokę Powershell jako administrator]]
2. Sprawdź czy OpenSSH jest dostępne
   ```Powershell
	Get-WindowsCapability -Online | Where-Object Name -like 'OpenSSH*'
	```
	![[Pasted image 20220627120931.png]]
1. Zainstaluj klienta [[OpenSSH]] jeśli nie jest obecny
	```Powershell
	Add-WindowsCapability -Online -Name OpenSSH.Client~~~~0.0.1.0
	```


4. Zainstaluj serwer [[OpenSSH]] jeśli nie jest obecny
   ```Powershell
	Add-WindowsCapability -Online -Name OpenSSH.Server~~~~0.0.1.0
	```

