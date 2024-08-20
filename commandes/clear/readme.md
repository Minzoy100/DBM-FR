# Clear
Il s'agit d'une [slash command](https://support.discord.com/hc/en-us/articles/1500000368501-Slash-Commands-FAQ). La commande `/clear` permet de supprimer un certain nombre de message, définie par l'utilisateur dans le paramètre "nombre" par exemple ici : `/clear nombre:10` la commande est faite pour supprimer 10 messages. Cette commande demande la permission "gérer les messages" pour que seuls les modérateurs ou membres qui ont la possibilité de supprimer des messages puissent utiliser cette commande.

<details>
<summary>RAW DATA</summary>

### RAW DATA de la commande `/clear`

  ```js
{
  "name": "Clear",
  "permissions": "MANAGE_MESSAGES",
  "permissions2": "NONE",
  "restriction": "1",
  "_id": "OmHDB",
  "actions": [
    {
      "channel": "0",
      "count": "${slashParams(\"nombre\")}",
      "condition": "0",
      "custom": "",
      "varName": "",
      "name": "Delete Bulk Messages"
    },
    {
      "color": "#2981f5",
      "storage": "1",
      "varName": "color",
      "name": "Color"
    },
    {
      "member": "1",
      "varName": "",
      "info": "16",
      "storage": "1",
      "varName2": "avatar",
      "name": "Store Member Info"
    },
    {
      "member": "1",
      "varName": "",
      "info": "2",
      "storage": "1",
      "varName2": "name",
      "name": "Store Member Info"
    },
    {
      "channel": "0",
      "varName": "",
      "message": "",
      "buttons": [],
      "selectMenus": [],
      "attachments": [],
      "embeds": [
        {
          "title": "Clear",
          "url": "",
          "color": "${tempVars(\"color\")}",
          "timestamp": "true",
          "imageUrl": "",
          "thumbUrl": "",
          "description": "J'ai bien supprimé `${slashParams(\"nombre\")}` messages !",
          "fields": [],
          "author": "${tempVars(\"name\")}",
          "authorUrl": "",
          "authorIcon": "${tempVars(\"avatar\")}",
          "footerText": "Made with ❤️ by Minzoy",
          "footerIconUrl": "https://images-ext-1.discordapp.net/external/wKKYyNAGo9-uZMGp7OwfJDTKW_I14ZRwrnBmyLzVC1w/https/cdn.discordapp.com/avatars/687317661381558279/31dd73826dd85d536cf2504f6b242d92.png?format=webp&quality=lossless&width=96&height=96"
        }
      ],
      "reply": true,
      "ephemeral": false,
      "tts": false,
      "overwrite": false,
      "dontSend": false,
      "editMessage": "0",
      "editMessageVarName": "",
      "storage": "0",
      "varName2": "",
      "name": "Send Message"
    }
  ],
  "comType": "4",
  "description": "Permet de clear des commandes",
  "parameters": [
    {
      "name": "nombre",
      "description": "Nombre de messages à supprimer",
      "type": "INTEGER",
      "required": true,
      "choices": null
    }
  ],
  "_timeRestriction": 5
}
```

</details>

***

## Fonctionnement utilisateur
La commande peut être appelée avec `/clear`. Une fois la commande sélectionnée, le paramètre obligatoire "nombre" apparaît dedans. Vous devez mettre des **nombres** ces nombres sont le nombre de messages que le bot doit supprimer. Cette commande a également un cooldown de 5 secondes.

![prompt de la commande pour clear](ressources🗃️/commande/clear/command_clear_prompt.png)

Une fois cette commande éxécuté le bot va supprimer le nombre de message voulus seulement si l'utilisateur qui éxécute la commande a la permission "gérer les messages".

exemple avec 10 messages : 

![10 messages](../ressources🗃️/commande/clear/command_clear_test.png)

Une fois la commande éxécuté : 

![résultat de la commande](../ressources🗃️/commande/clear/command_clear_result.png)

***

## Développement
Dans cette commande on commence par définir notre commande en tant que "Slash command" ensuite on vient ajouter le paramètre "nombre" qui est un paramètre "number" pour bien avoir que des nombres, ensuite on indique le nom de notre paramètre donc "nombre" et la description de ce paramètre donc pour ma commande clear "Nombre de messages à supprimer", ensuite on vérifie les permissions de l'utilisateur grâce au "Primary Required Permission" et on vérifie que l'utilisateur a bien la permission "Manage messages" ensuite on vient supprimer un certain nombre de messages avec l'action "Delete Bulk Messages" dans le champ de saisi on vient mettre notre paramètre de notre slash command donc "${slashParams("nombre")}" et dans "Delete condition" on laisse sur none car on veut que tout les 10 derniers messages soient supprimer. Ensuite la libre au dév de faire comme il veut, dans mon cas j'ai mis une action "color" pour définir la couleur de mon embed qui va être utiliser comme résultat de commande, après ça je récupère l'avatar et le username de la personne qui fait la commande pour le mettre dans "author" donc l'auteur de la commande.
***

### FIN
Commande réalisée par **Minzoy**. Libre d'édition
Une future mise à jour pour cette commande va être déployé.
Si vous avez la moindre amélioration ou correction pour cette doc, n'hésitez pas à me contacter sur Discord : minzoy
