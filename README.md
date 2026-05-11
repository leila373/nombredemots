# nombredemots 




## Description

Ce projet Java permet de compter le nombre total de mots présents dans un fichier texte.

Le programme :

* lit un fichier texte ligne par ligne
* sépare les mots grâce aux espaces
* compte le nombre de mots de chaque ligne
* additionne tous les mots
* affiche le total final

---

## Fonctionnalités

* Lecture d’un fichier texte avec `Scanner`
* Comptage automatique des mots
* Gestion des lignes vides
* Gestion des erreurs si le fichier est introuvable

---

## Technologies utilisées

* Java
* File
* Scanner
* Exception Handling

---

## Structure du projet

```text id="o67p4h"
WordCounter/
│
├── src/
│   └── Main.java
│
├── texte.txt
│
└── README.md
```

---

## Exemple de fichier texte

```text id="z8m0an"
Bonjour tout le monde
Java est un excellent langage
Ce programme compte les mots
```

---

## Exemple de résultat

```text id="2t4d9z"
Nombre total de mots : 13
```

---

## Compilation et exécution

### Compiler le programme

```bash id="l98x4u"
javac Main.java
```

### Exécuter le programme

```bash id="qt8f1k"
java Main
```

---






