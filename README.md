# Exporter une base Firebase.

**Human:**
comment exporter une base de donner firebase

***

**Assistant:**

Pour exporter une base de données Firebase, vous pouvez utiliser l'outil de ligne de commande "Firebase CLI". Il vous permet de sauvegarder et de restaurer vos données de la base de données Firebase.

Voici les étapes pour exporter une base de données Firebase :
<ol><li>Installez Firebase CLI en utilisant npm (Node Package Manager) en exécutant la commande suivante :</li></ol>
```
npm install -g firebase-tools

```
<ol start="2"><li>Connectez-vous à votre compte Firebase en utilisant la commande :</li></ol>
```
firebase login

```
<ol start="3"><li>Sélectionnez le projet Firebase que vous souhaitez exporter en utilisant la commande :</li></ol>
```
firebase use --add

```
<ol start="4"><li>Exécutez la commande suivante pour exporter les données de la base de données Firebase :</li></ol>
```
firebase database:get / > nom_du_fichier.json

```

Cela vous permettra de sauvegarder les données de la base de données Firebase dans un fichier JSON. Vous pouvez également exporter des données spécifiques en utilisant un chemin de noeud spécifique à la place de "/" dans la commande ci-dessus.


***

Exported on 19 janvier 2023 4:19 PM.
