# Go web server

Ce projet consiste en un serveur HTTP simple écrit en Go, capable de servir des fichiers statiques, de gérer un formulaire POST et de répondre à une requête "hello" sur le chemin "/hello".

## Installation

1. Assurez-vous d'avoir Go installé sur votre système. Si ce n'est pas le cas, suivez les instructions sur https://golang.org/doc/install.

2. Clonez ce dépôt :
   ```bash
   git clone https://github.com/dofbi/go-web-server.git
   ```

3. Accédez au répertoire du projet :
   ```bash
   cd go-web-server
   ```

4. Exécutez le programme :
   ```bash
   go run main.go
   ```

## Utilisation

Une fois le serveur démarré, vous pouvez accéder à différents chemins :

- `/` : Affiche les fichiers statiques du répertoire `./static`.
- `/form` : Traite un formulaire POST avec les champs `name` et `adresse`, puis affiche les valeurs saisies.
- `/hello` : Affiche simplement "hello!".

## Structure du Code

- `main.go` : Contient le code principal du serveur.
- `static/` : Répertoire contenant les fichiers statiques à servir.

## Auteur

Ce projet a été développé par [@dofbi](https://github.com/dofbi).

## Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.

---

Assure-toi de personnaliser les liens et les informations selon ton propre dépôt et tes préférences.