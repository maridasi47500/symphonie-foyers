Symphonie Foyers

Un réseau de foyers où chaque ligne de code devient une note. Dirigée par un chef d’orchestre.

---

L’idée

Il y a un réseau de foyers.  
Certains sont musiciens, d’autres pas.  
Peu importe : dans chaque foyer, on programme en Symfony ou en PHP pour faire du développement web.

Chaque utilisateur est rattaché à un pays.  
Ton code, tes commits, tes bugs, c’est ta façon de faire jouer ton pays dans l’orchestre.

Au-dessus de tout ça, il y a un compositeur. Un chef d’orchestre.  
C’est lui qui décide :

Quand les gens se parlent
Ce que les gens font dans leur métier
Ce que les gens publient sur Facebook et les réseaux sociaux
Quelles rumeurs circulent

Ces rumeurs ne s’arrêtent pas au foyer.  
Elles montent. Jusqu’au bureau oval virtuel.  
Jusqu’au bureau virtuel du président de n’importe quel pays.

Toutes ces voix, tous ces gestes, toutes ces publications, orchestrés ensemble, ça forme une grande symphonie.

---

Ce que fait l’app

Symphonie Foyers transforme le dev web en expérience collaborative et narrative.

Foyers
Crée ou rejoins un foyer. Musicien ou pas, tout le monde code.
Stack imposée : Symfony / PHP pour le web.
Chaque foyer a son activité, son ambiance, son rythme.

Pays
Chaque user est lié à un pays.
L’activité de ton foyer alimente la "partition" de ton pays.
Classements, stats, identité nationale basée sur le code produit.

Le Chef d’Orchestre
Rôle spécial qui orchestre le réseau.
Il décide quand les gens se parlent, ce qu’ils font, ce qu’ils publient.
Il lance des événements, des consignes métier, des rumeurs.

Rumeurs & Bureaux Virtuels
Les rumeurs naissent dans les foyers.
Elles se propagent via le réseau social interne.
Si elles montent assez haut, elles arrivent dans un bureau oval virtuel ou dans le bureau présidentiel d’un pays.
Le chef d’orchestre peut les valider en "décrets" qui changent les règles du jeu.

La Symphonie
Chaque action devient une note.
Visualisation en temps réel de l’activité globale : plus ça bouge, plus la symphonie est riche.
Écoute la symphonie de ton foyer, de ton pays, ou du monde entier.

---

Fonctionnalités
| Module | Description |
| **Foyers** | Espaces de travail collaboratifs. Code, chat, partage de snippets Symfony/PHP |
| **Pays** | Profil national basé sur l’activité des users. Classement et événements par pays |
| **Orchestration** | Le chef d’orchestre crée des scénarios, impose des thèmes, déclenche des interactions |
| **Réseau Social** | Posts, commentaires, partages. Tout est influencé par l’orchestration |
| **Bureaux Virtuels** | Bureau oval et bureaux présidentiels qui reçoivent les rumeurs les plus fortes |
| **Visualiseur Symphonie** | Génération audio/visuelle de l’activité en direct |
---

Installation
git clone https://github.com/tonuser/symphonie-foyers.git
cd symphonie-foyers
composer install
symfony console doctrine:database:create
symfony console doctrine:migrations:migrate
symfony server:start
Stack technique

Backend : Symfony 7, PHP 8.3, PostgreSQL
Frontend : Stimulus + Turbo + Tailwind
Temps réel : Mercure pour la propagation des événements et de la musique live
Audio : http://Tone.js pour générer la symphonie à partir des actions users

---

Rôles

Développeur : Tu codes, tu discutes, tu publies. Tu fais vivre ton foyer et ton pays.  
Chef d’Orchestre : Tu diriges. Tu lances les événements, tu contrôles le tempo, tu décides ce qui monte au sommet.  
Président Virtuel : Rôle optionnel. Tu reçois les rumeurs majeures et tu valides les décrets qui affectent tous les foyers.

---

Philosophie

> Ici, programmer n’est pas solitaire.  
> Chaque commit est une note, chaque conversation une mesure, chaque rumeur un crescendo.  
> Et quand tout s’aligne, ça devient une symphonie.

---

Contribuer

Tu veux ajouter un instrument, un type d’événement, un nouveau bureau ?  
Ouvre une PR. 

Règle unique : tout doit pouvoir être orchestré. Si le chef d’orchestre ne peut pas le diriger, ça ne rentre pas.

---

"Dans Symphonie Foyers, on ne code pas seul. On joue ensemble."
