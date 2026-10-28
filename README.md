# Music Overlay

**Votre Spotify, accessible en un raccourci.**

Music Overlay permet de rechercher une musique, gérer la lecture et consulter la file d’attente sans revenir dans la fenêtre principale de Spotify. Son interface sombre et épurée s’affiche au-dessus de vos applications, avec un fond dont vous pouvez régler la transparence.

**Windows 64 bits · Spotify Premium · Version de test**

## Télécharger

### [⬇ Télécharger la dernière version](https://github.com/TOMDER3/music-overlay/releases/latest)

Sur la page de téléchargement, ouvrez **Assets** si nécessaire et choisissez **MusicOverlay-Installer.exe**. C’est le seul fichier nécessaire. Les fichiers « Source code » ne servent pas à installer l’overlay.

[Installation](#installation) · [Premiers pas](#premiers-pas) · [Raccourcis et clics](#raccourcis-et-clics) · [Mises à jour](#mises-à-jour) · [FAQ](#faq)

## Ce que vous pouvez faire

- **Contrôler Spotify** : lecture, pause, morceau précédent ou suivant, déplacement dans le morceau, volume et mode muet.
- **Rechercher** des titres, artistes, albums et playlists.
- **Retrouver vos raccourcis récents** dans « Tout », synchronisés avec l’accueil Spotify.
- **Parcourir les albums et playlists**, consulter leurs morceaux et lancer leur lecture avec « Lire tout ».
- **Gérer vos titres likés** : ajouter un morceau avec **+**, ou retirer son like avec **✓**, depuis le lecteur ou les résultats de recherche.
- **Utiliser la file « À suivre »** : voir les morceaux à venir, en ajouter, en retirer ou passer directement à l’un d’eux.
- **Découvrir du contenu personnel** avec « Pour toi » et « Podcasts », selon les données et suggestions disponibles pour votre compte.
- **Changer d’appareil Spotify** depuis le menu Appareils du lecteur, parmi ceux disponibles pour votre compte.
- **Personnaliser le fond** dans les paramètres : à **0 %**, il est transparent ; à **100 %**, il devient gris uni.

L’overlay contrôle l’application Spotify : Spotify reste le lecteur qui diffuse le son.

## Installation

### Avant de commencer

- Utilisez **Windows 64 bits** et un **compte Spotify Premium**.
- Installez la **version classique de Spotify** depuis le [téléchargement direct officiel](https://www.spotify.com/download/windows/), plutôt que la version Microsoft Store.
- Demandez au créateur de l’overlay d’**autoriser votre compte Spotify**. Il lui faut votre nom et l’adresse e-mail associée au compte, jamais votre mot de passe.

### Installer l’overlay

1. **Ouvrez Spotify** et connectez votre compte habituel. Lors d’une première installation, laissez-le charger environ une minute.
2. Téléchargez **MusicOverlay-Installer.exe** depuis la [dernière version](https://github.com/TOMDER3/music-overlay/releases/latest).
3. Lancez l’installateur **sans mode administrateur**. Il prépare l’overlay et sa liaison avec Spotify grâce à Spicetify. Spotify peut redémarrer pendant cette étape.
4. Répondez **Oui** à « Lancer automatiquement l’overlay avec Spotify ? » si vous souhaitez le démarrage discret.
5. Dans l’overlay, ouvrez **⚙ Paramètres → Connecter Spotify**, puis autorisez votre propre compte dans le navigateur.
6. Revenez avec **Alt+S**. Le badge **« Overlay : connecté »** dans Spotify confirme que la liaison locale est établie.

**Python n’est pas nécessaire.** Chaque personne utilise son compte et ses propres données Spotify.

## Premiers pas

1. Appuyez sur **Alt+S** pour afficher l’overlay.
2. Cliquez sur la **petite flèche de la barre de recherche** pour ouvrir les catégories. À chaque réouverture, « Tout » affiche les raccourcis de l’accueil Spotify.
3. Saisissez une recherche ou ouvrez une catégorie. Un clic sur un album ou une playlist affiche son contenu ; **Retour** revient à la vue précédente.
4. Cliquez sur un morceau pour le lire, ou sur **Lire tout** pour démarrer un album, une playlist ou les titres likés. Depuis le contenu d’une collection, la lecture se poursuit dans cette collection.
5. Masquez l’overlay avec **Échap** ou **Alt+S** : la musique continue.

Dans le lecteur, le nom du morceau se souligne au survol. Cliquez dessus pour ouvrir son album ; pour un épisode de podcast, cela permet d’accéder à son émission lorsque les informations sont disponibles.

## Raccourcis et clics

### Clavier

| Raccourci | Action |
| --- | --- |
| **Alt+S** | Afficher ou masquer l’overlay. |
| **Échap** | Masquer l’overlay. |
| **Alt+F5** | Redémarrer l’overlay et le réafficher. |
| **Alt+F6** | Réappliquer Spicetify et recharger la liaison avec Spotify. Spotify peut redémarrer. |

### Souris

| Où cliquer ? | Résultat |
| --- | --- |
| **Flèche de la barre de recherche** | Ouvrir ou refermer la fenêtre de recherche. |
| **Engrenage ⚙** | Ouvrir ou refermer les paramètres. |
| **Un clic sur le fond, en dehors des panneaux** | Fermer la recherche et les menus ouverts. Cliquer dans un panneau ne les ferme pas. |
| **Double-clic sur le fond** | Masquer tout l’overlay. |
| **Bouton − en haut à droite** | Masquer l’overlay. |
| **Bouton × en haut à droite** | Quitter l’application. Pour la retrouver, utilisez le raccourci Bureau. |
| **Barre de progression du lecteur** | Aller à un autre moment du morceau. |
| **Icône de haut-parleur** | Couper ou rétablir le son de Spotify. |
| **Icône + ≡ d’un résultat** | Ajouter le morceau à la file, sans interrompre celui en cours. |
| **Un titre dans « À suivre »** | Le lire et passer les morceaux qui le précèdent dans la file. |
| **Poubelle d’un titre dans « À suivre »** | Retirer cette occurrence de la file, sans supprimer le morceau de Spotify ni de vos titres likés. |

Les listes se parcourent avec la molette ou leur barre de défilement grise.

## Retrouver et rouvrir l’application

Le plus simple est d’ouvrir **Music Overlay**, le raccourci créé sur votre **Bureau**, puis d’utiliser **Alt+S** si l’interface est masquée.

Le dossier d’installation est :

`%LOCALAPPDATA%\MusicOverlay`

Vous pouvez coller ce chemin dans la barre d’adresse de l’Explorateur Windows. Dans ce dossier, ouvrez **MusicOverlay.exe** pour relancer l’application.

### Démarrage automatique

Si vous l’avez accepté pendant l’installation, un petit programme de surveillance démarre discrètement avec votre session Windows. **Il attend l’ouverture de Spotify pour lancer l’overlay en arrière-plan.** Utilisez ensuite **Alt+S** pour l’afficher.

## Mises à jour

Dans les paramètres de l’overlay :

**Rechercher les mises à jour → Télécharger la mise à jour → Installer et redémarrer**

Le téléchargement est vérifié avant installation. Votre connexion Spotify, votre clé de liaison, vos réglages et le dernier morceau mémorisé sont conservés.

Vous pouvez aussi télécharger le nouvel installateur depuis [le même lien GitHub](https://github.com/TOMDER3/music-overlay/releases/latest) : il reconnaît une installation existante.

Les modifications arrivent chez vous lorsqu’une nouvelle version est publiée, pas simplement lorsque le créateur modifie son projet sur son PC.

## FAQ

<details>
<summary><strong>Faut-il Spotify Premium ?</strong></summary>

Oui, Premium est nécessaire pour utiliser l’ensemble des commandes de lecture prévues par cette version. Un compte gratuit ne garantit pas le fonctionnement complet.

</details>

<details>
<summary><strong>Pourquoi mon compte doit-il être autorisé avant la première utilisation ?</strong></summary>

Cette distribution utilise une application Spotify en mode développement, réservée aux utilisateurs autorisés. Envoyez au créateur votre nom et l’adresse e-mail associée à votre compte Spotify. Il n’a pas besoin de votre mot de passe.

Lors de « Connecter Spotify », choisissez bien ce même compte.

</details>

<details>
<summary><strong>Dois-je installer Spicetify ou Python moi-même ?</strong></summary>

Python n’est pas nécessaire. L’installateur prépare l’extension Spicetify et installe Spicetify via winget s’il est absent. Si winget est introuvable, l’installateur indique qu’il faut installer ou mettre à jour « App Installer » depuis le Microsoft Store, puis recommencer.

Spicetify sert ici à établir la liaison avec l’application Spotify.

</details>

<details>
<summary><strong>L’overlay fonctionne-t-il si Spotify est fermé ?</strong></summary>

Spotify doit être ouvert pour écouter et contrôler la musique. L’overlay peut conserver l’affichage du dernier morceau, mais cet affichage ne signifie pas que Spotify est connecté ou en cours de lecture.

Avec le démarrage automatique, la surveillance attend Spotify : elle ne lance pas le lecteur Spotify à votre place.

</details>

<details>
<summary><strong>J’ai cliqué sur × et Alt+S ne réouvre plus l’overlay. Que faire ?</strong></summary>

La croix ferme l’application. Ouvrez **Music Overlay** depuis le Bureau, ou **MusicOverlay.exe** dans `%LOCALAPPDATA%\MusicOverlay`.

Pour laisser l’application disponible au clavier, utilisez plutôt **Échap**, **Alt+S**, le bouton **−** ou un double-clic sur le fond.

</details>

<details>
<summary><strong>Le badge « Overlay : connecté » n’apparaît pas. Que vérifier ?</strong></summary>

Ouvrez Spotify classique et Music Overlay, puis laissez-les charger. Vérifiez que vous utilisez le bon compte et que la connexion a été autorisée dans **Paramètres → Connecter Spotify**.

Si la liaison reste absente, utilisez **Alt+F6**. Après une mise à jour de Spotify, Spicetify peut devoir être réappliqué ou mis à jour lui aussi. Si une erreur persiste, transmettez son texte au créateur de l’overlay.

Le badge confirme la liaison locale ; il ne remplace pas la connexion de votre compte dans les paramètres.

</details>

<details>
<summary><strong>Une playlist reste vide ou une commande affiche « accès refusé ». Que faire ?</strong></summary>

Vérifiez votre connexion Internet, le compte Spotify utilisé et son autorisation par le créateur. Rechargez la liaison avec **Alt+F6**, puis rouvrez la playlist.

Certaines playlists nécessitent la liaison Spicetify pour afficher leur contenu. Le message affiché dans l’overlay aide à distinguer un problème d’accès d’une playlist réellement vide.

</details>

<details>
<summary><strong>Pourquoi « Pour toi » ou « Podcasts » propose peu de contenu ?</strong></summary>

Ces catégories dépendent des données disponibles pour votre compte et des suggestions fournies par Spotify. Les podcasts peuvent inclure l’émission en cours, des propositions de l’accueil et les émissions suivies. Elles ne constituent pas un historique complet de toutes vos écoutes.

Vous pouvez également rechercher une émission par son nom dans « Podcasts ».

</details>

<details>
<summary><strong>Que se passe-t-il quand je like ou retire un titre ?</strong></summary>

Le **+** ajoute le morceau à vos titres likés et devient **✓**. Recliquez sur **✓** pour retirer le like. Ces actions modifient vos titres likés sur votre propre compte Spotify.

La poubelle de « À suivre » agit uniquement sur la file d’attente.

</details>

<details>
<summary><strong>Vais-je perdre mon compte ou mes réglages lors d’une mise à jour ?</strong></summary>

Le système de mise à jour conserve les données locales de l’installation existante. Il ne remplace pas votre compte par celui du créateur. Spotify peut toutefois demander une nouvelle autorisation si votre connexion a expiré ou a été révoquée.

</details>

<details>
<summary><strong>Windows affiche un avertissement au téléchargement ou à l’installation.</strong></summary>

Cette version de test n’est pas signée numériquement. Téléchargez uniquement depuis les Releases de ce dépôt. Si Windows bloque le fichier ou si vous avez un doute, contactez le créateur avant de continuer.

</details>

<details>
<summary><strong>Comment signaler un problème ?</strong></summary>

Indiquez ce que vous faisiez, le message affiché, la version de l’overlay visible dans les paramètres et, si utile, une capture d’écran sans information personnelle.

Vous pouvez contacter le créateur ou [ouvrir un ticket](https://github.com/TOMDER3/music-overlay/issues). Ne publiez jamais vos fichiers de session, votre clé locale, votre mot de passe ou un jeton de connexion.

</details>

---

Music Overlay est un projet indépendant pour Windows, non affilié à Spotify. Les licences des dépendances sont incluses dans le paquet d’installation.
