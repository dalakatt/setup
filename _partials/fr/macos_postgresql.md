## PostgreSQL

Dans quelques semaines, on abordera les bases de données et le SQL, et tu auras besoin de [PostgreSQL](https://www.postgresql.org/), un système de gestion de base de données adapté à la production, puissant et open source.

Installons-le maintenant.

Exécute les commandes suivantes :

```bash
brew install postgresql
brew services start postgresql
```

Une fois que c’est fait, on va vérifier que tout a bien fonctionné :

```bash
psql -d postgres
```

Si tu vois apparaître un nouveau message comme celui-ci, c’est bon !

```bash
psql (13.3)
Type "help" for help.

postgres=#
```

Pour quitter PostgreSQL, saisis `\q` puis `ENTRÉE`.
