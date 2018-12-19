# geolid-commits-cz
> A [commitizen](https://github.com/commitizen/cz-cli) adapter for Geolid.

#### Demo
```
? Select the type of change that you're committing: (Use arrow keys)
❯  FIX:      correction de bug/typo/etc...
   ADD:      ajout de feature/assets/etc...
   DEL:      suppression de feature/assets/etc...
   CLN:      nettoyage de code
   REF:      refactorisation de code
   TST:      tests unitaire, fonctionnel, etc…
   DOC:      documentation
```

#### Installing the command line tool

First install [commitizen](https://github.com/commitizen/cz-cli)

Then install geolid-commits-cz package (under Geolid/ root)
```
npm init -y
npm i geolid-commits-cz
commitizen init geolid-commits-cz --save-dev --save-exact --force
```

#### Using the command line tool
Now, simply use `git cz` instead of `git commit` when committing.

## Author
Med Mahjbi <m.mahjbi@geolid.com>
