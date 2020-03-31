# SNTMDP
# SNT activité en ligne 1

Objectif : faire un générateur de mot de passe "fort". 

vous avez accès à un exemple de programme ici : [lien](https://repl.it/@jpeaud/generateurmdp) 

```python
print("Mon générateur de mots de passe")
import random
lettres="abcdefghijklmnopqrstuvwxyz01234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ!@#$%^&*()?"
longueur=8
mdp="".join(random.sample(lettres,longueur))
print("le mot de passe est: " + mdp)
```

Pour choisir au hasard nous utiliserons la bibliothèque **random** qui permet de tirer au sort ce que l'on veut. 

Dans la variable **lettres**, on stocke les caractères que l'on autorise pour le mot de passe

Dans la variable **longueur** on stocke la longueur du mot de passe. 

Dans la variable **mdp** on stocke le mot de passe généré. /!\ on signale à l'ordinateur que la variable est vide avec les " ". 

la commande suivante permet de joindre au hasard le nombre de caractères contenus dans **lettres** dans la limite de la valeur marquée dans **longueur**

```python
mdp="".join(random.sample(lettres,longueur))
```

la commande **print** permet d'afficher le résultat.

<details>  <summary>Cliquer pour voir le script en action</summary>   <img src="https://github.com/Svt-lim/SNTMDP/blob/master/20200329_160135.gif" alt="" /></details>

------

## Consigne

Donnez le choix de la longueur du mot de passe à utilisateur 

<details>  <summary>une piste</summary>   
il faut utiliser la commande int(input()) comme dans l'exemple suivant : x=int(input("entrez un nombre :" ))
</details>

## Defi 

Donnez le choix de la longueur du mot de passe à utilisateur et lui donner le choix entre un mot de passe fait uniquement de chiffres, uniquement des lettres de l'alphabet ou le mode par défaut (=tout)

<details>  <summary>une piste</summary>   
il faut utiliser une boucle if/else
</details>

------

## Retours

le site repl.it est design responsive, la programmation est donc possible sur ordinateur/tablette et smartphone même si cela n'est pas forcement très confortable. 

Il vous est tout à fait possible de me communiquer votre script à l'écrit par mail ou Pronote/ENT 
