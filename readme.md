# Verziókezelés

## Helyi repó létrehozása

- inicializálás:
    > git init
- git felhasználó ellenörzése:
    > git config user.name

    > git config user.email

- ellenörzés (mi a külömbség a munka könyvtár és a helyi repo közt ?)
    > git status

- előkészítjük a commit-ra (beindexelődnek), mindent eltárolunk
    > git add .

- ellenörzés
    > git status
- eltárolja az újabb verziónak:
    > git commit -m "first"

## összekapcsolás a távoli repoval(Github)

- új github repo létrehozása
- helyi repo összekapcsolása a távolival
    > git remote add origin https://token@github.com/VDani420/Travel-Agency.git
- első push-nál meg kell mondani a branch nevét:
    > git push -u origin master

- új cucc