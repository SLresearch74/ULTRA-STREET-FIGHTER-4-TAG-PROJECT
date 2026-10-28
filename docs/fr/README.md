[English](../../README.txt) · [Langues](../README.md)

# USF4 TAG! — Installation et utilisation

**Pré-alpha v0.1 · Version 0.1.0 · Français**

## Avant de commencer

Il vous faut votre propre installation Steam d'**Ultra Street Fighter IV**, sous Windows, avec **PowerShell 5.1** et **.NET Framework 4.7.2 ou supérieur**. Setup vérifie le build Steam pris en charge et les fichiers originaux nécessaires. Une connexion Internet est requise si la version testée de Simp n'est pas déjà installée.

Il s'agit d'une pré-alpha de combat à un personnage, avec **42 personnages**. Le jeu en équipe/tag reste séparé ; **Hugo et Hakan sont reportés**. La réduction supplémentaire de **50%** de l'étourdissement s'applique actuellement uniquement en **Training Ultra standard hors ligne**.

Les boutons du lanceur sont en anglais : leurs libellés exacts sont conservés ci-dessous. Les noms de personnages et de coups suivent le document anglais.

## Installer

1. Quittez USF4 et Simp normalement. **Extrayez le ZIP complet** dans un dossier.
2. Exécutez **USF4TAG-PreAlpha-0.1.0-Setup.exe**.
3. Si demandé, choisissez le dossier du jeu Steam contenant **SSFIV.exe**.
4. Cliquez sur **Install Pre-Alpha** et attendez **Installation complete**.

Setup installe le mod et configure automatiquement la version testée de Simp. Il réutilise une copie installée identique ou la télécharge et la vérifie depuis sa source. Si le téléchargement est indisponible, vous pouvez sélectionner une copie testée existante ou annuler. Une autre version déjà installée est préservée, sans écrasement. Le raccourci du bureau reste utilisable après suppression de l'installateur téléchargé.

## Jouer

1. Ouvrez **USF4 TAG Pre-Alpha** sur le bureau et cliquez sur **Launch USF4**.
2. Attendez au **menu principal** du jeu, avant d'entrer en Training.
3. Revenez au lanceur et cliquez sur **Load Pre-Alpha**.
4. Dans Simp, sélectionnez **tag_pre_v0100** puis cliquez sur **Launch**.
5. Gardez le lanceur ouvert jusqu'à la fenêtre **Patching complete**.
6. Revenez au jeu et entrez en **Training Ultra standard**. Utilisez les personnages Ultra standard, plutôt qu'Omega ou des éditions antérieures.

La règle d'étourdissement Training démarre automatiquement après le patch. Touchez avec le launcher de votre personnage et maintenez **Haut** pour poursuivre dans les airs. Commencez la chaîne normale aérienne avec un **léger ou un moyen** ; un fort la termine. Voir [les modifications complètes des 42 personnages](ROSTER_CHANGES.md) pour les launchers, commandes et exceptions.

## USF4 normal

Quittez normalement USF4 et Simp. Choisissez **Play Normal USF4** ou lancez une nouvelle session Steam avec Simp fermé. Les fichiers originaux et sauvegardes sont conservés.

## Mises à jour et bugs

- **Manage → Check for updates :** télécharge et vérifie un installateur publié plus récent si vous choisissez de mettre à jour. Fermez normalement USF4 et Simp avant installation.
- **Manage → Open logs :** ouvre les rapports locaux d'erreur et d'opération.
- **Manage → Report a bug :** présente un aperçu du diagnostic puis ouvre une issue GitHub préremplie. Relisez et envoyez-la sur GitHub. Les fichiers et journaux bruts ne sont pas téléversés automatiquement.

## Réparation et suppression

Fermez USF4 et Simp, puis utilisez **Manage → Repair installation** ou **Manage → Remove Pre-Alpha**. Les réparations et mises à jour gérées conservent des copies de récupération. Les fichiers étrangers ou modifiés sont préservés et peuvent nécessiter votre intervention.

## Contenu et assistance

Le paquet contient l'installateur, les instructions, les [changements du roster](ROSTER_CHANGES.md), les traductions, **CREDITS.txt**, **THIRD_PARTY_NOTICES.txt**, **LICENSE.txt** et les sommes de contrôle **SHA256SUMS.txt**. L'installateur contient le lanceur permanent, le runtime et les patchs de combat. Le jeu et l'exécutable Simp ne sont pas inclus.

[Projet GitHub](https://github.com/SLresearch74/ULTRA-STREET-FIGHTER-4-TAG-PROJECT) · [Signaler un problème](https://github.com/SLresearch74/ULTRA-STREET-FIGHTER-4-TAG-PROJECT/issues)
