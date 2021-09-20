# Test

## Exercice 2

## 1 Identifier le role de la commande which

```bash
man which
```

## 2 Quitter le manuel

```bash
q
```

## 3 Afficher la première page d'une section

```bash
man 6 intro // Description des jeux et de différents programmes amusants
```

## 4 Aller dans le dossiser /var/log

```bash
cd /var/log
```

## Remonter dans le dossier parent (/var) en utilisant un chemin relatif

```bash
cd ../
```

## Retourner dans le dossier personnel

```bash
cd
```

## Revenier au dossier précédent sans utiliser de chemin

```bash
cd -
```

## Accès au dossier root

```bash
cd root // Permission refusée
```

## Accès au dossier root avec sudo

```bash
cd sudo /root // La commande SUDO est un droit administrateur sous linux, on peut donc ouvrir le dossier root
```

## Création de l'arborescence

```bash
cd
mkdir Dossier1 && mkdir Dossier2
cd /Dossier1
touch fichier1
cd /Dossier2
mkdir Dossier2.1 && mkdir Dossier2.2
cd /Dossier2.2
touch fichier2 && touch fichier3
```

## Supprimer Fichier1 puis Dossier1

```bash
cd /Dossier1
rm Fichier1 // Suppression réussi

rm Dossier1 // Erreur, impossible à supprimer avec cette commande

rm -r Dossier2 // Permet de supprimer le dossier
```

## Afficher l'heure

```bash
date
```
