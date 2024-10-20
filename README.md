# TP2 - HAI913I - Analyse du Couplage des Classes et Identification de Modules

## Description

Cette application permet d'analyser du code source Java, de générer un graphe de couplage pondéré entre les classes et d'identifier des modules fortement couplés au sein d'une application. L'application produit également des statistiques sur les relations entre classes, ainsi qu'une visualisation graphique des résultats sous forme de fichiers `.dot` et `.png`.

## Prérequis

Avant d'utiliser cette application, assurez-vous d'avoir installé les éléments suivants :

- **Java 11** ou une version plus récente
- **Eclipse IDE** (ou tout autre IDE compatible)
- **Graphviz** (pour la génération et la visualisation des fichiers `.dot` et `.png`).

### Installation de Graphviz
sudo apt-get install graphviz


## Installation

### 1. Décompression du projet

Téléchargez et décompressez l'archive du projet.

### 2. Ouvrir le projet

Ouvrez le projet dans Eclipse ou tout autre IDE compatible avec Java. 

## Utilisation

### 1. Démarrage de l'application

- Ouvrez le fichier `ASTParse.java`.
- Modifiez la variable `directoryPath` à la ligne 62 pour spécifier le chemin du répertoire contenant le code source Java à analyser.
- Modifiez également la variable `outputDotFilePath` à la ligne 65 pour définir le chemin où les fichiers de sortie seront enregistrés.

Exemple : `/home/utilisateur/eclipse-workspace/tp2hai913/src/main/java/tp2hai913/tp2hai913/classAanalyser`

(Remplacez la partie `/home/utilisateur/eclipse-workspace` par votre propre chemin).

- Exécutez le fichier `ASTParse` en fonction de votre configuration.


### 2. Génération le graphe de couplage

- Un fichier `.dot` et un fichier`.png` sont générés automatiquement lors de l'execution. Ils seront situés dans le répertoire que vous avez spécifié dans outputDotFilePath.

Exemple : `/home/utilisateur/eclipse-workspace/tp2hai913/src/main/java/tp2hai913/tp2hai913/classAanalyser`

- Rafraîchissez le répertoire correspondant aux classes à analysé pour voir les fichiers générés. Le fichier `.png` contient une représentation visuelle du graphe de couplage entre les classes.

### 3. Visualisation du graphe

- Pour visualiser le fichier `.png`, double-cliquez dessus. Vous pouvez également utiliser n'importe quel visualiseur d'images pour ouvrir et zoomer sur le fichier généré.

### 4. Affichage des résultats

- Les différents résultats sont affichés dans le terminal lors de l'exécution.
## Auteurs

- Alexandre SAR




