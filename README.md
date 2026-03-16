# Zadanie-rekrutacyjne-solvro
Zadanie rekrutacyjne do kn solvro

## Jak to odpalić?

1. Sklonuj to repo do siebie.

2. Utworz .venv:
   ```bash
   python3 -m venv .venv
   ```

3. Aktywuj .venv:

    *A) macOS*
       ```
       source .venv/bin/activate
       ```
    *B) Windows*
       ```
       .venv\Scripts\activate
       ```

4. Zainstaluj biblioteki z `requirements.txt`. W terminalu wpisz:
   ```bash
   pip install -r requirements.txt
   ```

5. Cały główny kod jest w folderze `notebooks`. Odpal tam Jupyter Notebooka albo otwórz plik w VSCode i po prostu klikaj "Run All" od góry do dołu.

Jakby wywalało jakieś błędy z plikami, to upewnij się, że masz dataset w folderze `data`. A wytrenowane modele zapisują się w `models`.