## Podsumowanie
>Menedżer pakietów - zbiór narzędzi programowych, które automatyzują proces instalowania, aktualizowania, konfigurowania i usuwania programów komputerowych z komputera w spójny sposób.
# Przykłady
| Nazwa                                | Użycie                                                          |
| ------------------------------------ | --------------------------------------------------------------- |
| [[APT (Advanced Packaging Tool)]]                              | [[system uniksopodobny\|systemy uniksopodobne]], np. [[Ubuntu]], zazwyczaj pakiety [[deb]] |
| [[Windows Package Manager (winget)]] | [[Windows 10]], [[Windows 11]]                                  |
| [[DNF (Dandified YUM)]]              |  [[Linux]], pakiety [[rpm]]                                                               |

## Przykłady komend
- "pakiet" - nazwa pakietu dla którego chcemy użyć komendy.
- "plik" - nazwa/ścieżka pliku dla którego chcemy użyć komendy.
- "wzor" - wzór, który chcemy użyć w komendzie.
- "repo" - lokalizacja repozytorium, które chcemy użyć w komendzie.
| Czynność                              | apt                        | dnf                                    | winget               |
| ------------------------------------- | -------------------------- | -------------------------------------- | -------------------- |
| Aktualizacja listy pakietów           | apt update                 | dnf check-update                       | winget upgrade       |
| Aktualizacja zainstalowanych pakietów | apt upgrade                | dnf update                             | winget upgrade --all |
| Instalacja z repozytorium             | apt install pakiet         | dnf install pakiet                     | winget install pakiet       |
| Aktualizuj pakiet                     | apt install pakiet         | dnf erase pakiet                       |                      |
| Usuń pakiet                           | apt remove pakiet          | dnf erase pakiet                       |                      |
| Instalacja pakietu z pliku            | apt install plik           | dnf localinstall plik                  |                      |
| Wyszukaj pakiet po nazwie             | apt search pakiet          | dnf list pakiet                        |                      |
| Wyszukaj pakiet po wzorcu             | apt search wzor            | dnf search wzor                        |                      |
| Wyszukaj pakiet po nazwie pliku       | apt search plik            | dnf provides file                      |                      |
| Lista zainstalowanych pakietów        | apt list --installed       | dnf list installed                     |                      |
| Informacje o pakiecie                 | apt show pakiet            | dnf info pakiet                        |                      |
| Lista repozytoriów                    | cat /etc/apt.sources.list  | dnf repolist                           |                      |
| Dodaj repozytorium                    | edit /etc/apt/sources.list | dnf config-manager -add-repo repo      |                      |
| Usuń repozytorium                     | edit /etc/apt/sources.list | dnf config-manager --set-disabled repo |                      |

---
Powiązane: [[IT]], [[Linux]], [[Windows]]