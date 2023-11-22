# s.e-epi

**1. Lister les caractéristiques d'un fichier existant**

Pour lister les caractéristiques d'un fichier existant, nous utilisons la commande `ls` avec l'option `-l`.

```
ls -l fichier_existant
```

Par exemple, si nous avons un fichier nommé `mon_fichier` dans notre répertoire courant, nous pouvons utiliser la commande suivante :

```
ls -l mon_fichier
```

Cette commande affichera les informations suivantes sur le fichier :

```
-rw-r--r-- 1 utilisateur groupe 0 2023-11-22 10:00 mon_fichier
```

**2. Lister les caractéristiques d'un fichier inexistant**

Si nous essayons de lister les caractéristiques d'un fichier inexistant, nous obtiendrons une erreur.

```
ls -l fichier_inexistant
```

Cette commande générera l'erreur suivante :

```
ls: fichier_inexistant: No such file or directory
```

**3. Sauvegarder les résultats dans des fichiers**

Pour sauvegarder les résultats de la commande `ls` dans des fichiers, nous pouvons utiliser la redirection de sortie.

```
ls -l fichier_existant > out-normal
```

Cette commande redirige la sortie de la commande `ls` vers le fichier `out-normal`.

Nous pouvons également utiliser la redirection de sortie pour sauvegarder les erreurs dans un fichier.

```
ls -l fichier_inexistant 2> out-err
```

Cette commande redirige la sortie d'erreur de la commande `ls` vers le fichier `out-err`.

**4. Ajouter les résultats dans un fichier existant**

Pour ajouter les résultats de la commande `ls` à un fichier existant, nous pouvons utiliser la redirection de sortie avec l'option `>>`.

```
ls -l fichier_existant >> out-normal
```

Cette commande ajoute les résultats de la commande `ls` à la fin du fichier `out-normal`.

**5. Lister deux fichiers dans un même fichier**

Pour lister deux fichiers dans un même fichier, nous pouvons utiliser la commande `tee`.

```
ls -l fichier_existant fichier_inexistant | tee out
```

Cette commande utilise la commande `ls` pour lister les caractéristiques des deux fichiers, puis la commande `tee` pour rediriger la sortie de `ls` vers le fichier `out`.

**6. Rediriger la sortie vers un périphérique**

En plus des fichiers, nous pouvons également rediriger la sortie d'une commande vers un périphérique.

Par exemple, pour rediriger la sortie de la commande `ls` vers le périphérique `/dev/null`, nous pouvons utiliser la commande suivante :

```
ls -l fichier_existant > /dev/null
```

Cette commande supprimera la sortie de la commande `ls`.

**7. Exécuter des commandes dans plusieurs fenêtres**

Pour exécuter des commandes dans plusieurs fenêtres, nous devons ouvrir deux fenêtres ou deux sessions.

Dans la première fenêtre, nous pouvons exécuter les commandes que nous voulons afficher dans la seconde fenêtre.

Dans la seconde fenêtre, nous pouvons utiliser la commande `tail` pour afficher la sortie de la première fenêtre.

Par exemple, si nous voulons afficher la sortie de la commande `ls` dans la seconde fenêtre, nous pouvons utiliser la commande suivante dans la première fenêtre :

```
ls -l
```

Dans la seconde fenêtre, nous pouvons utiliser la commande suivante pour afficher la sortie de la première fenêtre :

```
tail -f
```

Cette commande affichera la sortie de la première fenêtre en continu.

**8. Exécuter des commandes dans plusieurs sessions**

Pour exécuter des commandes dans plusieurs sessions, nous devons ouvrir deux sessions.

Dans la première session, nous pouvons exécuter les commandes que nous voulons afficher dans la seconde session.

Dans la seconde session, nous pouvons utiliser la commande `ssh` pour nous connecter à la première session.

Par exemple, si nous voulons afficher la sortie de la commande `ls` dans la seconde session, nous pouvons utiliser la commande suivante dans la première session :

```
ls -l
```

Dans la seconde session, nous pouvons utiliser la commande suivante pour nous connecter à la première session :

```
ssh utilisateur@localhost
```

Une fois connectés à la première session, nous pouvons utiliser la commande `tail` pour afficher la sortie de la commande `ls`.
