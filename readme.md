#Boilerplate HTML

Boilerplate minimaliste avec une grille CSS simple.

### Pré-requis (optionnel)

* Installer NodeJS (et NPM de facto) : https://nodejs.org/en/download/package-manager/
* Mettre à jour NPM : https://docs.npmjs.com/getting-started/installing-node

### Installation (optionnel)

*``npm install`` à lancer dans le répertoire racine pour installer un serveur HTTP simple ainsi que BrowserSync.

### Commandes (optionnel)

* ``npm run live`` à lancer dans le répertoire racine pour exécuter BrowserSync et le serveur HTTP (port 8080 par défaut). Tous les changements sur le fichier *index.html* ainsi que sur les fichiers *.css* dans ce répertoire seront directement appliqués et rafraîchis dans le navigateur.

* ``npm run serve`` pour lancer uniquement le serveur HTTP sur le port *8080*.

### Utilisation

* Explorer le fichier *boilerplate.css* ainsi que le fichier *index.html* pour facilement démarrer votre projet. Par défaut, la mise en page est constituée d'une balise *header*, d'une balise *main* qui représente le coeur de page, et d'un *footer*. Le modèle *flexbox* est utilisé pour positionner le *footer* ainsi que pour centrer verticalement et horizontalement les éléments grâce aux classes "v-centering" et "h-centering", entre autres.