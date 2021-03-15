# Serveur Faction Préconfiguré
## Installation du Serveur:
* Pour commencer, il faut installer le serveur sur une machine. Etant partenaire de [MTX-Serv](https://mtxserv.com/fr/hebergeur-serveur-minecraft), et faisant principalement le serveur pour eux, je vous conseille donc de prendre un serveur chez eux et de l'installer en 1 click dans la section "plugin pack" dans le panel du serveur. Si vous choisissez ce chemin, vous pouvez passer à la [prochaine section](https://github.com/ImoriSama/Faction-MTX/blob/main/README.md#configuration-du-serveur)

* Vous pouvez malgré tout télécharger par vous même les fichiers via le bouton ci-dessous:
![Image download](https://github.com/ImoriSama/Images-Explications/blob/main/Screenshot_450.png)

Il faut ensuite De-Zip le dossier (via winrar par exemple).
Le dossier ne contient pas un start.bat afin de lancer le serveur sur votre ordinateur, vous pouvez facilement en trouver un sur internet. Il vous faudra un start.sh qui est trouvable facilement sur internet pour le mettre sur un vps par exemple.

## Caractéristiques du serveur

Le serveur possède plusieurs évenements:
* Un event de parcours
* Un koth à 25 connectés
* Un réaction de chat

Des nouvelles fonctionnalités que vos joueurs aimeront:
* Un coinflip
* McMMO
* Un clear lagg
* Des tags après les pseudos `/tags`
* Un top de Faction `/f top`
* Un shop équilibré `/warp shop`
* Un casseur d'obsidienne, via tnt
* Un unclaim finder (voir craft au spawn)
* Un Hammer (mine 3x3) (voir craft au spawn)
* Un plugin de skin si vous le mettez en crack `/skin set`
* Un vérif autoclicker `/verif`
* Un menu de modération `/mod`
* Un nouveau minerais (par défault le pandarium qui remplace l'or
* Un système de mariage `/mariage`
* un monde minage `/mine`
* Une arêne PvP `/warp pvp`
* Une vendeuse légendaire qui vend la pioche qui permet de casser les spawners (caché dans le spawn)
* Un plugin qui permets de mettre un grade temporairement `/setrank`

## Configuration du Serveur
Pour configurer le serveur, il faut changer quelques fichiers. Ça peut faire peur comme ça, mais vous allez voir, c'est simple !

Allez dans le fichier "plugins > Skript > scripts"

Vous trouverez plien de fichiers en `.sk`, vous pouvez donc les changer à votre guise. Changez tous les "site" ou "Serveur" par le nom de votre serveur.

Voici la liste **OBLIGATOIRE** des `.sk` à changer:
* autres.sk
* bc.sk
* ore.sk

Maintenant, il faut passer à la configuration des plugins

Revenez dans le dossier plugins, vous devrez modifier toutes les mentions `Serveur` par le nom de votre serveur

Il vous faudra changer **OBLIGATOIREMENT** la configuration des plugins suivant:
* AutoBroadcaster (faire attention aux accent, le plugin n'aime pas trop)
* ClearLag
* CustomGUI
* TitleManager

## Fin
Vous avez compris comment marche le serveur, alors amusez-vous bien !
Merci d'avoir suivi ce tuto.

Vous pouvez me contacter sur discord si vous avez des questions Imori-Sama#0612

Vous pouvez aussi me suivre sur mes réseaux sociaux:
* [Twitter](https://twitter.com/Imori_Sama)
* [YouTube](https://www.youtube.com/c/IMORISAMA/)
