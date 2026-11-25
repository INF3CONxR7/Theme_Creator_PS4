<p align="center">
  <img src="https://zupimages.net/up/26/47/9otr.png" alt="Logo de PS4 Theme Creator" width="128">
</p>

<h1 align="center">PS4 Theme Creator</h1>

<p align="center">
  Créez vos thèmes PS4 dans un éditeur sombre et moderne :<br>
  fonds, icônes, sons et couleurs, avec l’aperçu en direct de l’écran d’accueil et de l’écran des fonctions,<br>
  puis fabriquez le paquet <code>.pkg</code> du thème, prêt à installer sur la console.
</p>

<p align="center">
  <a href="https://github.com/INF3CONxR7/Theme_Creator_PS4/releases/latest"><img src="https://img.shields.io/github/v/release/INF3CONxR7/Theme_Creator_PS4?label=t%C3%A9l%C3%A9charger&color=6E9BFF" alt="Télécharger"></a>
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?logo=windows&logoColor=white" alt="Windows 10 et 11">
  <a href="https://discord.gg/TbFYvqsh5z"><img src="https://img.shields.io/badge/Discord-rejoindre-5865F2?logo=discord&logoColor=white" alt="Serveur Discord"></a>
</p>

---

## Sommaire

- [Fonctionnalités](#fonctionnalités)
- [Configuration requise](#configuration-requise)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Installer un thème sur la PS4](#installer-un-thème-sur-la-ps4)
- [Menus et raccourcis](#menus-et-raccourcis)
- [Mises à jour et Discord](#mises-à-jour-et-discord)
- [En cas de problème](#en-cas-de-problème)
- [Désinstaller](#désinstaller)
- [Crédits et licences](#crédits-et-licences)
- [Support](#support)
- [English](#english)

## Fonctionnalités

- **Aperçu en direct, en 1920 × 1080** : l’**écran d’accueil** (barre du haut, Boutique, jeu sélectionné, tuiles de
  contenu, bandeau « Nouveautés ») et l’**écran des fonctions** (rangée des 11 fonctions, avatar, tuiles du bas), tels
  que la console les affichera, avec le défilement des applications (molette, flèches, clavier ou glisser) et la
  transition de la PS4 entre les deux écrans. Chaque modification apparaît aussitôt ; qualité de l’aperçu en 1080p ou
  720p.

- **Arrière-plans** : une image PNG ou JPG pour l’écran d’accueil et une pour l’écran des fonctions (1920 × 1080 ; une
  image d’une autre taille est recadrée toute seule), et une **barre des fonctions** facultative (1920 × 164), que la
  console affiche en haut de l’écran quand une application reprend après le mode repos.

- **Couleur du thème** : la couleur que la PS4 affiche dans ses Paramètres et ses autres menus, parmi ses huit
  couleurs : bleu (par défaut), rose, rouge, bleu marine, gris foncé, or, bleu acier clair ou violet. Elle ne change
  pas les arrière-plans.

- **Icônes** : les **10 icônes de contenu** (Internet, Disque, Galerie, Bibliothèque, En direct de PlayStation,
  Musique, Disque (incrustation), Dossier, Jeu en partage, TV et vidéo) et les **9 icônes de fonction** (Notifications,
  Amis, Communautés, Événements, Messages, Groupe, Trophées, Paramètres, Alimentation), ces dernières chacune avec son
  **halo** : celui que vous choisissez, ou un halo généré à la couleur du focus. Un clic sur une case de l’aperçu, un
  glisser-déposer ou le clic droit pour lui donner votre image PNG. Le « + » de PlayStation Plus, le profil, l’avatar,
  la Boutique et le jeu sélectionné ne sont pas modifiables par un thème PS4 : ils restent dans l’aperçu, marqués
  « non modifiable » au survol. **Effacer** remet les icônes par défaut ou retire les images de fond.

- **Sons** : musique de fond (activable), musique principale (AT9, WAV, MP3, OGG, FLAC, M4A ou WMA) et effets sonores
  **Défilement**, **Sélection** et **Annulation** (les mêmes formats, ou VAG), un par un ou les trois d’un coup avec
  **Tout importer**. À la création du thème, ils sont convertis tout seuls aux formats de la PS4 (ATRAC9 et HE-VAG),
  avec les outils fournis avec l’application. Le volume de la musique est ajusté, et une musique de plus de 4 min est
  raccourcie, avec un fondu de sortie ; un effet sonore trop long pour la PS4 est coupé (environ 0,37 s pour
  **Défilement**, 0,65 s pour **Sélection** et **Annulation**).

- **Police et voiles** : couleurs de la police, de l’ombre de la police, du focus et des voiles de l’accueil, des
  fonctions et des titres, avec l’opacité de l’ombre et des voiles ; **Réinitialiser** rend les valeurs d’origine.

- **Thème** : titre et fournisseur affichés sur la console, **Title ID** tiré au hasard pour chaque projet (4 lettres
  et 5 chiffres, par exemple `KQRA48213`), **Content ID** dont les 4 derniers chiffres, la révision, augmentent tout
  seuls quand vous recréez un thème modifié, et icône 512 × 512.

- **Créer le thème** fabrique le **paquet `.pkg`** du thème, installable avec GoldHEN : vérification du projet (les
  erreurs s’affichent sous les champs), progression étape par étape, annulation possible, contrôles du paquet
  fabriqué, puis compte rendu. Voir [Installer un thème sur la PS4](#installer-un-thème-sur-la-ps4).

- **Projets** `.ps4theme` : chaque projet est un dossier qui garde une copie de vos fichiers ; **enregistrement quand
  vous le décidez** (Ctrl+S), avec un « * » après le titre du thème tant que des modifications ne sont pas
  enregistrées, et la proposition de les enregistrer avant de fermer ; projets récents ; ouverture par double-clic sur
  un `.ps4theme` ; import des fichiers d’un thème existant ; export des aperçus en PNG.

- **Interface soignée** : thèmes **sombre**, clair ou celui de Windows, et **4 langues** : français, anglais,
  espagnol et italien.

- **Mises à jour automatiques signées** et **activité Discord** (voir [Mises à jour et Discord](#mises-à-jour-et-discord)).

## Configuration requise

- Un PC sous **Windows 10 ou 11 (64 bits)**.

- Rien d’autre à installer : le runtime .NET est inclus dans l’exécutable, et les outils de conversion des sons
  (at9tool, vagconv2 et ffmpeg) sont fournis avec l’application.

- Pour installer vos thèmes : une **PS4 avec GoldHEN** et une clé USB (voir
  [Installer un thème sur la PS4](#installer-un-thème-sur-la-ps4)).

- Pour l’activité Discord (facultative) : l’application Discord ouverte sur le même PC.

## Installation

1. Ouvrez la [dernière version](https://github.com/INF3CONxR7/Theme_Creator_PS4/releases/latest) et téléchargez
   **`ThemeCreatorPS4-win-x64.zip`** (environ 180 Mo). Le fichier `.zip.sig` sert au programme de mise à jour :
   inutile de le télécharger pour utiliser l’application.

2. Extrayez l’archive à l’endroit de votre choix, par exemple dans Documents ou sur le Bureau : vous obtenez le dossier
   **`ThemeCreatorPS4-win-x64`**. Gardez-le tel quel, avec tous ses fichiers et sous-dossiers : l’application en a
   besoin pour fabriquer les thèmes et pour se mettre à jour.

   ```
   ThemeCreatorPS4-win-x64\
   ├─ PS4 Theme Creator.exe                   l’application
   ├─ LibOrbisPkg.dll                         fabrication et vérification des paquets .pkg
   ├─ Licenses\
   │  ├─ Inter.LICENSE.txt                    licence de la police Inter
   │  ├─ JetBrainsMono.LICENSE.txt            licence de la police JetBrains Mono
   │  ├─ LibOrbisPkg\                         licences (LGPL 3.0 et GPL 3.0), notice et sources de LibOrbisPkg
   │  └─ FFmpeg\                              licence (GPL 3.0) et notes de FFmpeg, avec l’adresse de ses sources
   ├─ Tools\
   │  ├─ ATRAC9\                              at9tool.exe, encodeur de la musique (avec vcruntime140.dll)
   │  ├─ HEVAG\                               vagconv2.exe, encodeur des effets sonores
   │  └─ FFmpeg\                              ffmpeg.exe, décodage, rééchantillonnage et volume des sons
   └─ Updater\
      └─ PS4 Theme Creator Update.exe         programme de mise à jour
   ```

3. Lancez **`PS4 Theme Creator.exe`** depuis ce dossier. La langue se change dans **Paramètres > Langue**, le thème
   dans **Paramètres > Thème**.

> **Windows SmartScreen** : l’exécutable n’est pas signé Authenticode, Windows peut donc afficher « Windows a protégé
> votre ordinateur ». Cliquez sur **Informations complémentaires**, puis sur **Exécuter quand même**.

## Utilisation

1. **Commencer** : **Fichier > Nouveau projet** (Ctrl+N) demande le nom du thème et crée son dossier dans le dossier
   de sortie (`Documents\PS4 Theme Creator` par défaut, à changer dans **Paramètres > Dossier de sortie…**).
   **Fichier > Ouvrir un projet…** (Ctrl+O) reprend un fichier `.ps4theme`. Vos modifications ne s’enregistrent pas
   toutes seules : enregistrez-les avec Ctrl+S (voir **Enregistrer**, sous ces étapes).

2. **Arrière-plan** (panneau de droite) : l’image d’accueil et l’image des fonctions (obligatoires), la barre des
   fonctions (facultative) et la couleur du thème. Les onglets **Écran d’accueil** et **Écran des fonctions**,
   au-dessus de l’aperçu (ou Ctrl+1 et Ctrl+2), basculent entre les deux écrans.

3. **Icônes** : cliquez sur une case de l’aperçu, ou déposez-y une image PNG. Le clic droit propose aussi **Remettre
   l’image par défaut** et, sur une icône de fonction, **Choisir le halo…** et **Halo automatique** (qui retire le
   halo choisi : un halo est alors généré à la création du thème) ; une icône de fonction et son halo
   (`nom_glow.png`) peuvent être déposés ensemble. **Disque** et **Disque (incrustation)** vont par paire : fournissez
   les deux, sinon la PS4 garde les deux icônes par défaut.

4. **Son** : activez ou non la **musique de fond**, choisissez la musique principale (clic ou glisser-déposer) et les
   effets sonores (**Choisir**, ou **Tout importer**, qui les répartit d’après leurs noms).

5. **Police et voiles** (sous l’aperçu) : un clic sur une couleur ouvre le sélecteur de couleur. L’ombre de la police,
   toujours visible dans l’aperçu, ne s’affiche sur la console que si **Paramètres > Thèmes > Ombre portée du texte** y
   est sur « Standard ».

6. **Thème** (en bas du panneau) : titre, fournisseur, Title ID, icône (PNG, obligatoire) et Content ID.

7. **Créer le thème** (en bas à droite, ou Ctrl+Entrée) : les modifications du projet sont d’abord enregistrées, comme
   avec Ctrl+S (si l’enregistrement échoue, le thème n’est pas créé) ; le paquet est écrit dans le dossier du projet,
   sous `build\pkg\<CONTENT_ID>-A0000-V0100.pkg` ; ceux des révisions précédentes sont rangés dans `build\pkg\archive`.
   Le compte rendu propose **Afficher le paquet** et **Installer sur la PS4…**.

**Enregistrer** : vos modifications ne s’enregistrent jamais toutes seules. **Fichier > Enregistrer** (Ctrl+S) écrit
le projet, copie dans son dossier les images et les sons choisis ou importés depuis le dernier enregistrement, et en
retire les copies devenues inutiles. D’ici là, le dossier du projet reste tel qu’il a été enregistré (c’est ce que
montrent **Dossier du projet** et **Fichier > Ouvrir le dossier du projet**), et l’aperçu montre vos fichiers là où
vous les avez pris. Tant que le projet diffère de sa dernière version enregistrée, un « * » suit le titre du thème,
affiché dans la barre de titre après le nom de l’application (dans la barre des tâches, il le précède). Si
l’enregistrement échoue, le message nomme le fichier en cause, rien ne change dans le dossier du projet et les
modifications restent à enregistrer. L’application n’enregistre d’elle-même que dans deux cas : après
**Créer le thème**, pour noter dans le projet la révision du thème créé (le projet venait d’être enregistré) ; et à
l’ouverture d’un projet d’une version précédente de l’application, rangé une fois pour toutes (ses fichiers passent
dans le sous-dossier `sources\`).

**Modifications non enregistrées** : avant de fermer la fenêtre, d’ouvrir ou de créer un autre projet, ou d’installer
une mise à jour, l’application propose de les enregistrer : **Enregistrer**, **Ne pas enregistrer** (le projet reste
tel qu’il a été enregistré) ou **Annuler**. Quand Windows s’arrête ou ferme la session, rien n’est enregistré à votre
place : l’application retient l’arrêt et pose la même question.

**Fichier > Enregistrer sous…** (Ctrl+Maj+S) copie le projet sous un autre nom, avec ses propres identifiants : la
copie est un autre thème. Elle reçoit le projet tel que vous le voyez, modifications non enregistrées comprises, et
s’ouvre à sa place ; l’original reste tel qu’il a été enregistré. **Fichier > Importer un thème…** reprend dans le
projet ouvert les images et les sons d’un dossier (projet, thème déjà créé, ou pack d’images et de sons reconnus
d’après leurs noms). **Fichier > Exporter** enregistre l’aperçu de l’écran d’accueil ou de l’écran des fonctions en
image PNG, pour le partager.
**Paramètres > Outils externes…** permet d’utiliser un autre at9tool, vagconv2 ou ffmpeg que ceux fournis.

## Installer un thème sur la PS4

Le paquet créé est un paquet non signé (« fake PKG ») : il s’installe sur une PS4 avec **GoldHEN**, sans signature de
Sony. Il faut aussi une clé USB formatée en **exFAT** ou **FAT32**, avec une table de partition **MBR**.

1. Copiez le fichier **`.pkg`** à la **racine** de la clé USB, pas dans un dossier.
2. Branchez la clé sur la PS4 et chargez **GoldHEN**.
3. Installez le paquet avec le **Package Installer** de GoldHEN.
4. Ouvrez **Paramètres > Thèmes > Sélectionner un thème**, choisissez votre thème, puis **Appliquer**.

Un thème installé ainsi revient au thème par défaut après chaque redémarrage complet de la console : réappliquez-le une
fois GoldHEN relancé, ou utilisez le mode repos avec l’option **Enable Rest Mode Support** de GoldHEN. Un thème modifié
puis recréé reçoit une nouvelle révision, donc un nouveau Content ID et un nouveau nom de paquet.

Ces étapes sont aussi dans l’application : **Paramètres > Installer un thème sur la PS4…**, ou **Installer sur la
PS4…** dans le compte rendu de **Créer le thème**.

> **À savoir** : aucun thème fabriqué avec LibOrbisPkg n’a encore été signalé publiquement comme testé sur une
> console : les paquets créés ainsi restent à valider sur votre PS4.

## Menus et raccourcis

| Menu | Contenu |
|---|---|
| **Fichier** | Nouveau projet · Ouvrir un projet… · Projets récents (les 10 derniers) · Enregistrer · Enregistrer sous… · Importer un thème… · Exporter (aperçu de l’écran d’accueil ou de l’écran des fonctions en PNG) · Ouvrir le dossier du projet · Quitter |
| **Paramètres** | Langue (français, anglais, espagnol, italien) · Thème (sombre, clair, système) · Qualité de l’aperçu (1080p, 720p) · Dossier de sortie… · Outils externes… · Raccourcis clavier · Installer un thème sur la PS4… · Vérifier les mises à jour · À propos de PS4 Theme Creator |

En bas de la fenêtre : **Effacer** (Icônes de contenu, Icônes de fonction, Fond d’accueil, Fond des fonctions),
**Dossier du projet**, qui l’ouvre dans l’Explorateur, et **Créer le thème**.

| Raccourci | Action |
|---|---|
| Ctrl+N | Nouveau projet |
| Ctrl+O | Ouvrir un projet |
| Ctrl+S | Enregistrer |
| Ctrl+Maj+S | Enregistrer sous |
| Ctrl+1 / Ctrl+2 | Écran d’accueil / Écran des fonctions |
| ← / → | Faire défiler les applications (aperçu sélectionné) |
| Début / Fin | Aller à la première ou à la dernière application |
| Menu ou Maj+F10 | Options des cases de l’aperçu (image, halo, image par défaut) |
| Ctrl+Entrée | Créer le thème |
| Alt, F10 ou Alt+F | Ouvrir le menu Fichier |
| Alt+P | Ouvrir le menu Paramètres |
| Échap | Fermer un menu ou une fenêtre |
| Alt+F4 | Quitter |

**Paramètres > Raccourcis clavier** les rappelle tous.

## Mises à jour et Discord

- **Mises à jour** : quelques secondes après l’ouverture, l’application vérifie sur GitHub si une nouvelle version est
  publiée. Si c’est le cas, aucune fenêtre ne s’ouvre : le badge de version, à droite de la barre de titre, passe en
  bleu. Un clic sur ce badge (ou **Paramètres > Vérifier les mises à jour**, à tout moment) ouvre « Mise à jour
  disponible » ; un clic sur **Installer**, et l’application se ferme, installe la mise à jour, puis se relance (si le
  projet ouvert a des modifications non enregistrées, elle propose d’abord de les enregistrer). La vérification au
  démarrage se coupe dans **Paramètres > Outils externes…**. Chaque version est **signée** : une version dont la
  signature est absente ou invalide est refusée. Une mise à jour télécharge la version entière (environ 180 Mo). Aucun
  droit d’administrateur n’est demandé, sauf si l’application est installée dans un dossier protégé comme
  `C:\Program Files`.

- **Activité Discord** (activée par défaut) : si Discord est ouvert sur le PC, votre profil indique que vous utilisez
  PS4 Theme Creator, ce que vous faites (édition, enregistrement, création du thème…) et le **titre du thème** en
  cours, avec un bouton « Rejoindre le serveur Discord ». Le nom et le chemin de vos fichiers ne sont jamais montrés.
  Elle se désactive dans **Paramètres > Outils externes…** (« Afficher mon activité sur Discord »).

## En cas de problème

| Problème | Solution |
|---|---|
| « Windows a protégé votre ordinateur » | Voir la note **Windows SmartScreen** de l’[installation](#installation). |
| « Impossible d’enregistrer le projet » | Le message nomme le fichier en cause : un fichier choisi a été déplacé, renommé ou supprimé depuis (ou se trouve sur une clé débranchée), un fichier est ouvert dans un autre programme, ou le dossier du projet est protégé en écriture ou sur un disque plein. Rien n’a changé dans le dossier du projet : rechoisissez le fichier ou retirez-le, puis enregistrez de nouveau, ou enregistrez une copie ailleurs avec **Enregistrer sous…**. |
| Windows indique que PS4 Theme Creator empêche l’arrêt (« Le projet a des modifications non enregistrées… ») | Choisissez **Annuler** sur cet écran de Windows, puis répondez à la question de l’application (**Enregistrer** ou **Ne pas enregistrer**) : elle se ferme, et vous pouvez relancer l’arrêt. |
| **Créer le thème** signale un outil introuvable, ou que `LibOrbisPkg.dll` est absente | Un fichier de l’application manque, souvent mis en quarantaine par un antivirus : retéléchargez la dernière version et gardez tous les fichiers de l’archive. Pour un outil, vous pouvez aussi indiquer son emplacement dans **Paramètres > Outils externes…**. |
| « at9tool.exe » ne démarre pas (code 0xC0000135) | Il lui manque la bibliothèque Visual C++ `vcruntime140.dll` : remettez-la dans `Tools\ATRAC9\` (en retéléchargeant la dernière version) ou installez « Microsoft Visual C++ Redistributable » (x64). |
| Les outils de Sony ne savent pas lire le chemin du projet (« ★ », « 東京 »…) | Renommez ou déplacez le dossier du projet pour que son chemin n’ait aucun de ces caractères, puis recréez le thème. |
| Un effet sonore `.vag` est refusé | Un fichier HE-VAG qui ne convient pas tel quel à la PS4 (pas en 48 kHz, en boucle ou trop long) ne peut pas être converti : choisissez sa source (WAV, MP3…), que l’application convertit et raccourcit au besoin. |
| CE-37695-0 à l’installation sur la PS4 | Le paquet a été installé comme une application (marqueur de thème absent) : recréez le thème avec la dernière version de PS4 Theme Creator, dont les contrôles vérifient ce marqueur, puis réinstallez le paquet. |
| « Données endommagées » sur la PS4 | Empreintes du paquet invalides, ou fichier hors spécification : recopiez le `.pkg` sur la clé USB (la copie a pu être abîmée), ou recréez le thème, dont les contrôles vérifient les empreintes, puis réinstallez-le. |
| CE-33676-5 sur la PS4 | Contenu non détecté : chargez GoldHEN, ou réinstallez le paquet. |
| Le thème redevient le thème par défaut | C’est normal après un redémarrage complet : réappliquez-le une fois GoldHEN relancé, ou utilisez le mode repos (**Enable Rest Mode Support**). |
| La mise à jour ne démarre pas, ou le programme de mise à jour est introuvable | Vérifiez que le dossier `Updater` est bien à côté de `PS4 Theme Creator.exe`, avec les autres fichiers de l’archive ; sinon, retéléchargez la dernière version. |
| Une mise à jour échoue | Le message en donne la cause, et le lien **Ouvrir le journal** de la fenêtre de mise à jour le détail (`%LocalAppData%\PS4 Theme Creator\Logs\updates.log`). **Réessayer**, quand il est proposé, recommence. En cas d’échec, la version installée est remise en place ; si elle ne peut pas l’être entièrement, le message indique le dossier où ses fichiers sont conservés, et la mise à jour suivante la répare. |
| « Une mise à jour de PS4 Theme Creator est en cours d’installation » au lancement | Attendez la fin de la mise à jour : l’application se relancera toute seule. Si la fenêtre de mise à jour affiche une erreur, fermez-la, puis relancez l’application. |
| « Une erreur inattendue s’est produite » | L’application continue : enregistrez votre projet, puis redémarrez-la si quelque chose ne fonctionne plus. Pour signaler le problème, joignez le **détail technique** affiché sous le message. |

Une question ? Rejoignez le [serveur Discord](https://discord.gg/TbFYvqsh5z).

## Désinstaller

Supprimez le dossier de l’application. Elle garde aussi, pour votre compte Windows :

| Emplacement | Contenu |
|---|---|
| `HKEY_CURRENT_USER\Software\ThemeCreatorPS4` | Réglages : langue, thème, qualité de l’aperçu, dossier de sortie, chemins des outils externes, projets récents, fenêtre, activité Discord, vérification des mises à jour au démarrage. |
| `HKEY_CURRENT_USER\Software\Classes\ThemeCreatorPS4.Project` et `HKEY_CURRENT_USER\Software\Classes\.ps4theme` | Ouverture des projets `.ps4theme` par double-clic. |
| `%LocalAppData%\PS4 Theme Creator` | Journal des mises à jour (`Logs\updates.log`). |

Vous pouvez supprimer ces clés et ce dossier. Vos projets restent là où ils sont : un dossier par projet (par défaut
dans `Documents\PS4 Theme Creator\<nom du thème>\`), avec ses paquets créés dans `build\pkg\`.

## Crédits et licences

- **PS4 Theme Creator** : Copyright © 2026 INF3C7ONxR7. Tous droits réservés.
- **Polices Inter** (© 2016 The Inter Project Authors) et **JetBrains Mono** (© 2020 The JetBrains Mono Project
  Authors) : sous licence [SIL Open Font License 1.1](https://openfontlicense.org/), embarquées dans l’application ;
  leurs licences sont livrées dans `Licenses\`.
- **Icônes [Lucide](https://lucide.dev/)** (© Lucide Contributors, sous licence [ISC](https://lucide.dev/license) ;
  en partie © Cole Bemis, Feather, sous licence MIT), dessinées par l’application.
- **[LibOrbisPkg](https://github.com/maxton/LibOrbisPkg)** (Copyright © 2018-2020 Maxton) : sous licence
  [GNU LGPL 3.0](https://www.gnu.org/licenses/lgpl-3.0.html), dans une copie adaptée aux thèmes ; elle fabrique et
  vérifie les paquets `.pkg`. Elle reste une bibliothèque distincte (`LibOrbisPkg.dll`), que vous pouvez remplacer par
  une version modifiée ; ses licences, sa notice (origine et modifications) et ses sources sont livrées dans
  `Licenses\LibOrbisPkg\`.
- **[FFmpeg](https://ffmpeg.org/)** (build Windows de [gyan.dev](https://www.gyan.dev/ffmpeg/builds/)) : sous licence
  [GNU GPL 3.0](https://www.gnu.org/licenses/gpl-3.0.html), programme distinct fourni dans `Tools\FFmpeg\` ; sa
  licence et ses notes, avec l’adresse de ses sources, sont livrées dans `Licenses\FFmpeg\`.
- **at9tool** et **vagconv2** : outils du SDK PlayStation, © Sony Interactive Entertainment Inc., fournis dans
  `Tools\`.

Projet non officiel, sans lien avec Sony. PlayStation et PS4 sont des marques de Sony Interactive Entertainment.
FFmpeg est une marque de Fabrice Bellard. Discord et GitHub sont des marques de leurs propriétaires.

## Support

- Discord : [discord.gg/TbFYvqsh5z](https://discord.gg/TbFYvqsh5z)
- GitHub : [INF3CONxR7/Theme_Creator_PS4](https://github.com/INF3CONxR7/Theme_Creator_PS4) (versions et signalement
  des problèmes)

Développé par **INF3C7ONxR7**. Copyright © 2026 INF3C7ONxR7.

---

## English

**PS4 Theme Creator** is a dark, modern editor for **PS4 themes**: backgrounds, icons, sounds and colors, with a
**live 1920 × 1080 preview** of the home screen and the function screen, exactly as the console will show them. It
then builds the theme’s **`.pkg` package**, ready to install on a PS4 with GoldHEN. The interface is available in
French, English, Spanish and Italian (**Settings > Language**), with dark, light or system theme.

**Requirements**: Windows 10 or 11 (64-bit) PC, nothing else to install (the .NET runtime and the sound conversion
tools are included). To install your themes: a PS4 running GoldHEN and a USB drive.

**Features**: live preview of the home screen (top bar, Store, selected game, content tiles, “What’s New” banner) and
of the function screen (row of 11 functions, avatar, bottom tiles), with app scrolling and the PS4 screen transition,
in 1080p or 720p · home and function screen images (PNG or JPG, 1920 × 1080; other sizes are cropped and resized to
fit) and an optional function area bar (1920 × 164) · theme color: the color the PS4 shows in its Settings and other
menus, one of its eight colors (blue by default, pink, red, navy, dark gray, gold, light steel blue or purple), which
does not change the backgrounds · the 10 content icons, and the 9 function icons with their glows (chosen, or generated in the focus
color): click, drop a PNG or right-click a slot of the preview; the PlayStation Plus “+”, profile, avatar, Store and
selected game cannot be changed by a PS4 theme and stay as preview only; **Clear** restores the default icons or
removes the backgrounds · a **Background music** switch, the main music (AT9, WAV, MP3, OGG, FLAC, M4A or WMA) and
the **Scroll**, **Select** and **Cancel** sound effects (same formats or VAG; **Import all** picks the three at once),
converted automatically to ATRAC9 and HE-VAG with the bundled tools; the music volume is adjusted and music longer
than 4 min is shortened with a fade-out; sound effects longer than the PS4 allows are cut (about 0.37 s for Scroll,
0.65 s for Select and Cancel) ·
font, font shadow, focus and home, functions and titles overlay colors, with opacity for the shadow and the overlays
(**Reset** restores them) · theme title and provider, random **Title ID** (4 letters and 5 digits, for example
`KQRA48213`), **Content ID** whose last 4 digits (the revision) go up when you build a modified theme again, and
512 × 512 icon · **Create theme** checks the project, builds the `.pkg` with progress and cancel, checks the package,
then shows a report · `.ps4theme` projects, each one a folder holding a copy of your files, saved when you choose
(Ctrl+S), with a “*” after the theme title while changes are unsaved and an offer to save them before closing ·
signed automatic updates and Discord activity.

**Install**: download **`ThemeCreatorPS4-win-x64.zip`** (about 180 MB) from the
[latest release](https://github.com/INF3CONxR7/Theme_Creator_PS4/releases/latest) (not the `.sig` file, used by the
updater), extract it wherever you like to get the **`ThemeCreatorPS4-win-x64`** folder, keep it as is with all its
files (`LibOrbisPkg.dll`, the `Licenses`, `Tools` and `Updater` subfolders), and run **`PS4 Theme Creator.exe`**. The
executable is not Authenticode-signed, so Windows SmartScreen may show “Windows protected your PC”: click
**More info**, then **Run anyway**.

**Usage**: create a project (**File > New project**, Ctrl+N: it asks for the theme name and creates its folder in the
output folder, `Documents\PS4 Theme Creator` by default) or open a `.ps4theme` file (Ctrl+O). Save your changes
with Ctrl+S (see **Saving**). Pick the backgrounds and the theme color in the right-hand panel, click or drop images on
the preview, add the music and sound effects, set the colors under the preview and the title, provider, Title ID,
icon and Content ID at the bottom of the panel, then click **Create theme** (Ctrl+Enter). The package is written to
`build\pkg\` inside the project folder. **File > Export** saves either preview as a PNG image; **Settings > External
tools…** lets you use another at9tool, vagconv2 or ffmpeg.

**Saving**: your changes are never saved on their own. **File > Save** (Ctrl+S) writes the project, copies the images
and sounds chosen or imported since the last save into its folder and removes the copies no longer used; until then
the project folder stays as last saved, and that is what **Project folder** and **File > Open the project folder**
show. While the project differs from its last saved version, a “*” follows the theme title shown in the title bar (it
comes first in the taskbar). Before closing the window, opening or creating another project or installing an update,
the app offers to save the changes: **Save**, **Don’t save** (the project stays as last saved) or **Cancel**; when
Windows shuts down, nothing is saved for you and the app holds the shutdown to ask. If saving fails, the message names
the file at fault and nothing in the project folder changes. **Create theme** saves the project first and does not
run if the save fails; the built revision is then recorded in the project on its own. **File > Save as…**
(Ctrl+Shift+S) copies the project under another name with its own identifiers, unsaved changes included, and opens
the copy; the original stays as last saved. A project from an earlier version of the app is tidied up once when
opened (its files move into the `sources\` subfolder).

**Installing a theme on the PS4**: you need a PS4 running **GoldHEN** (the package is an unsigned fake PKG) and a USB
drive formatted as exFAT or FAT32 with an MBR partition table. Copy the `.pkg` to the root of the drive, load GoldHEN,
install the package with GoldHEN’s **Package Installer**, then open **Settings > Themes > Select Theme**, choose your
theme and **Apply**. After a full restart the console goes back to the default theme: apply it again once GoldHEN is
loaded, or use rest mode with GoldHEN’s **Enable Rest Mode Support**. The same steps are in the app (**Settings >
Install a theme on the PS4…**). No theme built with LibOrbisPkg has been publicly reported as tested on a console yet.

**Updates**: a few seconds after it opens, the app checks GitHub for a new version (this can be turned off in
**Settings > External tools…**). When one is found, no window opens: the version badge in the title bar turns blue.
Click it (or **Settings > Check for updates**, at any time) to see the new version and **Install** it (if the open
project has unsaved changes, the app first offers to save them). Every release is signed; unsigned or tampered
releases are refused. No administrator rights are needed, unless the app is installed in a protected folder such as
`C:\Program Files`. When the Discord app is running on the same PC, your profile shows that you are using PS4 Theme
Creator, what you are doing (editing, saving, creating the theme) and the theme title, never your file names or
paths. This is on by default; turn it off in **Settings > External tools…** (“Show my activity on Discord”).

**Troubleshooting**: if **Create theme** reports a missing tool or a missing `LibOrbisPkg.dll`, a file of the app is
missing (often quarantined by an antivirus): download the latest release again and keep all the files of the
archive, or set the tool’s location in **Settings > External tools…**. If at9tool.exe does not start (code
0xC0000135), `vcruntime140.dll` is missing from `Tools\ATRAC9\`: download the latest release again or install the
“Microsoft Visual C++ Redistributable” (x64). If saving fails, the message names the file at fault (a chosen file
moved or deleted since, a file open in another program, a write-protected folder…): nothing in the project folder has
changed; choose the file again or remove it, then save again, or save a copy elsewhere with **Save as…**. If Windows
says that PS4 Theme Creator is preventing shutdown, click **Cancel** there and answer the app’s question (**Save** or
**Don’t save**): the app closes and you can shut down again. If an update fails, **Open the log** in the update
window shows the details (`%LocalAppData%\PS4 Theme Creator\Logs\updates.log`).

**Uninstall**: delete the app folder. You can also delete what it keeps for your Windows account: its settings in
`HKEY_CURRENT_USER\Software\ThemeCreatorPS4`, the `.ps4theme` file association in
`HKEY_CURRENT_USER\Software\Classes\ThemeCreatorPS4.Project` and `HKEY_CURRENT_USER\Software\Classes\.ps4theme` (only
these two keys), and the update log in `%LocalAppData%\PS4 Theme Creator`. Your projects stay where they are.

**Credits and licenses**: Inter and JetBrains Mono fonts under the SIL Open Font License 1.1 · Lucide icons under the
ISC license (Feather portions under the MIT license) · [LibOrbisPkg](https://github.com/maxton/LibOrbisPkg)
(Copyright © 2018-2020 Maxton) under the GNU LGPL 3.0, as a separate, replaceable `LibOrbisPkg.dll`, with its
licenses, notice and source code in `Licenses\LibOrbisPkg\` · [FFmpeg](https://ffmpeg.org/) (gyan.dev Windows build)
under the GNU GPL 3.0, with its license and source code address in `Licenses\FFmpeg\` · at9tool and vagconv2,
PlayStation SDK tools, © Sony Interactive Entertainment Inc. Unofficial project, not affiliated with Sony.

**Support**: [Discord](https://discord.gg/TbFYvqsh5z) · [GitHub](https://github.com/INF3CONxR7/Theme_Creator_PS4) ·
Copyright © 2026 **INF3C7ONxR7**.
