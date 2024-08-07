# Configuration générale ⚙️
Bien configuré ses logiciels et ses projets c'est primordiale ! Un logiciel bien configuré c'est un logiciel plus simple et plus à utilisé ! Je vais donc ici vous présentez comment configuré votre logiciel DBM ainsi que votre projet à l'aide de screen.

## Démarrer un nouveau projet 📄
Quand c'est votre première fois sur DBM, il va vous être demandé si vous voulez ouvrir un projet ou créer un nouveau projet, comme vous êtes nouveau vous n'avez pas déjà un projet donc vous allez cliquer sur "créer un nouveau projet"
Ensuite, cette fenêtre va apparaître : 

![Fenêtre de création d'un nouveau projet sur DBM](https://i.imgur.com/FDcfLR8.png)

Donc tout d'abord vous allez choisir le nom de votre projet/bot et sur la ligne d'en dessous vous allez choisir l'emplacement de où va être le dossier avec les fichiers du projet.
Et pour finir je vous conseil de rester sur "**Blank Project**".

### Configuration du nouveau projet ⚙️
Une fois votre nouveau projet crée vous vous retrouverez sur cette page.

![nouveau projet vierge](https://i.imgur.com/l5qbVFb.png)

On retrouve sur cette page une barre d'outils, je vais commencer par `file`, les raccourcis sont marqués en gris à côté des options. Ce menu permet principalement de gérer vos projets et votre projet actuel.

![menu file dans la barre d'outil](https://i.imgur.com/jBBmpY3.png)

<details>
<summary>Liste des options du menu file</summary>

> - **Create New Project** : Sert à crée un nouveau projet.

> - **Open Existing Project** : Perrmet d'ouvrir un projet existant grâce au fichier qui est en extension `.discordbot`.

> - **Open Recent Project** : Permet d'ouvrir un de vos projets récents lorsque vous passez votre souris sur cette option, un autre menu apparaît à droite, il liste tous vos projets récents.

> - **save Current Project** : Permet de sauvegarder votre projet sur lequel vous êtes.

> - **Close Project** : permet de fermer votre projet, quand vous cliquer dessus il vous demande avant si vous voulez **annuler**,**ne pas sauvegarder** ou **sauvegarder** une fois que vous avez choisis sauvergarder ou ne pas sauvegarder vous allez attérir sur ce menu :
>
> ![Menu sans projet d'ouvert](https://i.imgur.com/qi6ydf5.png)

***

> - **Export Project** :   Permet d'exporter votre projet en projet NodeJS avec un fichier en `.zip`.

***

> **Je n'ai jamais utilisé les options de cette catégorie je n'ai donc pas d'informations sur les options suivantes : `Load Current Save`,`Restore Encrypted Backup`,`Restore Unencrypted Backup`.**

***

> - **Update bot.js** : Permet de mettre à jour le fichier `bot.js` dans le dossier de votre bot, ce dossier contient toute la configuration de votre bot.

> - **Actions/Events/Extensions** : Permet de re-vérifier soit les fichiers moddés des dossiers `Actions`,`Events`,`Extensions` ou de re vérifier les fichiers originaux de ces mêmes dossiers.

> - **Music Capabilities** : Permet de soit installer FFMPEG dans votre projet soit de mettre à jour les librairies musicales de votre projet, cela est utile pour ceux qui souhaitent faire des bots de musiques ou avec des fonctions musicales.

</details>

***

Ensuite le menu `Edit`, ce menu sert principalement à l'édition d'actions faites ou à l'édition textuelle.

![Menu Edit dans la barre d'outils](https://i.imgur.com/1xE1czV.png)

<details>
<summary>Liste des options du menu Edit</summary>

> - **Undo** : Comme un `CTRL + Z` sur Windows, il permet de revenir en arrière lors d'une action **⚠️ ATTENTION : Cela ne fonctionne pas sur les "Actions irreversibles" ⚠️**

> - **Redo** : Permet de revenir en avant (après un undo par exemple)

***

> - **Cut** : Comme un `CTRL + x` sur Windows, il permet de couper du texte ou une action.

> - **Copy** : Comme un `CTRL + c` sur Windows, il permet de copier du texte ou une action.

> - **Paste** : Comme un `CTRL + v` sur Windows, il permet de coller du texte ou une action.

> - **Select All** : Comme un `CTRL + a` sur Windows, il permet de sélectionner tout un texte dans une zone de texte.
  
</details>

***

Ensuite le menu `Window`, ce menu sert à géré votre logiciel DBM.

![Menu Window dans la barre d'outils](https://i.imgur.com/Yc5ckZK.png)

> [!CAUTION]
> Attention aux options sur lesquelles vous cliquez dans ce menu, cela peut vous faire **perdres toute modifications non sauvegardées** !

<details>
<summary>Liste des options du menu Window</summary>

> - **Open. Dev. Tools** : Permet d'ouvrir l'outil `inspecter` qu'on retrouve sur les navigateurs.

***

> - **Restart Program** : Permet de relancer votre logiciel. **⚠️ATTENTION, cette option va fermer et reouvrir votre logiciel sans vous demander d'enregistrer et cela ne va pas enregistrer vos modifications, donc toute modifications non sauvegardées seront perdues**.

> - **Minimize to Tray** : Permet de réduire votre logiciel en icône.

***

> - **Minimize** : Permet de réduire votre fenêtre.

> - **Maximize** : Permet de mettre votre fenêtre en grand.

> - **Close** : Permet de fermer votre fenêtre *(Vous demande avant de la fermer si vous voulez enregistrer)*.

***

> - **Reset Dimensions** : Permet de mettre votre fenêtre à sa position initiale.
  
</details> 

***

Ensuite le menu `Zoom`, ce menu sert à géré votre zoom comme sur un navigateur avec `CTRL + molette`.

![Menu Zoom dans la barre d'outils](https://i.imgur.com/HoX75KZ.png)

<details>
<summary>Liste des options du menu Zoom</summary>

> - **Zoom In** : Permet de zoomer sur votre fenêtre.

> - **Zoom Out** : Permet de dézoomer sur votre fenêtre.

> - **Reset Zoom** : Permet de revenir au niveau de zoom de base. 
  
</details>

***

Ensuite le menu `Project`, encore un grand menu qui lui sert à gérer votre projet.

![Menu Project dans la barre d'outils](https://i.imgur.com/yU0fkew.png)

<details>
<summary>Liste des options du menu Project</summary>

> - **Run Project** : Permet de démarrer votre projet/votre bot.

> - **Run Project Independently** : Permet de démarrer votre bot depuis une `cmd` (invite de commande), cela va vous ouvrir une invite de commande et vous marquer "bot ready !" Quand votre bot sera en ligne, cette invite de commande permet aussi de voir les logs de votre bot (nous allons voir plus tard comment les voir même quand on run depuis dbm)

> - **Stop Project** : Permet de stopper votre bot.

***

> - **Module Manager** : Permet de gérer les modules de votre projet.
> ![Module Manager](https://i.imgur.com/UXWysxs.gif)

> - **Reset/Resinstall Default Node Modules** : Permet de ré installer ou de rénisialiser les modules de NodeJS par défaut (Présent dans le dossier `nodes_modules` dans le dossier de votre projet).

> - **Reinstall Node Modules** : Permet de re installer les modules de NodeJS.

***

> - **Open Bot Log** : Permet d'ouvrir les logs de votre bot. Par exemple lorque vous lancer votre bot depuis DBM (`Run Project`) cela permet de voirs les erreurs de votre bot.

> - **Reset Bot Log Position** : Permet de reset les logs de votre bot.

***

> - **Open Project Directory** : Permet d'ouvrir le dossier de votre projet.

> - **Open Actions Directory** : Permet d'ouvrir le dossier d'actions de votre bot, par exemple lorsque vous téléchargez des actions moddées, il vous suffit de les glisser dans ce dossier pour les ajouter aux actions disponibles dans votre projet.

> - **Open Themes Directory** : Permet d'ouvrir votre dossier de thème pour votre projet.

> - **Open Translations Directory** : Permet d'ouvrir votre dossier de traduction de votre Projet, **par défaut vous n'avez que Anglais**.

***

> - **Verify Data Listing Integrity** : Permet de vérifier l'intégrité de vos fichiers de données dans le dossier `data` de votre projet.
  
</details>

***

 Ensuite le menu `Language`, lui permet de choisir la langue de votre logiciel, par défaut il n'y a que anglais. Je ne sais pas s'il existe de traduction en français, je vais donc essayer d'en faire une que je mettrais dans ce repo.

 ![Menu Language dans la barre d'outils](https://i.imgur.com/Jk83aYu.png)

 ***

Ensuite le menu `Theme`, lui permet de choisir le thème de votre logiciel, il me semble que de base il n'y a que default, celui que j'ai a dû être téléchargé avec des mods.

![Menu Theme dans la barre d'outils](https://i.imgur.com/5oXirCy.png)

***

Ensuite le menu `Resources`, lui permet d'avoir des documentations et de l'aide pour DBM, cependant ces aides sont en anglais.

![Menu Resources dans la barre d'outils](https://i.imgur.com/tccTAyD.png)

***

Ensuite le menu `About`, ce menu permet d'avoir les différents réseaux ou informations sur le logiciel.

![Menu About dans la barre d'outils](https://i.imgur.com/eH1W9pS.png)

***

Ensuite le menu `Extensions`, ce menu permet de géré les extensions du bot.

![Menu Extensions dans la barre d'outils](https://i.imgur.com/wJifFH2.png)

<details>
<summary>Liste des options du menu Extensions</summary>

> - **Bot Intents** : Permet de gérer les instances du bot, vous pouvez également gérer ces instances dans le [portail de développeur Discord](https://discord.com/developers/applications).
>
> ![Menu de bot intents](https://i.imgur.com/Au6sJgV.png)

> - **Bot Partials** : **ℹ️ Je n'ai pas d'informations sur cette partie**.
>
> ![Menu de bot partials](https://i.imgur.com/So6hADS.png)

  
</details>

***

## Onglet `Settings` Dans notre projet ⚙️
Dans cet onglet, on retrouve plusieurs catégories comme : `Bot Settings`,`Bot Settings 2`,`Editor Settings`,`Slash Command Options`,`Text Command Options`.
Je vais vous présenter les catégories une par une.

![Onglet Settings](https://i.imgur.com/6qR0HJ5.png)

***

### Bot Setings ⚙️

![Catégorie Bot Settings](https://i.imgur.com/gwXEF9t.png)

> - **Bot Owner ID** : Dans ce champ vous pouvez mettre l'ID du propriétaire du bot donc votre ID ([Comment obtenir une ID ?](https://support.discord.com/hc/fr/articles/206346498-O%C3%B9-trouver-l-ID-de-mon-compte-utilisateur-serveur-message))

> - **Bot Token** : Ici vous devez entrez le Token de votre bot

<details>
<summary>Comment obtenir le token de notre bot ?</summary>

> Pour obtenir le token de votre bot, il vous suffit de vous rendre sur le [portail de développeur Discord](https://discord.com/developers/applications) une fois connecter, soit vous créez une application soit vous avez déjà une application. Une fois votre application créée vous devrez aller dans bot puis sur "Reset Token", cela va reset le token de votre bot pour vous afficher le nouveau. Si l'autentification à 2 facteurs est activée sur votre compte, votre code vous sera demandé (je vous conseille de le garder **en sécurité** quelque part pour ne pas devoir le reset en cas de modification sur votre projet).
>
> ![Comment obtenir le token de son bot](https://i.imgur.com/Drbwx73.gif)

</details>

> - **Client ID** : Lorsque vous mettez le token de votre bot ce champ sera automatiquement remplis, vous pouvez quand même le remplir manuellement, il s'agit ici de l'id de votre bot ([Comment obtenir une ID ?](https://support.discord.com/hc/fr/articles/206346498-O%C3%B9-trouver-l-ID-de-mon-compte-utilisateur-serveur-message))

> - **Permissions Integer** : Il s'agit ici de choisir quelles permissions vous voulez mettre sur l'invitation de votre bot, si vous laissez ce champ par défaut toute les permissions seront mise dans l'invitation, pour obtenir les numéro des permissions il vous suffis d'aller sur le calculateur de permission de Discord dans le [portail de développeur Discord](https://discord.com/developers/applications) que vous retrouverez `OAuth2`>`OAuth2 URL Generator`>`bot`.
>
> ![Comment avoir le numéro de permission](https://i.imgur.com/vgcP94I.gif)

> - **Encryption Password** : **ℹ️Je ne sais pas de quoi il s'agit, je pense qu'il s'agit d'un mot de passe à mettre pour changer le token ou quelque chose comme ça mais je n'ai jamais utilisé cette option.**

***

### Bot Settings 2 ⚙️
Désormais la 2ème catégorie de bot settings, elle qui est plus pour de la configuration diverse.

![Catégorie Bot Settings 2](https://i.imgur.com/287vRzU.png)

> - **Invalid Button Response** : Ce paramètre permet de définir une réponse invalide sur l'action d'un bouton.

> - **Invalid Select Menu Response** : La même chose que pour les boutons mais sur les menu de sélections cette fois-ci.

> - **Invalid User Response** : Permet de définir une erreur de réponse de permissions sur l'action, par exemple si seul l'utilisateur de la commande peut interagir avec le bouton.

> - **Auto-Leave Voice Channel Delay (Seconds)** : Permet de définir en seconde au bout de combien de temps le bot va automatiquement leave un salon vocal.

> - **Auto-Defean on Voice Channel Join** : Permet de définir si le bot doit couper le son du casque lorsque qu'il rejoint un salon vocal
>
> ![icône deafen](ressources/deafened.png)

> - **Allow Bot Volume Changing in Actions** : Permet d'autoriser le changement de volume du bot dans certaines actions.

***

### Editor Settings 📊
Dans cette catégorie ça va être la partie pour configuré notre logiciel DBM

![Catégorie Editor Settings](https://i.imgur.com/w042Uug.png)

> - **Editor Content Fill** : Permet de changer la largeur de votre espace de travail donc toute la zone grise. **Reset** permet de mettre la valeur à son état normal (`1200`). **Fill** Permet de remplir toute la zone disponible (2400) si vous ne mettez rien dans le champ toute la zone va automatiquement être occupée.

> - **Editor Zoom** : Permet de géré le zoom de votre logiciel, par défaut 0.

> - **Delete Policy** : Permet de faire en sorte d'activer ou de désactiver la demande avant la suppression. **Ask Always to Delete** : Toujours demander pour supprimer, à chaque fois que vous voudriez supprimer quelque chose, il vous demandera si vous êtes sûr. **Delete Actions without Asking** : Supprimer les actions sans demander, cela permet de retiré la confirmation seulement pour les actions. **Never Ask, Delete Immediately** : Ne jamais demander supprimer immédiatement, plus aucune confirmation de suppression.

> - **Auto Restart Bot on Save** : Permet de redémarré le bot automatiquement à chaque sauvegarde.

> - **Show Command/Event IDs** : Permet d'afficher les IDs des commandes et des événements, je ne l'utilise pas personellement car je ne trouve pas l'utilité.

> - **Automatically Update Bot-js** : permet de mettre à jour automatiquement le fichier `bot.js` lorsque vous sauvegarder.

> - **Automatically Update Modules** : permet de mettre à jour automatiqueement les modules.

> - **Allow Action Dialog Resizing** : **ℹ️Je n'ai pas d'information sur ce paramètre.**

> - **Allow Extension Dialog Resizing** : **ℹ️Je n'ai pas d'information sur ce paramètre.**

***

### Slash Command Options ⚙️
Cette catégorie permet de configuré toute la partie slash command (les commandes en `/`).

![Catégorie Slash Command Options](https://i.imgur.com/H4D0pow.png)

> - **Slash Command Creation Preference** : Il y a ici beaucoup de choix, cette option vous permet de choisir comment et où vos slash command seront deployés. Si vous choisissez une option où il faut renseigner certain serveur l'espace texte en dessous se débloquera, vous devrez mettre les id des serveurs ici et une id par ligne. ([Comment avoir l'id de son serveur?](https://support.discord.com/hc/fr/articles/206346498-Où-trouver-l-ID-de-mon-compte-utilisateur-serveur-message)
>
> ![Aide Slash Command Creation Preference](https://i.imgur.com/JtOKYYf.gif)

<details>
<summary>Traduction de l'aide</summary>

### Automatically Decide Based on Server Count | Décidé automatiquement sur le nombre de serveur

> - Si le bot est dans un petit nombre de serveurs (environ 15), "Créer toutes les commandes Slash pour chaque serveur" sera utilisé.

> - Sinon, "Make all Slash Commands Global"(Rendre toutes les slash command global) sera utilisé.

### Make all Slash Commands Global | Rendre toutes les slash command global

> - Toutes les commandes s’enregistreront comme des commandes "globales" sur l’API de Discord.

> - Toutes les commandes slash seront disponibles sur tous les serveurs où se trouve le bot.

> - Les commandes Slash seront disponibles dans les DM du bot.

### Create all Slash Commands for every Server | Crée toute les command slash pour tout les serveurs

> - Toutes les commandes seront enregistrées comme des commandes "serveur" pour chaque serveur dans lequel le bot est sur l’API de Discord.

> - Toutes les commandes slash seront disponibles sur tous les serveurs où se trouve le bot.

> - Les commandes Slash ne fonctionneront PAS dans les DM du bot.

> - Heureusement, les commandes du serveur se rafraîchissent très rapidement, ce qui en fait une excellente option pour les bots sur seulement quelques serveurs ou ceux qui sont testés fréquemment.

> - Cependant, si le bot est sur trop de serveurs, cela peut être plus lent et moins cohérent que les commandes globales.

### Create all Slash Commands in Selected Servers Only, No Global | Crée toute les slash command dans les serveurs sélectionnés seulement, non global

> - Toutes les commandes seront enregistrées comme des commandes "serveur" pour chaque serveur répertorié sur l’API de Discord.

> - Toutes les slash command seront disponibles uniquement sur les serveurs listés.

> - Les slash command ne fonctionneront PAS dans les DM du bot.

> - Heureusement, les commandes du serveur se rafraîchissent très rapidement. C’est parfait pour tester des slash command en privé.

### Create all Slash Commands in Selected Servers, and Use Global Everywhere Else | Crée toute les slash command dans les serveurs sélectionner, et utilse les commandes global.

> - Toutes les commandes seront enregistrées comme des commandes "serveur" pour chaque serveur répertorié sur l’API de Discord.

> - Toutes les commandes s’enregistreront comme des commandes "global" sur l’API de Discord.

> - Toutes les slash command seront disponibles sur tous les serveurs où se trouve le bot, cependant elles prennent une heure pour rafraîchir les serveurs non spécifiquement répertoriés.

> - Les slash command fonctionneront dans les DM du bot, mais elles prennent une heure pour se rafraîchir.

> - Cela permet aux slash command d’être testées et modifiées rapidement sur certains serveurs, mais restent actives sur d’autres en utilisant des commandes globales.

  
</details>

> [!TIP]
> Je vous conseil pour ceux qui font des bots de test de mettre l'option "Create all Slash Commands in Selected Servers Only, No Global" qui vous permet de choisir sur quels serveurs il va y avoir vos slash command, cela permet aussi d'augmenter la rapidité de celles-ci.
> Si vous voulez mettre vos commandes partout et pour un bot qui va avoir plus de serveur je vous conseil l'option "Make all Slash Commands Global"

> - **Default Slash Command Response** : Il s'agit de la réponse à vos slash command par défaut, par exemple si dans toute vos actions il n'y à pas d'action de texte dans le salon d'où est éxécuté la commande ça va être ce texte qui sera mit en [message éphémère](https://support.discord.com/hc/en-us/articles/1500000580222-Ephemeral-Messages-FAQ).

> - **No Description Text** : Il s'agit ici de la description qui sera mise au slash command sans description.

> - **Invalid Permissions Response** : Il s'agit ici de la réponse à la slash command si les permissions de l'utilisateurs sont invalides.

> - **Time Restriction Enforced Response** : Il s'agit ici de la réponse qui sera donnée sur les commandes à cooldown, par exemple sur une qui a 5s de cooldown. Si j'effectue cette commande et et que je la refais directement après je vais avoir cette réponse `Must wait 5s before using this action.`, cette réponse peut être modifiée. Vous pouvez mettre ce que vous voulez et pour définir où est mis le temps vous devez mettre `%s` exemple : `Merci d'attendre %s avant d'éxécuter cette commande.` le `%s` sera remplacé par le nombre de secondes/minutes/+ que l'utilisateur doit attendre.

***

### Text Command Options ⚙️
Il s'agit ici des options pour les commandes textuels ou les commandes avec préfix.

[catégorie Text Command Options](https://i.imgur.com/zejkqfO.png)

> - **Command tag** : Permet de choisir le préfix du bot.

> - **Parameter Separator** : **ℹ️Je n'ai pas d'information sur ce paramètre.**

> - **No Command Case Sensitive** : **ℹ️Je n'ai pas d'information sur ce paramètre.**

> - **Allow Prefix Spaces** : Ce paramètre sert à définir si on autorise les espace avant ou après le préfix, si le paramètre est sur "No" alors si quelqu'un met un espace entre le préfix et la commande, la commande ne sera pas éxécuté.

***

## FIn des explications 🛑
Merci d'avoir suivi cette aide, je tiens à m'excuser des fautes d'ortographes ainsi que du manque d'informations je me renseignerais pour mettre à jour cette documentation.

Si vous avez des idées ou des améliorations pour cette doc vous pouvez me contacter sur Discord sous mon pseudo : minzoy

<sub>Je tiens à remercier Str4ky qui ma aider sur le Run Project Independently</sub>
