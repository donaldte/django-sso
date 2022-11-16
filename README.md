# Django Single Sign On
Dans ce didacticiel Django, je vais vous montrer comment implémenter l'authentification sociale dans Django, ce qui donnera à vos utilisateurs le pouvoir de se connecter ou de s'inscrire avec plusieurs comptes sociaux sans les laisser créer un nouveau compte sur votre site Web. Nous traiterons avec plusieurs fournisseurs comme `Facebook`, `Google` et `GitHub`. L'authentification unique (SSO) est une fonctionnalité très puissante dans les applications Web. En général, il y aura :
. Se connecter avec Google / S'inscrire avec Google
. Connectez-vous avec Facebook / Inscrivez-vous avec Facebook
. Connectez-vous avec GitHub / Inscrivez-vous avec GitHub

Nous vous montrerons tout à partir de zéro; enregistrer votre application auprès de fournisseurs tels que Facebook, Google et GitHub ; configurer django dans le cadre de la connexion des fournisseurs sociaux, puis enregistrer l'application dans le panneau d'administration Django. En dehors de cela, nous expliquerons chaque étape à mesure que nous avancerons avec le code. Nous utiliserons l'implémentation OAuth2 pour tous les fournisseurs. Nous verrons des éléments tels que l'ID client, le secret client, le jeton d'accès, le code d'autorisation, le serveur d'autorisation, le serveur de ressources et d'autres éléments connexes.

Nous utiliserons le package `django-allauth`

# Illustration

![Screenshot from 2022-11-16 02-08-56](https://user-images.githubusercontent.com/81464575/202065840-b52a1e2a-0852-4b1b-aca3-180576dfcf8f.png)

# installation

1. clonez le projet

```
git clone
```

2. Entrez dans le projet

```
cd django-sso
```

3. Creez un environement virtuel

```
python3 -m venv venv
```

4. Activer l'enviroment virtuel

Linux

```
source venv/bin/activate
```

Window

```
source  venv\script\activate
```
5. install les requirements

```
pip install -r requirements.txt
```

Abonne toi a ma chaine [Youtube](https://youtube.com/@donaldprogrammeur)

