## [[menedżer pakietów]] [[dnf]]
1. Sprawdź aktualizacje dla wszystkich włączonych repozytoriów
   ```shell
   sudo dnf check-update
   ```
   ![[Pasted image 20220627083330.png]]
2. Zaktualizuj wszystkie pakiety
   ```shell
   sudo dnf upgrade --refresh
	```
3. Zainstaluj [[Python]] 3 przy użyciu [[menedżer pakietów|menedżera pakietów]] [[dnf]] używając poniższej komendy
	```shell
	   sudo dnf install python3
	```
