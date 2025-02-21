# Script Troller - Serveur GTA RP

Bienvenue dans le **Script Troller** pour votre serveur **FiveM GTA RP**. Ce script a été créé par **Momo** et des intelligences artificielles, et permet de gérer les instances et les utilisateurs dans le cadre de votre serveur.

## Description

Le script Troller offre plusieurs fonctionnalités utiles pour gérer les joueurs dans des **instances** (salles privées ou zones spécifiques), incluant des commandes pour envoyer ou retirer des joueurs d'une instance, gérer des grades sur le serveur, supprimer certaines explosifs comme le C4 et la Bazooka, et maintenir la connexion des joueurs dans une instance même après une déconnexion.

## Fonctionnalités

- **Commandes pour gérer les instances** :
  - `envoyertroller IDtemporaire` : Permet d'envoyer un joueur dans une instance spécifique.
    ```lua
    RegisterServerEvent('envoyertroller:setBucket')
    ```
  - `retirertroller IDtemporaire` : Permet de retirer un joueur d'une instance spécifique.
    ```lua
    RegisterServerEvent('envoyertroller:removeFromBucket')
    ```

- **Gestion des grades** :
  - Modification des grades directement depuis le côté serveur pour attribuer des rôles spécifiques comme :
    - Fondateur
    - Développeur
    - Responsable
    Ces rôles peuvent être utilisés pour accorder des permissions supplémentaires aux joueurs.

- **Suppression des explosions** :
  - Désactivation des armes explosives comme le C4, la Bazooka, etc., pour éviter les abus sur le serveur.

- **Maintien des instances après déconnexion** :
  - Lorsque un joueur se déconnecte puis se reconnecte, il reste dans l'instance où il se trouvait précédemment.

## Installation

1. **Téléchargez le fichier** du script via ce lien :  
   [Télécharger TakaTroller](https://cdn.discordapp.com/attachments/1341846348189798452/1341846453076885547/TakaTroller.rar?ex=67b77b64&is=67b629e4&hm=32acc93909e18f82988873f1b7e25ac70c3c8cc19d2e2b2ab80cbd6b05a2a61a&)

2. **Décompressez** le fichier téléchargé et placez-le dans le répertoire de votre serveur.

3. **Ajoutez** les fichiers nécessaires à votre serveur FiveM, puis **modifiez** la configuration selon vos préférences.

4. **Redémarrez le serveur** pour appliquer les changements.

## Utilisation

### Commandes Serveur

- `envoyertroller IDtemporaire` : Envoie un joueur dans l'instance spécifiée.
- `retirertroller IDtemporaire` : Retire un joueur de l'instance en cours.

### Gestion des Grades

1. Connectez-vous en tant qu'administrateur sur le serveur.
2. Accédez au côté serveur et modifiez les grades des joueurs comme suit :
   - Fondateur
   - Développeur
   - Responsable

### Suppression des Explosifs

Les armes comme le C4, la Bazooka et d'autres explosifs seront désactivées automatiquement pour éviter tout abus.

### Gestion des Instances

Les joueurs resteront dans leur instance même s'ils se déconnectent et se reconnectent plus tard.

## Aide et Support

Si vous avez besoin d'aide ou de support technique, n'hésitez pas à poser des questions dans notre **Discord** ou à consulter notre documentation.

---

Merci d'avoir choisi le script **Troller** pour votre serveur FiveM ! Profitez bien de votre expérience RP ! 😎
