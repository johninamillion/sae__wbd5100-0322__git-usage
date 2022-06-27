# Git Usage

## Basic Commands

#### Git Clone

`git clone` wird verwendet um ein vorhandenes git repository zu klonen.

```shell
$ git clone https://github.com/johninamillion/sae__wbd5100-0322__git-usage.git
```

`git add` fügen wir eine Datei für unsere nächste git operation hinzu.

```shell
git add /src/*
git add /templates/register/index.php
git README.md
```

`git commit` nutzen zum Erstellen von einem Commit, es ist notwendig vorher die Dateien die wir commiten möchten per `git add` hinzuzufügen.

```shell
git commit -m "Commit Message, was habe ich hier gemacht?"
```