# PROJET - Chat d'avril

# I- Sujet

Le but de ce tp, est de créer une application de discussion, permettant de communiquer avec la personne que l'on souhaite et peu importe l'endroit où on se trouve. En fait: un Chat.
Vous devez réaliser cette application dans le langaguage que vous souhaitez parmis les suivants: java, C#, python.
Le serveur et le client devront être écris dans des langages différents.

## Le client

Voici une liste d'exigences pour le client :
- L'utilisateur doit définir un pseudo avant de pouvoir se connecter et le pseudo ne doit dépasser 20 caractères.
- L'utilisateur ne peut pas prendre un pseudo déjà utilisé
- L'utilisateur doit envoyer le message au serveur et le message sera diffusé à tous les autres utilisateurs.
- Utilisez la notion de classe avec des structures
- Prévenir les autres utilisateurs qu'un utilisateur s'est connecté/déconnecté
- Le client et le serveur communiquent via le protocole TCP
- Utiliser les SCOKET et le MULTI-THREAD 
- Le client peut être en interface graphique ou en console

## Le serveur

Le serveur est une application différente de l'application client.
Voici une liste d'exigences pour le serveur :
- Le serveur accepte plusieurs utilisateurs
- Le serveur possède un fichier de logs avec les connexions entrantes et sortantes.
- Utilisez la notion de classe avec des structures pour le code
- Doit stocker en mémoire la liste des clients
- Le client et le serveur communiquent via le protocole TCP
- Utiliser les SCOKET et le MULTI-THREAD 
- Le serveur doit être en console

## Discution privée

Un utilisateur peut envoyer un message à un autre utilisateur en privé, ce qui signifie que les autres utilisateurs sur le chat ne verront pas ce message.
Pour cela il sélectionne le pseudo de son interlocuteur privé et lui envoie le message. L'utilisateur recevant le message doit savoir que c'est un message privé.

## Groupe (bonus)

Un utilisateur peut créer un groupe, puis ajouter d'autre utilisateur dans le groupe.
Dans ce cas tous les messages envoyés dans ce groupe ne sont lisibles que par les membres du groupe.
Un utilisateur peut quitter le groupe quand il le souhaite, le créateur du groupe peut supprimer un membre quand il le souhaite.


## Documentation

Le code complet devra être documenté.

# Groupes et fonctionnement

Le projet est a développé en équipe de 4 personnes. Vous choisissez votre groupe.

Toute inscription est définitive.  Les étudiants ne sont pas autorisés, par la suite, à changer de groupe.

Au sein d'un groupe, les étudiants se répartiront les tâches pour le projet, de façon équitable.  Il est explicitement exigé que chaque membre consacre au moins 50% de son travail à du développement technique. Du code de test est acceptable, tant qu'il ne constitue pas l'intégralité de la réalisation technique du membre du groupe.

Les étudiants sont encouragés (mais pas obligés) à mettre en place un système de contrôle des sources de type Git ou équivalent, afin d'affecter et partager efficacement les fichiers de codes et autres composants numériques du projet (fichiers sources, descripteurs de déploiement, documents de recherche, cas d'utilisation, suites de tests, etc.).

# Présentation et rendu

Le rendu aura lieux le vendredi 14 avril 2023.

Les rendus doivent figurer sur un seul compte par groupe.
Le rendu s'effectu via un repos GIT. L'adresse du rendu est envoyé par mail.
Le mail de rendu est vleclerc@inow.fr
Les fichiers rendus doivent contenir
  - L'arborescence du projet, immédiatement exploitable ou un GIT.
  - Un readme.md listant les membres du groupe (prénom, nom), à raison d'un par ligne.  Il liste ensuite les responsabilités effectives de chacun dans le groupe.
Le sujet du mail doit contenir votre section ainsi que le nom du projet et du groupe.
Les fichiers rendus peuvent aussi comprendre: 
  - Des documents de recherche créés pour le projet et fournissant plus de détails pour l'enseignant.
Pour tout autre type de fichier, veuillez demander à l'enseignant si son inclusion est appropriée.
La soutenance dure 10 minutes durant lesquelles les membres présentent leur travail. Un échange de questions peut se faire entre le professeur et les membres du groupe.



