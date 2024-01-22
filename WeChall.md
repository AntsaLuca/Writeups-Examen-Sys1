# Writeups-Examen-Sys1
WeChall code

# Tutoriel pour obtenir les mots de passe de WeChall niveaux 0-5

Aujourd’hui je vais vous présenter les démarches pour obtenir les mots de passe de WeChall niveaux 0-5.

1. **Enregistrement sur WeChall :**
   - Tout d'abord, il faut s'enregistrer sur [WeChall](https://www.wechall.net/).
   - Ensuite, entrez le mot de passe WeChall et retapez-le en bas.

2. **Connexion via SSH :**
   - Après l'enregistrement, notez l'adresse IP fournie par WeChall pour se connecter via SSH dans Putty.
     Exemple : `ssh -p 19192 rakoto@warchall.net`
   - Utilisez Putty pour vous connecter.
     Exemple : 
     ```
     Login: Rakoto
     rakoto@192.168.178.128's password: rakoto
     ```

3. **Commandes utiles dans les niveaux :**
   Avant de résoudre les niveaux de WeChall, voici quelques commandes à retenir :
   - `cd`: signifie « changer de répertoire ».
   - `pwd`: affiche le répertoire actuel.
   - `ls`: affiche le contenu d'un répertoire.
   - `ls –al`: affiche les fichiers cachés.
   - `cat`: sert à lire un fichier.
   - `chmod`: signifie commande de changement de mode.
     Exemple : `chmod +r` signifie lecture et modification des autorisations de fichier en lecture.

Maintenant, vous pouvez utiliser ces étapes pour résoudre les niveaux de WeChall.

## Niveau 0
- Utilisez `pwd` pour voir le répertoire actuel.
- `cd /home/level`
- `ls`
- `cd 00_*`
- `ls`
- `cat`
  
Mot de passe : "bitwarrior"

## Niveau 1
- Utilisez `cd` pour changer de répertoire.
- `cd blue ; hats ; grey ; solution ; patience`
- `cat`

Mot de passe : "patience"

## Niveau 2
- `cd documents`
- `ls`
- `cat`

Mot de passe : "level02"

## Niveau 3
- Utilisez `ls –al` pour voir les dossiers et fichiers cachés.
- `cd .bash_history`

Mot de passe : "RepeatingHistory"

## Niveau 4
- Revenez dans le dossier de départ.
- `ls`
- `cd level`
- `cd 04_*`
- `ls`
- `chmod +r` : pour modifier les autorisations du fichier en lecture pour l'utilisateur.
- `cat README2.md`

Mot de passe : "AndOfCourseIDoKnowChown"

## Niveau 5
- `cd /home/level 05_*`
- `ls`
- `cat README.md`

Mot de passe : "OKPRIVATE"

