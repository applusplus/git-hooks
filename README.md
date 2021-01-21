## Globale Git-Hooks Installation

#### Requirements
[git](https://git-scm.com/) Version 2.9 or later

#### Installation under Windows
1. Clone the git-hooks repository.
2. Open cmd and navigate to repository's directory.
3. Register hooksPath globally.
    ```bash
    git config --global core.hooksPath %cd%
    ```
5. Done. Git should now use files from your local git-hooks repository as hooks, as long files name match.