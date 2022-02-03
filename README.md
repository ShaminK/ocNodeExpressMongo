# Projet Node/Express et Mongo DB du cours Openclassrooms

Réalisation du projet en suivant le cours "Passez au Full Stack avec Node.js, Express et MongoDB" d'Openclassrooms

Lien vers le cours :point_right: https://openclassrooms.com/fr/courses/6390246-passez-au-full-stack-avec-node-js-express-et-mongodb

# Installation du projet

:one: Création d'un répertoire et le nommer "go-fullstack" par exemple puis création d'un sous-répertoire "frontend"

:two: Cloner la partie frontend (réalisée par openclassrooms) dans le répertoire "frontend" via la commande :point_down: :point_down: :point_down:
      
    git clone https:<span></span>//github.com/OpenClassrooms-Student-Center/go-fullstack-v3-fr.git frontend

:three: Lancement du serveur frontend via la commande :point_down: :point_down: :point_down:

    cd frontend
    npm install
    npm run start
    
:four: Création d'un sous-répertoire backend et téléchargement du dépôt

:five: Configuration de la base de données :

Accédez au site web de MongoDB et inscrivez-vous pour obtenir un compte gratuit. Une fois que vous avez accès à votre tableau de bord, créez un cluster puis configurez-le avec l'option AWS et uniquement les options gratuites afin de pouvoir développer gratuitement.

Pendant le démarrage de votre cluster, vous pouvez accéder à l'onglet Database Access. D'abord, vous devrez ajouter un utilisateur disposant de la capacité de lecture et d'écriture dans n'importe quelle base de données. Choisissez le nom d'utilisateur ainsi que le mot de passe de votre choix et notez-les, car vous en aurez besoin pour connecter votre API à votre cluster.

:six: Connexion avec la base de données

Dans le fichier app.js à la ligne 9, modifiez le l'adresse SVR par la vôtre et votre mot de passe utilisateur MongoDB

:seven: Lancement du serveur backend via la commande :point_down: :point_down: :point_down:

    cd backend
    nodemon server
    
L'application est prête à l'emploi :ok_hand:	:ok_hand:	
