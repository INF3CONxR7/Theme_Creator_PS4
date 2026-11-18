<p align="center">
  <img src="logo.png" alt="Logo de PS4 Theme Creator" width="128">
</p>

<h1 align="center">PS4 Theme Creator</h1>

<p align="center">
  Créez vos thèmes PS4 dans un éditeur sombre et moderne :<br>
  fonds, icônes, sons et couleurs, avec l’aperçu en direct de l’écran d’accueil et de l’écran des fonctions.
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
- [Menus et raccourcis](#menus-et-raccourcis)
- [Mises à jour et Discord](#mises-à-jour-et-discord)
- [En cas de problème](#en-cas-de-problème)
- [Désinstaller](#désinstaller)
- [Compiler depuis les sources](#compiler-depuis-les-sources)
- [Crédits et licences](#crédits-et-licences)
- [Support](#support)
- [English](#english)

## Fonctionnalités

- **Aperçu en direct, en 1920 × 1080** : l’**écran d’accueil** (barre du haut, Boutique, jeu sélectionné, tuiles de
  contenu, bandeau « Nouveautés ») et l’**écran des fonctions** (rangée des 11 fonctions, avatar, tuiles du bas), tels
  que la console les affichera. Chaque modification apparaît aussitôt ; qualité de l’aperçu en 1080p ou 720p.
- **Arrière-plans** : une image en PNG ou JPG (1920 × 1080) pour l’écran d’accueil et une pour l’écran des fonctions.
- **Couleur du thème** : la couleur que la PS4 affiche dans ses Paramètres et ses autres menus, parmi ses huit
  couleurs : bleu (par défaut), rose, rouge, bleu marine, gris foncé, or, bleu acier clair ou violet. Elle ne change
  pas les arrière-plans.
- **Icônes** : un clic sur une icône, une tuile, l’image de la Boutique, le jeu sélectionné ou l’avatar de l’aperçu
  pour choisir son image PNG, à la même taille et à la même place. **Effacer** vide d’un clic les icônes de contenu ou
  les icônes de fonction, ou retire les images de fond.
- **Sons** : musique de fond (activable), musique principale par glisser-déposer, et effets sonores **Défilement**,
  **Sélection** et **Annulation** (un par un, ou les trois d’un coup avec **Tout importer**).
- **Couleurs** : police, ombre de police, focus, et voiles de l’accueil, des fonctions et des titres, avec leur
  opacité ; **Réinitialiser** rend les valeurs d’origine.
- **Thème** : titre affiché sur la console, **Title ID** (`CUSA99999` : 4 lettres et 5 chiffres, mis en majuscules
  tout seul) et icône 512 × 512. **Créer le thème** vérifie le titre et le Title ID, signale les erreurs sous les
  champs, puis enregistre le thème dans le dossier de sortie.
- **Projets** `.ps4theme` : nouveau projet, ouverture, projets récents, enregistrement, import d’un thème existant,
  export des aperçus en PNG, ouverture du dossier du projet dans l’Explorateur.
- **Interface soignée** : thèmes **sombre**, clair ou celui de Windows, et **4 langues** : français, anglais,
  espagnol et italien.
- **Mises à jour automatiques signées** et **activité Discord** (voir [Mises à jour et Discord](#mises-à-jour-et-discord)).

## Configuration requise

- Un PC sous **Windows 10 ou 11 (64 bits)**.
- Rien d’autre à installer : le runtime .NET est inclus dans l’exécutable.
- Pour l’activité Discord (facultative) : l’application Discord ouverte sur le même PC.

## Installation

1. Ouvrez la [dernière version](https://github.com/INF3CONxR7/Theme_Creator_PS4/releases/latest) et téléchargez
   **`ThemeCreatorPS4-win-x64.zip`**. Le fichier `.zip.sig` sert au programme de mise à jour : inutile de le
   télécharger pour utiliser l’application.
2. Extrayez l’archive à l’endroit de votre choix, par exemple dans Documents ou sur le Bureau : vous obtenez le dossier
   **`ThemeCreatorPS4-win-x64`**. Gardez-le tel quel, avec ses sous-dossiers : l’application en a besoin pour se mettre
   à jour.

   ```
   ThemeCreatorPS4-win-x64\
   ├─ PS4 Theme Creator.exe                   l’application
   ├─ Licenses\
   │  ├─ Inter.LICENSE.txt                    licence de la police Inter
   │  └─ JetBrainsMono.LICENSE.txt            licence de la police JetBrains Mono
   └─ Updater\
      └─ PS4 Theme Creator Update.exe         programme de mise à jour
   ```
3. Lancez **`PS4 Theme Creator.exe`** depuis ce dossier. La langue se change dans **Paramètres > Langue**, le thème
   dans **Paramètres > Thème**.

> **Windows SmartScreen** : l’exécutable n’est pas signé Authenticode, Windows peut donc afficher « Windows a protégé
> votre ordinateur ». Cliquez sur **Informations complémentaires**, puis sur **Exécuter quand même**.

## Utilisation

1. **Commencer** : **Fichier > Nouveau projet** (Ctrl+N), ou **Fichier > Ouvrir un projet…** (Ctrl+O) pour reprendre
   un fichier `.ps4theme`. **Importer un thème…** part d’un thème existant.
2. **Arrière-plan** (panneau de droite) : choisissez l’image d’accueil et l’image des fonctions, et la couleur du
   thème. Les onglets **Écran d’accueil** et **Écran des fonctions**, au-dessus de l’aperçu, basculent entre les deux
   écrans.
3. **Icônes** : cliquez sur un élément de l’aperçu pour lui donner votre image PNG.
4. **Son** : musique de fond, musique principale et effets sonores.
5. **Police et voiles** (sous l’aperçu) : un clic sur une couleur ouvre le sélecteur de couleur.
6. **Thème** (en bas du panneau) : titre, Title ID et icône.
7. **Enregistrer** : Ctrl+S, ou **Fichier > Enregistrer** ; **Enregistrer sous…** (Ctrl+Maj+S) écrit une copie
   ailleurs. **Créer le thème** (en bas à droite) vérifie le thème et l’enregistre dans le dossier de sortie
   (`Documents\PS4 Theme Creator` par défaut, à changer dans **Paramètres > Dossier de sortie…**) ; **Dossier du
   projet** l’ouvre dans l’Explorateur.

**Fichier > Exporter** enregistre l’aperçu de l’écran d’accueil ou de l’écran des fonctions en image PNG, pour le
partager. **Paramètres > Outils externes…** retient l’outil de fabrication de paquets PS4 de votre choix.

## Menus et raccourcis

| Menu | Contenu |
|---|---|
| **Fichier** | Nouveau projet · Ouvrir un projet… · Projets récents · Enregistrer · Enregistrer sous… · Importer un thème… · Exporter (aperçu de l’écran d’accueil ou de l’écran des fonctions en PNG) · Ouvrir le dossier du projet · Quitter |
| **Paramètres** | Langue (français, anglais, espagnol, italien) · Thème (sombre, clair, système) · Qualité de l’aperçu (1080p, 720p) · Dossier de sortie… · Outils externes… · Raccourcis clavier · Vérifier les mises à jour · À propos de PS4 Theme Creator |

| Raccourci | Action |
|---|---|
| Ctrl+N | Nouveau projet |
| Ctrl+O | Ouvrir un projet |
| Ctrl+S | Enregistrer |
| Ctrl+Maj+S | Enregistrer sous |
| Échap | Fermer le menu ouvert |
| Alt+F4 | Quitter |

Les raccourcis fonctionnent menus fermés ; **Paramètres > Raccourcis clavier** les rappelle tous.

## Mises à jour et Discord

- **Mises à jour** : l’application vérifie sur GitHub si une nouvelle version est publiée, et le propose : un clic sur
  **Installer**, et elle se ferme, installe la mise à jour, puis se relance. Vous pouvez aussi vérifier à tout moment
  avec **Paramètres > Vérifier les mises à jour**. Chaque version est **signée** : une version dont la signature est
  absente ou invalide est refusée. Aucun droit d’administrateur n’est demandé, sauf si l’application est installée
  dans un dossier protégé comme `C:\Program Files`.
- **Activité Discord** : si Discord est ouvert sur le PC, votre profil indique que vous utilisez PS4 Theme Creator et
  ce que vous faites (création, enregistrement…), sans jamais montrer le nom ni le chemin de vos fichiers. Elle
  n’existe que dans une version où l’application Discord de PS4 Theme Creator est renseignée, et se désactive dans
  **Paramètres > Outils externes…**.

## En cas de problème

| Problème | Solution |
|---|---|
| « Windows a protégé votre ordinateur » | Voir la note **Windows SmartScreen** de l’[installation](#installation). |
| La mise à jour ne démarre pas, ou le programme de mise à jour est introuvable | Vérifiez que les dossiers `Licenses` et `Updater` sont bien à côté de `PS4 Theme Creator.exe` ; sinon, retéléchargez la dernière version. |
| Une mise à jour échoue | Le message en donne la cause, et le lien **Ouvrir le journal** de la fenêtre de mise à jour le détail (`%LocalAppData%\PS4 Theme Creator\Logs\updates.log`). **Réessayer** recommence ; la version installée n’est jamais abîmée. |
| « Une mise à jour de PS4 Theme Creator est en cours d’installation » au lancement | Attendez la fin de la mise à jour : l’application se relancera toute seule. |
| « Une erreur inattendue s’est produite » | L’application continue : enregistrez votre projet, puis redémarrez-la si quelque chose ne fonctionne plus. Pour signaler le problème, joignez le **détail technique** affiché sous le message. |

Une question ? Rejoignez le [serveur Discord](https://discord.gg/TbFYvqsh5z).

## Désinstaller

Supprimez le dossier de l’application. Elle garde aussi, pour votre compte Windows :

| Emplacement | Contenu |
|---|---|
| `HKEY_CURRENT_USER\Software\ThemeCreatorPS4` | Réglages : langue, thème, qualité de l’aperçu, dossier de sortie, outil externe, projets récents, fenêtre, activité Discord. |
| `%LocalAppData%\PS4 Theme Creator` | Journal des mises à jour (`Logs\updates.log`). |

Vous pouvez supprimer cette clé et ce dossier. Vos projets `.ps4theme` et vos thèmes créés (par défaut dans
`Documents\PS4 Theme Creator`) restent là où vous les avez enregistrés.

## Compiler depuis les sources

Il faut Windows 10 ou 11 et le **SDK .NET 10** (Visual Studio 2026, ou la ligne de commande `dotnet`). Aucun paquet
NuGet : tout est écrit avec .NET et Windows Forms.

1. Ouvrez la solution **`Theme_Creator_PS4.slnx`** dans Visual Studio, ou, depuis son dossier :

   ```powershell
   dotnet build Theme_Creator_PS4.slnx -c Debug
   ```

   L’application compilée est dans `bin\Debug\net10.0-windows\` (`PS4 Theme Creator.exe`), avec son dossier
   `Licenses\` et, en Debug seulement, le programme de mise à jour dans `Updater\`.
2. Pour publier une version (deux exécutables autonomes, paquet `.zip` signé et notes de version) :

   ```powershell
   powershell -NoProfile -ExecutionPolicy Bypass -File .\build\Publish-Release.ps1
   ```

   La clé de signature se crée une fois avec `build\New-SigningKey.ps1`. Mode d’emploi complet :
   `build\README-MISES-A-JOUR.md`.

## Crédits et licences

- **PS4 Theme Creator** : Copyright © 2026 INF3C7ONxR7. Tous droits réservés.
- **Polices Inter** (© 2016 The Inter Project Authors) et **JetBrains Mono** (© 2020 The JetBrains Mono Project
  Authors) : sous licence [SIL Open Font License 1.1](https://openfontlicense.org/), embarquées dans l’application ;
  leurs licences sont livrées dans `Licenses\`.
- **Icônes [Lucide](https://lucide.dev/)** (© Lucide Contributors ; en partie © Cole Bemis, Feather) : sous licence
  [ISC](https://lucide.dev/license), dessinées par l’application.

Projet non officiel, sans lien avec Sony. PlayStation et PS4 sont des marques de Sony Interactive Entertainment.
Discord et GitHub sont des marques de leurs propriétaires.

## Support

- Discord : [discord.gg/TbFYvqsh5z](https://discord.gg/TbFYvqsh5z)
- GitHub : [INF3CONxR7/Theme_Creator_PS4](https://github.com/INF3CONxR7/Theme_Creator_PS4) (versions et signalement
  des problèmes)

Développé par **INF3C7ONxR7**. Copyright © 2026 INF3C7ONxR7.

---

## English

**PS4 Theme Creator** is a dark, modern editor for **PS4 themes**: backgrounds, icons, sounds and colours, with a
**live 1920 × 1080 preview** of the home screen and the function screen, exactly as the console will show them. The
interface is available in French, English, Spanish and Italian (**Settings > Language**), with dark, light or system
theme.

**Requirements**: Windows 10 or 11 (64-bit) PC, nothing else to install (the .NET runtime is included).

**Features**: live preview of the home screen (top bar, Store, selected game, content tiles, “What’s New” banner) and
of the function screen (row of 11 functions, avatar, bottom tiles), in 1080p or 720p · home and function background
images (PNG or JPG, 1920 × 1080) · theme colour: the colour the PS4 shows in its Settings and other menus, one of its
eight colours (blue by default, pink, red, navy, dark gray, gold, light steel blue or purple), which does not change
the backgrounds · click any icon, tile, Store image, selected game or avatar of the preview to replace it with your
PNG; **Clear** empties the content or function icons, or removes the background images · background music, main music
(drag and drop) and the **Scroll**, **Select** and **Cancel** sound effects (**Import all** picks the three at once) ·
font, font shadow, focus and home, function and title veil colours, with opacity · theme title, **Title ID**
(`CUSA99999`: 4 letters and 5 digits) and 512 × 512 icon · **Create theme** checks the title and Title ID, then saves
the theme to the output folder · `.ps4theme` project files (new, open, recent projects, save, import an existing
theme, export the previews as PNG) · signed automatic updates and Discord activity.

**Install**: download **`ThemeCreatorPS4-win-x64.zip`** from the
[latest release](https://github.com/INF3CONxR7/Theme_Creator_PS4/releases/latest) (not the `.sig` file, used by the
updater), extract it wherever you like to get the **`ThemeCreatorPS4-win-x64`** folder, keep it as is with its
`Licenses` and `Updater` subfolders, and run **`PS4 Theme Creator.exe`**. The executable is not Authenticode-signed,
so Windows SmartScreen may show “Windows protected your PC”: click **More info**, then **Run anyway**.

**Usage**: start a new project (Ctrl+N) or open a `.ps4theme` file (Ctrl+O), pick the backgrounds and the theme colour
in the right-hand panel, click the preview to replace icons, add the music and sound effects, set the colours under
the preview and the title, Title ID and icon at the bottom of the panel, then save (Ctrl+S; Ctrl+Shift+S: save as) and
click **Create theme**. **File > Export** saves either preview as a PNG image.

**Updates**: the app checks GitHub for new versions; you can also check at any time from **Settings > Check for
updates**. Every release is signed; unsigned or tampered releases are refused. No administrator rights are needed,
unless the app is installed in a protected folder such as `C:\Program Files`. When Discord is running on the same PC,
your profile shows that you are using PS4 Theme Creator (never your file names or paths).

**Uninstall**: delete the app folder. Settings are in `HKEY_CURRENT_USER\Software\ThemeCreatorPS4`, the update log in
`%LocalAppData%\PS4 Theme Creator`.

**Build from source**: Windows 10 or 11 and the .NET 10 SDK (Visual Studio 2026 or the `dotnet` CLI), no NuGet
package: open `Theme_Creator_PS4.slnx`, or run `dotnet build Theme_Creator_PS4.slnx -c Debug`. Releases are published
with `build\Publish-Release.ps1` (see `build\README-MISES-A-JOUR.md`, in French).

**Credits and licenses**: Inter and JetBrains Mono fonts under the SIL Open Font License 1.1 · Lucide icons under the
ISC license. Unofficial project, not affiliated with Sony.

**Support**: [Discord](https://discord.gg/TbFYvqsh5z) · [GitHub](https://github.com/INF3CONxR7/Theme_Creator_PS4) ·
Copyright © 2026 **INF3C7ONxR7**.
