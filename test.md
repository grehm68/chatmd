---
clavier: true
gestionGrosMots: true
rechercheContenu: false
avatar: https://codimd.apps.education.fr/build/emojify.js/dist/images/basic/helmet_with_white_cross.png
footer: <footer id="footer"> Raphaël BROCQ - <a target="_blank" href="https://latourette.blogs.laclasse.com/">Collège La Tourette - Lyon 1er</a> - 2025 |   <a target="_blank" href="https://creativecommons.org/licenses/by-nc-sa/4.0/deed.fr">CC BY NC SA</a> | Réalisé avec <a target="_blank" href="https://chatmd.forge.apps.education.fr">ChatMD</a></footer>
tags: chatbot
---

# Une question, un problème avec le mBot (Moi) ?

<section markdown class="unique">
Tu veux savoir ce qu'on mange au Crous. Demande-moi !

Tu peux choisir parmi les propositions ci-dessous ou bien saisir ta demande dans la zone de saisie clavier ci-dessous.

C'est parti !
</section>

Quelle est ta question ? ton problème ?

1. [📂 Qu'est-ce qu'on mage aujourd'hui au Crous ?](Ouvrir_Fichier)
2. [💾 Où mange-t-on végé aujourd'hui ?](Enregistrer_Fichier)
3. [👩‍💻 Comment réaliser un programme ?](Realisation_d_un_programme)
4. [📤 Comment téléverser un programme ?](Televersement)
5. [#️⃣ Comment obtenir les blocs d'instruction pour le robot mBot dans l'interface mBlock ?](Blocs_mBot)
6. [🧰 Pourquoi mon programme ne se téléverse pas ?](Pb_Televersement)
7. [🤔 Le bouton Connecter est absent de mon écran ?](Televersement)


## Ouvrir_Fichier
- ouvrir
- local

L'interface mBlock propose deux méthodes pour ouvrir un fichier, soit :
- en ligne : le fichier est enregistré dans le cloud de la société makeblock,
- en local, sur son ordinateur ou sur un réseau privé comme celui du collège.

Au collège, nous **ouvrirons des fichiers enregistrés en local**. Donc pour ouvrir un fichier existant : 

:::info
🔧 1. Cliquer sur Fichier > Ouvrir à partir de votre ordinateur
2. Parcourir l'arborescence et sélectionner le fichier. Souvent il est dans le dossier Telechargement de l'utilisateur.
![Ouvrir un fichier depuis votre ordinateur](https://brocq-dandachi.fr/bots/mblock_01.png)<br>
3. Selon ta situation, une fenêtre s'ouvrira pour te demander si tu souhaites ou pas enregistrer le fichier actuel. A toi, de choisir entre **Ne pas enregitrer" et "Enregistrer".
![Sauvegarder_fichier_existant](https://brocq-dandachi.fr/bots/mblock_10.png)
:::

A toi de jouer :+1: 


1. [Retour au début]()


## Enregistrer_Fichier
- enregistrer
- sauvegarder

L'interface mBlock propose deux méthodes pour enregistrer un fichier, soit :
- en ligne : le fichier est enregistré dans le cloud de la société makeblock,
- en local, sur son ordinateur ou sur un réseau privé comme celui du collège.

Au collège, nous **enregistrerons les fichiers en local**. Il ne faudra donc pas cliquer sur **Enregistrer** ou **Enregistrer sous...***
:::info
🔧 Au collège, pour enregistrer un fichier, il faut donc :
1. Lui donner un nom en remplaçant *sans titre* par le nom souhaité
2. Cliquer sur Fichier > Enregistrer sur votre ordinateur
3. Par défaut, le fichier s'enregistrera dans le dossier Telechargement de l'utilisateur.  
![Enregistrer](https://brocq-dandachi.fr/bots/mblock_03.png)
:::
A toi de jouer :+1: 

1. [Retour au début]()



## Blocs_mBot
- appareil

Tu ne trouves pas les blocs spécifiques au **robot mBot** ? C'est tout simplement parce que par défaut les blocs du **robot mBot** ne sont pas activés. Il va falloir sélectionner le **robot mBot** dans la liste des appareils. Pour cela :

:::info
🔧 1. Cliquer sur le bouton Appareils
![Bouton Appareils](https://brocq-dandachi.fr/bots/mblock_04.png)
2. puis sélectionner le robot mBot 
3. et valider en cliquant sur le bouton OK.
![Sélection du mBot](https://brocq-dandachi.fr/bots/mblock_05.png)
Le robot mBot apparaît dans la liste des appareils.
![mBot dans Appareils](https://brocq-dandachi.fr/bots/mblock_06.png)
:::

1. [Retour au début]()


## Realisation_d_un_programme
- interface
- programme
- ide


:::info
🔧 
1. Lancer le logiciel mLink et le laisser en tâche de fond ([voir la méthode ici](#Verification 4))
2. Accéder à l'interface mBlock 5 via l'adresse https://ide.mblock.cc/
3. Aller dans l'onglet Appareils et ajouter le robot mBot.  ([voir la méthode ici](#Blocs_mBot))
4. Cliquer sur **Basculer vers mLink** puis sur le commutateur de mode pour basculer en mode **Téléverser**.
![mode mLink](https://brocq-dandachi.fr/bots/mblock_09.png)
:::

Tu es prêt pour réaliser un programme pour le robot mBot.

1. [Retour au début]()


## Televersement
- téléverser
- télécharger
- transférer
- connecter
- mode direct
- bascule


Pour tester ton programme, tu dois le téléverser dans le **robot mBot**. Pour cela :

:::info
🔧 1. Si ce n'est pas encore fait, cliquer sur **Basculer vers mLink** puis sur le commutateur de mode pour basculer en mode **Téléverser**.
![mode mLink](https://brocq-dandachi.fr/bots/mblock_09.png)
<br>2. Cliquer sur le bouton **Connecter**<br>
![Connecter](https://brocq-dandachi.fr/bots/mblock_12.png)
<br>3. Cliquer sur le bouton **Connecter** de la fenêtre qui s'est ouverte. Tu obtiens dès lors deux nouveaux boutons : le bouton **Déconnecter** et surtout le bouton **Télécharger** qui te permettra de téléverser ton programme dans le robot mBot.<br>
![Connecter et Télécharger](https://brocq-dandachi.fr/bots/mblock_13.png)
:::

Tu sais comment téléverser ton programme. Si tu as des messages d'erreur rendant impossible le téléversement, demande-moi de t'aider via le menu [Pourquoi mon programme ne se téléverse pas ?](#Pb_Televersement) et suis bien attentivement toutes les explications.

1. [Retour au début]()





## Pb_Televersement

Tu n'arrives pas à téléverser ton programme. Plusieurs raisons sont possibles.

Es-tu prêt à effectuer les vérifications ?
1. [Oui](Verification 1)

## Verification 1
- cable USB
- voisin
- ordinateur

**1ère vérification :** Le câble USB est-il bien branché à ton PC ?

Le câble USB côté USB-A doit être branché sur ton PC. 

:::info
🔧 Vérifie qu'il est bien branché sur ton PC et non sur le PC de tes voisins.
:::
Arrives-tu maintenant à téléverser ton programme ?

1. [Oui](Pb_Televersement_OK)
2. [Non](Verification 2)


## Verification 2
- port USB-B
- port RJ 45
- capteurs
- infrarouge
- ultrason

**2ème vérification :** Le câble USB est-il branché au bon endroit sur le robot ?

Le port du câble USB côté robot est un port USB-B.
Mais sur le robot, il y a également 4 ports RJ 45 pour connecter les capteurs et actionneurs (les ports 2 et 3 sont déjà occupés pour les capteurs infrarouges et ultrasons).
Si tu n'as pas fait attention, tu as peut-être positionné le câble USB dans l'un des 2 ports RJ 45 non occupés. Un grand classique !
:::info
🔧 Branche le câble dans le port USB-B du robot.<br>
![Branchement dans port USB-B](https://brocq-dandachi.fr/bots/mblock_15.png)
:::

Arrives-tu maintenant à téléverser ton programme ?

1. [Oui](Pb_Televersement_OK)
2. [Non](Verification 3)

## Verification 3
- sous tension
- ON/OFF
- batterie
- DEL

**3ème vérification :** Le robot mBot est-il sous tension ?

Pour téléverser le programme, il est bien évidemment nécessaire que le **robot mBot** soit sous tension. 

:::warning
⚠️ **Attention**, quand le robot est branché par son câble USB à un PC, sur le robot, une DEL (soit en rouge ou soit en vert) est constamment allumée.
Cela **ne signifie pas** que le robot est sous tension.
Cette DEL n'est qu'un témoin de charge. Si la DEL est verte, la batterie du robot est rechargée, si la DEL est rouge, la batterie est en cours de de charge.

D'autres DEL s'allument quand le robot est sous tension.
:::

:::info
🔧 Vérifie que le **bouton ON/OFF** est bien sur la **position ON**.<br> 
![Position ON/OFF](https://brocq-dandachi.fr/bots/mblock_16.png)
:::
Arrives-tu maintenant à téléverser ton programme ?

1. [Oui](Pb_Televersement_OK)
2. [Non](Verification 4)

## Verification 4
- mLink 2
- logiciel
- windows

**4ème vérification :** Le logiciel mLink2 est-il ouvert ?

Le **logiciel mLink 2** est nécessaire pour permettre le téléversement d'un programme dans le **robot mBot**. Il était donc nécessaire de l'ouvrir **AVANT** de commencer à programmer. 

:::info
🔧 Vérifie dans la barre des tâches de Windows s'il est ouvert. 

Si ce n'est pas le cas :
1. Enregistre ton programme en suivant la [procédure d'Enregistrement de fichiers](#Enregistrer_Fichier).
2. Fermer **mBlock** en fermant l'onglet correspondant. Attention à ne pas fermer ton navigateur, sinon tu me fermeras aussi !
3. Ouvre **mLink2** via l'outil de recherches de Windows.
![Ouvrir mLinkk2](https://brocq-dandachi.fr/bots/mblock_11.png)
4. Ouvre ton programme enregistré en suivant la [procédure d'Ouverture de fichiers](#Ouvrir_Fichier).
5. Réessaye de téléverser. 
:::
Arrives-tu maintenant à téléverser ton programme ?

1. [Oui](Pb_Televersement_OK)
2. [Non](Verification 5)

## Verification 5
- bloc
- gris
- démarrage
- connecter

**5ème vérification :** Le bloc de démarrage est-il présent dans le programme ?

Ton programme commence par un bloc de démarrage. Selon le mode d'utilisation, il va falloir sélectionner et joindre à ton programme le bon bloc de démarrage.

:::info
🔧 Vérifie que le **bloc Lorsque le mBot démarre** est bien joint à ton programme. 
![Bloc dé démarrage](https://brocq-dandachi.fr/bots/mblock_07.png)
<br>S'il est grisé, tu vas l'activer en réalisant les deux actions suivantes :
![Commutateur en direct](https://brocq-dandachi.fr/bots/mblock_08.png)
<br>1. Si ce n'est pas encore fait, cliquer sur **Basculer vers mLink** .
2. passer en mode Téléversement en cliquant sur le **commutateur de mode**. Le bouton **Téléverser** est alors activé. 
![mode mLink](https://brocq-dandachi.fr/bots/mblock_09.png)


:::
Arrives-tu maintenant à téléverser ton programme ?

1. [Oui](Pb_Televersement_OK)
2. [Non](Verification 6)

## Verification 6
- professeur


Si et **seulement si** tu as bien fait toutes les vérifications proposées, il ne te reste plus qu'à appeler ton professeur :-1: 

1. [Retour au début]()

## Pb_Televersement_OK

Félicitations :+1: Tu as été capable de résoudre ton problème en toute autonomie.

Place maintenant à tes tests.