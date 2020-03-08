# Documentation
Documentation de toutes les commandes de Swan (39)

## Commandes

#### 8ball (module "fun")

- **Description :** Le bot répondra par Oui ou Non à une n'importe quelle question que vous lui posez ! Réponse sûre garantie à 7%
- **Aliases :** `8ball`
- **Usage :** `8ball <question>`
- **Exemples :** `8ball suis-je le plus beau ?`

#### Addon Info (module "info")

- **Description :** Obtenir diverses informations sur un addon, telles que son auteur, sa dernière version, un lien de téléchargement, si l'addon est déprecié, les dépendances...
- **Aliases :** `addoninfo` | `addon_info` | `addon-info`
- **Usage :** `addon-info <addon>`
- **Exemples :** `addon-info skquery-lime | addonsinfos -list | addoninfo mirror`

#### Addon Pack (module "basic")

- **Description :** Permet de d'avoir un pack d'addon correspondant à une certaine version de Minecraft.
Si vous connaissez une version plus récente d'un addon fonctionnant dans une certaine version de minecraft, n'hésitez pas a contacter les devs ou à vous rendre sur le discord de développement (lien disponible dans les messages pins de #bot).
- **Aliases :** `addonpack` | `addon_pack` | `addon-pack`
- **Usage :** `addon-pack <votre version de serveur>`
- **Exemples :** `addon-pack 1.14`

#### Automatic Messages (module "basic")

- **Description :** Envoyer un message prédéfini parmis ceux-là : `%s`. Merci de ne pas abuser de cette commande, et de l'utiliser seulement si besoin.
- **Aliases :** `automaticmessage` | `automatic_message` | `automatic-message` | `automsg` | `auto_msg` | `auto-msg` | `auto`
- **Usage :** `automsg <nom du message>`
- **Exemples :** `automsg asktoask`

#### Ban (module "moderation")

- **Description :** Appliquer une restriction du Discord à un joueur.
- **Aliases :** `ban` | `sdb`
- **Usage :** `ban <@mention | ID> <durée> [<raison>]`
- **Exemples :** `ban @Uneo7 5j Mouahaha`

#### Code (module "basic")

- **Description :** Permet de mettre votre code dans un bloc de code.
- **Aliases :** `code` | `balise`
- **Usage :** `code <votre code>`
- **Exemples :** `code broadcast "Yeah!"`
- **Cooldown :** 5 secondes

#### Error Details (module "basic")

- **Description :** Commande qui permet de vous aider à régler les erreurs que vous pouvez avoir lorsque vous faites /sk reload. Attention, cette commande est en BETA, donc le pourcentage de précision n'est pas garanti à 100%. Il se peut aussi que certaines erreur ne soit pas disponibles.
- **Aliases :** `errordetail` | `errordetails` | `error_detail` | `error_details` | `error-detail` | `error-details`
- **Usage :** `errordetail <votre erreur>`
- **Exemples :** `errordetail Can't compare 'if arg 1' with a text`

#### Ghostping (module "moderation")

- **Description :** Permet de mentionner un membre sans laisser aucune trace.
- **Aliases :** `ghostping`
- **Usage :** `ghostping @mention`
- **Exemples :** `ghostping @Vengelis_ le FISC`

#### Help (module "basic")

- **Description :** Afficher la page d'aide de toutes les commandes de Swan, ou donne des informations sur une commande spécifique.
- **Aliases :** `help` | `aide`
- **Usage :** `help [<commande | page>]`
- **Exemples :** `help ping | help | help 4`

#### Join (module "music")

- **Description :** Ammener le bot dans votre canal s'il n'est pas occupé ailleurs, ou s'il n'y ai pas déjà.
- **Aliases :** `join` | `rejoindre`
- **Usage :** `join`
- **Exemples :** `join`

#### Joke (module "fun")

- **Description :** Envoie aléatoirement une blague drôle (ou pas).
- **Aliases :** `joke` | `blague` | `rire`
- **Usage :** `joke`
- **Exemples :** `joke`

#### Leave (module "music")

- **Description :** Permet de faire partir le bot du canal vocal.
- **Aliases :** `leave` | `quitter`
- **Usage :** `leave`
- **Exemples :** `leave`

#### Links (module "basic")

- **Description :** Avoir plusieurs liens importants relatifs à Skript, tels que des documentations, des forums, des liens de téléchargement, des discords...
- **Aliases :** `links` | `liens` | `link` | `lien`
- **Usage :** `link [<la page que vous souhaitez>]`
- **Exemples :** `link 3`

#### Loop (module "music")

- **Description :** Permet de faire en sorte que le bot répète une musique, ou ne répète pas.
- **Aliases :** `loop` | `boucle` | `repeat`
- **Usage :** `loop [music | off]`
- **Exemples :** `loop | loop music | loop off`

#### Mathematiques (module "basic")

- **Description :** Permet de tester une expression mathématique en Skript.
- **Aliases :** `math` | `mathematique` | `mathematiques` | `mathématique` | `mathématiques`
- **Usage :** `math <expression mathématique de skript>`
- **Exemples :** `math sqrt(12) + 18 - abs(-13)`

#### Mute (module "moderation")

- **Description :** Rendre muet un joueur dans les salons d'aide.
- **Aliases :** `mute`
- **Usage :** `mute <@mention | ID> <durée> [<raison>]`
- **Exemples :** `mute @AlexLew 5j Une raison plus ou moins valable`

#### Now Playing (module "music")

- **Description :** Affiche des informations sur la musique en cours.
- **Aliases :** `np` | `nowplaying` | `now-playing` | `now_playing`
- **Usage :** `nowplaying`
- **Exemples :** `nowplaying | np | music-info`

#### Pause (module "music")

- **Description :** Permet de mettre ou d'enlever la pause d'une musique.
- **Aliases :** `pause` | `resume`
- **Usage :** `pause`
- **Exemples :** `pause | resume`

#### Ping (module "basic")

- **Description :** Permet de savoir la latence entre vous et le bot, et le bot et l'API Discord.
- **Aliases :** `ping` | `ms`
- **Usage :** `ping`
- **Exemples :** `ping`

#### Play (module "music")

- **Description :** Permet de jouer une musique ou une playlist avec le bot, selon son nom, son URL youtube ou l'URL d'une playlist. Ajouter `--first` pour choisir automatiquement le premier résultat, si vous cherchez une musique par son nom.
- **Aliases :** `play` | `jouer` | `joue`
- **Usage :** `play [<musique [--first] | URL de musique youtube | URL de playlist youtube>]`
- **Exemples :** `play darude sandstorm | play gangnamstyle --first | play https://youtu.be/y6120QOlsfU | play`
- **Cooldown :** 3 secondes

#### Player Info (module "info")

- **Description :** Afficher diverses informations sur un certain joueur, que vous avez défini par son pseudo Minecraft.
- **Aliases :** `playerinfo` | `player_info` | `player-info`
- **Usage :** `player-info <pseudo>`
- **Exemples :** `player-info noftaly`

#### Poll (module "fun")

- **Description :** Lancer un sondage temporaire par lequel on peut répondre Oui/Non ou une réponse personnalisée.
- **Aliases :** `poll` | `vote` | `sondage`
- **Usage :** `poll <durée> "<sondage>" ["réponse 1"] ["réponse 2"] [...]`
- **Exemples :** `poll 10m "votre sondage" "réponse 1" "réponse 2" "réponse 3" "réponse 4" | poll 10m "votre sondage"`

#### Purge (module "moderation")

- **Description :** Supprimer X messages dans un canal, selon un certain utilisateur ou non. La limite est fixée à 100.
- **Aliases :** `purge`
- **Usage :** `purge [<@mention>]`
- **Exemples :** `purge @utilisateur 20`

#### Queue (module "music")

- **Description :** Permet d'afficher la liste de toutes les musiques dans la queue.
- **Aliases :** `queue`
- **Usage :** `queue [<remove <index> | clear>]`
- **Exemples :** `queue | queue remove 2 | queue clear`

#### Remove Music Restriction (module "moderation")

- **Description :** Redonner à un joueur l'accès à la commande `.play`.
- **Aliases :** `removemusicrestriction` | `remove-music-restriction` | `remove_music_restriction` | `remmusicrestr` | `rem-music-restr` | `rem_music_restr`
- **Usage :** `removemusicrestriction <@mention | ID> [<raison>]`
- **Exemples :** `removemusicrestr @4rno En fait c'est une bonne musique`

#### Rules (module "basic")

- **Description :** Permet d'afficher les règles des salons d'aide Skript.
- **Aliases :** `rule` | `rules` | `règle` | `regle` | `règles` | `regles`
- **Usage :** `rule <règle>`
- **Exemples :** `rule 2`

#### Server Info (module "info")

- **Description :** Afficher diverses informations sur un certain serveur Minecraft, selon son IP.
- **Aliases :** `serverinfo` | `server_info` | `server-info` | `serveurinfo` | `serveur_info` | `serveur-info`
- **Usage :** `serveur-info <IP>`
- **Exemples :** `serv-info hypixel.net`

#### Shuffle (module "music")

- **Description :** Permet de mélanger l'ordre des musiques dans la queue.
- **Aliases :** `shuffle` | `mix` | `melanger` | `mélanger`
- **Usage :** `shuffle`
- **Exemples :** `shuffle`

#### Skip (module "music")

- **Description :** Permet de passer une ou plusieurs musique.
- **Aliases :** `skip` | `next` | `passer` | `passe` | `suivant`
- **Usage :** `skip [<nombre>]`
- **Exemples :** `skip | skip 3`
- **Cooldown :** 3 secondes

#### Skript Info (module "info")

- **Description :** Avoir diverses informations sur Skript, telles que sa version actuelle, un lien de téléchargement, les versions de Skript à utiliser selon la version Minecraft...
- **Aliases :** `skriptinfo` | `skript-info` | `skript_info`
- **Usage :** `skript-info`
- **Exemples :** `skriptInfo`

#### Statistics (module "basic")

- **Description :** Avoir diverses statistiques sur le bot et le serveur.
- **Aliases :** `statistique` | `statistiques` | `statistic` | `statistics` | `stats` | `stat`
- **Usage :** `statistique`
- **Exemples :** `statistique`

#### Stop (module "music")

- **Description :** Permet de faire partir le bot du canal vocal.
- **Aliases :** `stop` | `arrêt` | `arret`
- **Usage :** `stop`
- **Exemples :** `stop`

#### Tag Role (module "moderation")

- **Description :** Permet de notifier un rôle qui n'est pas mentionnable.
- **Aliases :** `tagrole` | `tag-role` | `tag_role`
- **Usage :** `tag-role <rôle>`
- **Exemples :** `tagrole Notifications Évènements`

#### Toggle role notification (module "basic")

- **Description :** Permet de vous mettre ou de vous enlever le rôle Notifications Évenement.
- **Aliases :** `toggle-notif-role` | `togglenotifrole` | `toggle_notif_role`
- **Usage :** `toggle-notif-role`
- **Exemples :** `toggle-notif-role`

#### Unban (module "moderation")

- **Description :** Retirer une restriction du Discord à un joueur. Ajoutez l'argument `-no-delete` pour ne pas supprimer le canal privé.
- **Aliases :** `unban`
- **Usage :** `unban <@mention | ID> [-no-delete] [<raison>]`
- **Exemples :** `unban @Acenox Oups je voulais ban qqun d'autre`

#### Unmute (module "moderation")

- **Description :** Redonner la parole à un joueur dans les salons d'aide.
- **Aliases :** `unmute`
- **Usage :** `unmute <@mention | ID> [<raison>]`
- **Exemples :** `unmute @4rno G mété tronpé hé`

#### User Info (module "info")

- **Description :** Afficher diverses informations sur un certain membre du Discord Skript-MC, que vous avez défini par son ID ou en le mentionnant (Merci d'éviter de mentionner. Pour récupérer l'ID de quelqu'un, activez le mode développeur (Paramètres > Apparence > Avancé > Mode développeur), puis faites un clic-droit sur son pseudo > Copier l'Identifiant).
- **Aliases :** `userinfo` | `user-info` | `user_info`
- **Usage :** `user-info <@mention | ID>`
- **Exemples :** `userinfo @noftaly | user-infos 188341077902753794`

#### Volume (module "music")

- **Description :** Modifier le volume de la musique. Pour éviter de géner les autres utilisateurs, veuillez plutôt baisser le volume du bot, en faisant un `clique droit` dessus, puis en baissant le curseur `Volume de l'utilisateur`.
- **Aliases :** `volume`
- **Usage :** `volume [<nombre entre 1 et 10>]`
- **Exemples :** `volume | volume 3`

#### Warn (module "moderation")

- **Description :** Donner un avertissement à un joueur.
- **Aliases :** `warn`
- **Usage :** `warn <@mention | ID> [<raison>]`
- **Exemples :** `warn @polymeth Langage incorrect`

