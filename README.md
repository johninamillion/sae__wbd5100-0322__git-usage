# Git Usage

* [Basic Commands](#basic-commands)
  * [Repositories](#git-repositories)
    * [Git Init](#git-init)
    * [Git Clone](#git-clone)
  * [Branches](#branches)

## Basic Commands

### Git Repositories

#### Git Init
`git init` wird verwendet um ein git repository (local) zu erstellen.

```shell
$ git init your-repository
```

#### Git Clone
`git clone` wird verwendet um ein vorhandenes git repository (remote) zu klonen.

```shell
$ git clone https://github.com/johninamillion/sae__wbd5100-0322__git-usage.git
```

#### Git Add
`git add` fügen wir eine Datei für unsere nächste git operation hinzu.

```shell
$ git add /src/*
$ git add /templates/register/index.php
$ git README.md
```

#### Git Commit
`git commit` nutzen zum Erstellen von einem Commit, es ist notwendig vorher die Dateien die wir commiten möchten per `git add` hinzuzufügen.

```shell
$ git commit -m "Commit Message, was habe ich hier gemacht?"
```

#### Git Push
`git push` nutzen wir um bestehende commits (local) ins git repository zu pushen.

```shell
$ git push
```

#### Git Pull
`git pull` nutzen wir um bestehende commits (remote) aus dem git repository zu pullen

```shell
$ git pull
```

### Branches

Listet alle Branches auf
```shell
$ git branch
```

Erstellen von einem neuen Branch
```shell
$ git branch --create new-branch
```

Löschen von einem alten Branch
```shell
$ git branch --delete old-branch
```

Wechseln zu einem neuen Branch
```shell
$ git checkout new-branch
```

Commits mit einem neuen Branch (local) pushen
```shell
$ git push --set-upstream origin new-branch
```
