## Globale Git-Hooks Installation

#### Voraussetzung
[git](https://git-scm.com/) Version 2.9 oder neuerer

#### Installation
1. Das git-hooks Repository clonen.
2. In das Repo-Verzeichnis navigieren.
3. Den aktuellen Ordner global als hooksPath registrieren.
    ```bash
    git config --global core.hooksPath $PWD
    ```  
4. Alle Dateien im Verzeichnis ausführbar machen.
   ```bash
    chmod -R +x ./
    ```
5. Fertig. Die git hooks sind registriert.