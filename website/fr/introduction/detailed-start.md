![bernard-l'ermite dansant](https://github.com/ssbc/handbook.scuttlebutt.nz/blob/master/assets/garden/large-hermies-dancing.gif)

Ok, vous avez entendu parler de [Scuttlebutt](https://scuttlebutt.nz/) et décidé que
"Oui, je veux rejoindre cet extraordinaire réseau social oû se trouvent plein de gens bien, qu'aucune entreprise ne peut contrôler
et qui fonctionne aussi hors-ligne"

Voici un rapide aperçu des bases que vous devez savoir.

Remarque : Si vous n'avez pas le temps et voulez commencer dès maintenant, voici le [guide de démarrage rapide](https://scuttlebutt.nz/docs/introduction/quick-start) de l'introduction.

Tout d'abord, Scuttlebutt est un protocole que peuvent utiliser des applications très différentes.

Comme pour les réseaux sociaux, il y a beaucoup d'applications clientes, comme les différents clients Twitter.
Lequel vous utilisez n'a pas vraiment d'importance. Ils parlent tous sur le même réseau.

Patchwork est le client le plus abouti, qui ne demande aucune connaissance technique.
La seule particularité est qu'il s'exécute uniquement sur un ordinateur,
et votre identité est attachée aux fichiers de l'ordinateur sur lequel vous l'avez installé.
Des contournements existent, mais ce n'est pas l'objet de ce document.

![Capture d'écran de Patchwork](https://github.com/ssbc/handbook.scuttlebutt.nz/blob/master/assets/screenshots/patchwork.jpg)


## Étape 0 : Qu'est-ce que Scuttlebutt ?

Si vous ne l'avez pas déjà fait, allez voir la vidéo d'[histoire d'amour Scuttlebutt](https://scuttlebutt.nz/docs/introduction), puis revenez.


## Étape 1 : Installez Patchwork

[Téléchargez Patchwork](http://dinosaur.is/patchwork-downloader), et installez-là comme toute autre application.


## Étape 2 : Créez votre profil

Lancez Patchwork et créez votre profil.

![Patchwork : nouveau profil](https://github.com/ssbc/handbook.scuttlebutt.nz/blob/master/assets/screenshots/patchwork-first-boot.png)

Choisissez un nom. Les noms dans Scuttlebutt ne sont pas uniques, comme dans la vraie vie -- on peut s'appeler "Fred" même s'il y a d'autres personnes déjà nommées "Fred".

Choisir une image n'est pas obligatoire, mais est recommandé, car avec une illustration il est plus aisé de comprendre qui s'exprime, car les images par défaut sont très basiques.
Des personnes utilisent une photo d'elle-même, d'autres choisissent une illustration qu'elles aiment, tout comme sur Twitter.

Vous pourrez modidier tout ça par la suite (nom, photo, description). **Il est possible de retrouver vos anciens noms**, photos et descriptions,
donc considérez les implications sur la vie privée du contenu que vous renseignez.
Vous voudrez peut-être commencer avec une personalisation temporaire que vous changerez une fois familier avec Scuttlebutt.

La synthaxe [Markdown](http://commonmark.org/help) est utilisée pour la description.

Enregistrez quand vous avez terminé.


## Étape 3 : Connexion aux personnes et aux pubs.

Créer des connexions sociales ainsi qu'à des réseaux.

Scuttlebutt est original, il vaut la peine de comprendre comment il fonctionne :

Les connexions sociales (suivre quelqu'un) montre que vous êtes intéressé pour lire ses publications.
C'est le même concept que sur Twitter, votre ordinateur utilise vos connexions sociales pour savoir quelles données consulter lors de la synchronisation.

Les connexions de réseau ont lieu lorsque deux ordinateurs entrent en contact et tentent d'échanger des données.
Votre application scuttlebutt tentera de se connecter avec *tout autre ordinateur Scuttlebutt qu'elle trouvera* au cas où il ait de l'information des personnes auxquelles vous vous intéressez.

L'ordinateur de chacun se comporte donc comme un facteur transportant le courrier
et le distribuant aux autres ordinateurs environnant qui sont intéressés,
on appelle ce processus le "commérage" (_gossip_ en anglais).

Scuttlebutt télécharge directement tout ce qu'il peut, pour fonctionner lorsque vous êtes hors-ligne.
Sur cet aspect, c'est un peu comme un client courriel comme Outlook ou Thunderbird.


### À propos des connexions et du flux des messages

Votre application Scuttlebutt est intéressée par les personnes que vous suivez, et par celles qu'**elles** suivent (2ème cercle).
Elle ne montrera pas les plus éloignées dans la plupart des pages, mais tentera de télécharger leurs messages au cas où vous voudriez les consulter.

Si vous ne suivez personne, votre ordinateur ne demandera aucun message et vous n'aurez rien à lire.
Si personne ne vous suit, vos messages n'iront pas loin dans le réseau.

La prochaine étape est donc de suivre et d'être suivi.


### Connexion à une personne, localement

Si vous êtes dans la même pièce qu'une autre personne, sur le même réseau WiFi ou filaire, vos ordinateurs vont entrer en contact.
Vous verrez la personne dans la liste de gauche, section "Local".

Cliquez sur son profil pour en voir plus à propos d'elle,
et cliquez sur "Suivre" si vous désirez suivre ce que cette personne publie et aider à diffuser ce contenu.

Vos ordinateurs vont échanger même si vous ne vous suivez pas l'un l'autre,
car vous pourriez avoir du _commérage_ à échanger concernant un ami mutuel.


### Des pubs pour se connecter à distance

Le "Pub" est un ami virtuel pour vous aider à débuter.
Considérez-le comme un barman d'un pub du quartier qui connaît beaucoup de monde et propage les _commérages_.

Ils fonctionnent de la même manière que les autres personnes du réseau, sauf qu'ils peuvent vous suivre si vous les "rejoignez" grâce à un code d'invitation.

Ils existent pour deux raisons :
* Pour créer plus de connexions sociales, comme un de vos amis qui connaît tout le monde en ville, faisant que le _commérage_ se répande d'avantage et que vous rencontriez de nouvelles personnes
* Pour faciliter les connexions de réseau, comme ils sont tout le temps en ligne et joignables depuis n'importe où sur internet.
  
Vous n'avez pas besoin des pubs si vous et vos amis transportez vos ordinateurs et vous synchronisez en personne de temps en temps.
Mais si vous voulez trouver de nouvelles personnes ou des personnes éloignées, vous devriez rejoindre un ou deux pubs.


### C'est l'heure de rejoindre des pubs

"Rejoindre" un pub vous fait vous suivre mutuellement.

Choisissez un pub dans [la liste des serveurs pub](https://github.com/ssbc/ssb-server/wiki/Pub-Servers).

Pour l'un des pubs, cliquez sur le bouton "Obtenir une invitation" et un code d'invitation sera généré pour vous.
Cela ressemble à une longue chaîne aléatoire de lettres et chiffres. Copiez-le.
Puis cliquez sur le bouton "+ Join Pub" dans Patchwork, en haut à gauche,
et collez le code dans le champ de saisie.

![Bouton Rejoindre le pub](assets/screenshots/patchwork-join-pub-button.png)

Au cas où l'un des pubs cesse de fonctionner ou que le code ne soit plus valable,
il est préférable d'en rejoindre quelques-un.

Si vous avez déjà un ami sur Scuttlebutt, essayez de rejoindre un pub en commun pour pouvoir vous voir. (Demandez-lui sur quel pub il est).


## Étape 4 : Obtenir tout le commérage

**La première fois que vous rejoindrez le réseau, il y aura beaucoup de téléchargement et de traitement**.
Attendez-vous à ce que cette "synchronisation" prenne une heure et plusieurs gigaoctets. C'est tout à fait normal,
et certainement pas ce à quoi nous sommes habitués.

C'est l'occasion d'aller prendre un thé ou d'aller revoir l'[histoire d'amour Scuttlebutt](https://scuttlebutt.nz/docs/introduction).
Notez simplement que nous utilisons le web d'une façon complètement différente.

![Initial Sync Island](assets/initial-sync-island.png)

Patchwork télécharge l'historique entier de toutes les personnes auxquelles vous vous intéressez.
Une fois que c'est fait, vous pouvez le consulter hors-ligne !

C'est plus rapide si l'ordinateur d'un ami est sur le même réseau WiFi car le contenu sera téléchargé depuis cet orinateur plutôt que depuis internet.

Il y a une barre d'avancement en haut de la fenêtre. Pendant ce temps, il est préférable de laisser l'application de coté
et de ne pas l'utiliser car ce pourrait être lent ou produire un affichage incomplet.
Il n'y a pas de problème à quitter et redémarrer l'application pendant le traitement,
mais laissez plutôt l'application ouverte pour qu'elle finisse ce qu'elle a à faire.

Patchwork a un bug - après la fin de la première longue synchronisation, vous devrez redémarrer l'application pour pouvoir consulter la plupart du contenu.


### D'où viennent tous ces pubs listés à gauche dans Patchwork ? Je ne les ai pas rejoint !

Dans la barre gauche sont listés les "pubs connectés". Ce sont des connexions de réseau, pas des connexions sociales

Votre ordinateur se connecte à tous les ordinateurs qu'il peut trouver au cas où il y ait du commérage pertinent à partager.
Vous n'avez pas vraiment "rejoint" ces pubs, votre ordinateur cherche partout des nouvelles de vos amis.

Les pubs que vous avez "rejoint" sont affichés sur votre page de profil, parmi les personnes que vous suivez.


## Étape 5 : Socialisez !

La page *"Public"* montre les billets que vos amis ont écrit ou commenté.

La page *"Private"* vous permet d'écrire des messages privés jusqu'à 7 personnes à la fois.

Les *"Cannaux"* sont vraiment plus comme des hashtags sur Twitter. La liste des canaux actifs montre les canaux dernièremnt utilisés, vous en trouverez plus dans le menu "Plus".
Les canaux sont utiles pour organiser les sujets de conversation, et pour trouver des personnes à suivre.

![browse all button](assets/screenshots/patchwork-browse-all.png)

Il y a un champ de recherche en haut à droite. Commencez par *"@"* pour chercher des personnes, *"#"* pour trouvel un canal, ou simplement entrez les mots que vous voulez trouver.

Nous avons une tradition, les nouveaux arrivants doivent se présenter dans le canal #new-people.
Le plus facile pour s'y rendre est de chercher *"#new-people"*.


### Partage de contenu Scuttlebutt vers l'extérieur

Il y avait un système pour mettre du contenu Scuttlebutt sur le web classique mais il est désormais fermé.
Si vous voulez essayer, faites un clic droit sur un billet, puis "Copier le lien externe".

Le visionneur public est mis en ligne par la générosité d'un [membre de la communauté](https://github.com/clehner), pas une énorme entreprise avec des armoires de serveurs de sauvegarde. ;)

Seulement les utilisateurs ayant explicitement activé le visionneur public y apparaîtront.
Pour les détails, consultez la [page sur la vie privée](../faq/misc/privacy.md).


## Soyez heureux et en sécurité

Si quelqu'un vous ennuie ou dit des choses que vous ne voulez pas entendre, vous pouvez le bloquer ou l'ignorer, depuis sa page de profil (par le bouton Options).
Cela cachera ses messages et commentaires.

Vous pouvez bruyament *bloquer* quelqu'un, ou silencieusement *ignorer*.

Un blocage est public et tout le monde peut le voir. Le blocage est une façon de mettre en avant les normes de la communauté et avertir vos amis d'une personne qu'ils pourraient vouloir bloquer.
Parfois cela génère des conversations utiles.

Ignorer silencieusement est une action secrète dont vous seul(e) avez connaissance. Cela vous cache la personne.

Nous voulons que Scuttlebutt soit un espace sûr et confortable mais il reste des choses à régler :

* les personnes bloquées peuvent voir vos messages publics
* les publications des personnes bloquées restent sur votre ordinateur (C'est presque réglé !)
* Patchwork a un bogue qui fait apparaitre des publications de personnes bloquées dans certaines situations, alors qu'elles devraient être cachées
* Scuttlebutt ne fournit pas lui-même l'anonymisation d'adresse IP, mais vous pouvez l'utilisez à travers un VPN ou Tor
* pour l'instant, les messages ne peuvent être supprimés

Nous savons que ce n'est pas assez sécuritaire pour beaucoup de personnes et nous sommes en train de travailler sur ces problèmes.
