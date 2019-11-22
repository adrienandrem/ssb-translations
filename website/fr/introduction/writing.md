# Rédaction

Vous pouvez rédiger de nouveaux billets en haut de la page Public, celle de d'un canal ou commenter le billet de quelqu'un d'autre.



Le billet sont rédigés en synthaxe [Markdown](https://commonmark.org/help). La plupart des applications Scuttlebutt formaterot et afficheront vos rédactions d'après les styles Markdown.
Par exemple les titres sont simplement précédés par un `#`.

`# Coucou`

Quand vous avez terminé, cliquez sur "Prévisualiser et publier". Cela permet de vérifier le bon formatage puis d'effectivement publier.



Vous pouver mentionner des personnes à l'aide de "@" et elles seront notifiées sur leur page *Mentions*.


*Remarque !*

Les billets sont permanents! Vous ne pouvez pas les éditer ni les supprimer. Ce n'est pas une décision idéologique, mais un défi technique que nous travaillons à résoudre.

Utilisez votre correcteur d'orthographe, regardez bien la prévisualisationet ne publiez pas sous l'énervement. Vous ne pourrez pas annuler.

Scuttlebutt fonctionne hors-ligne comme les clients courriels Outlook et Thunderbird. Vous pouvez rédiger des billets et commentaires hors-ligne et ils se synchroniseront plus tard lorsque vous vous reconnecterez.
Pourquoi ne pas prendre votre ordinateur dehors et écrire à vos amis sous un arbre ?

Attendez-vous à une communication au même rythme que le courriel - les personnes peuvent répondre rapidement, et parfois c'est comme tennir une correspondance et attendre que le courrier arrive.


### Pour commencer

Une fois dans Patchwork, consultez les canaux suivants en entrant leur nom (avec #) dans la barre de recherche :

* #new-people : présentez-vous
* #faq : premières impressions, qu'est-ce qui déroute le nouvel arrivant ?
* #patchwork : signaler un dysfonctionnement, suggestions, etc
* #scuttlebutt : discussions techniques

Vous présenter sur #new-people est une bonne façon de rencontrer des personnes que vous aimeriez suivre ou qui pourraient avoir envie de vous suivre.
Sans cela, bien que les personnes puissent lire vos billets, il est possible que personne ne remarque votre arrivée, d'autant plus si c'est une période chargée, ce qui résulterait en des débuts solitaires et décourageants.
Nous sommes un groupe amical alors ne soyez pas timide ! Venez et dites-nous qui vous êtes sur #new-people que nous vous aidions à trouver d'autres personnes que vous voudriez mieux connaître.


## Liens vers du contenu

### Profils et canaux

La forme la plus simple d'un lien est une référence à une personne ou un canal. Commencez par taper `@` et le nom de la personne et Patchwork vous aidera avec des suggestions au fil de la saisie.
Validez le choix avec la touche entrée. C'est la même chose pour les canaux. Mais commencez par taper `#` puis le nom.

Vous pouver saisir le nom de plusieurs canaux dans votre message, tout comme avec les hashtags de Twitter.


### Le reste

Créer un lien vers une page web externe est simple, entrez juste

`[Texte à afficher](https://ssb.nz)`.

[Texte à afficher](https://ssb.nz)

Comment faire référence à d'autres messages _dans_ Scuttlebutt ?  
Premièrement, vous aurez besion de l'identifiant du message. Clic droit sur un lien vers le message auquel vous voulez faire référence, et choisir "Copy message ID".



Puis créez un lien avec l'identifiant entre les parenthèses. Entre les crochets, vous pouvez écrire la description que vous souhaitez voir apparaître. Ce sera affiché comme le texte d'un lien.

`[Voir mon dernier billet sur les chiens ici](%SNQIRZ8NU9ujOcr9iXJvlJP0qjdv99J/g4/JMuWYjK0=.sha256)`.

[Voir mon dernier billet sur les chiens ici](%SNQIRZ8NU9ujOcr9iXJvlJP0qjdv99J/g4/JMuWYjK0=.sha256)

Les profils sont un peu différents et normalement il n'y a qu'à laisser Patchwork compléter après avoir entré `@`.
Pour le faire manuellement, vous pourrez trouver l'identifiant sur la page de profil, juste sous le nom.
C'est une longue chaîne aléatoire de caractères commençant par un `@`.
