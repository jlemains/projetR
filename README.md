# Projet R 

*Auteurs : Thomas FONTAINE, Dan GOLDMAN, Juliette LEMAINS et Nicolas ROBIN*

Vous trouverez dans ce repository Git, l'ensemble fichiers permettant de répondre à l'énoncé donné en cours d'Outils et Méthodologie.

Voici la liste des fichiers :
- Un fichier "Projet.Rproj" à lancer pour se trouver dans le bon répertoire.
- Un fichier "Parametres.R" : ce fichier répertorie les différentes variables d'environnement, il inclut le chargement des bases de données de travail et également les variables nécessaires aux réponses des différentes questions.
- Un fichier "Projet.R" : ce fichier répertorie l'ensemble des fonctions qui répondent à chacune des questions. Nous avons choisis de créer une fonction par question, de manière à rendre le code plus structuré et faciliter le travail en groupe.
- Un fichier "Projet.Rmd" : ce fichier construit le rapport final grace à la librairie R-Markdown. Il génère un fichier .html.
- Un fichier .zip du fichier "correspondance-code-insee-code-postal.csv" téléchargé à partir du site https://public.opendatasoft.com/explore/dataset/correspondance-code-insee-code-postal.
- Une image "structure.png" : cette image est appelée dans le RMarkdown afin d'illustrer la structure de nos bases de données.
- **Un fichier chemin_a_renseigner.txt : c'est dans ce fichier que vous indiquerez le chemin du dossier dans lequel se trouve les données. Il doit absolument être completé avant de lancer l'exécution du code. (un exemple y est déjà)**
- Un fichier "Projet.html" : ce fichier est la sortie du R-Markdown. Ce fichier est considéré comme le **rapport final** de notre projet. Le rapport a aussi été téléchargé sur RPubs. Il peut être consulté simplement en cliquant sur ce lien : https://rpubs.com/databisons/457573

**Comment utiliser notre code ?**
- Pour utiliser ce code, vous pouvez soit choisir de le rapatrier manuellement en cliquant sur le bouton "Clone or download" de la page du projet et télécharger l'ensemble des fichiers de ce repository, soit créer un projet GitHub à partir de R-Studio en indiquant le "Repository URL" Git suivant : https://github.com/jlemains/projetR.
- N'oubliez pas de décompresser le fichier "correspondance-code-insee-code-postal.zip" qui vous permettra de récupérer le fichier csv. Placez-le ensuite dans le repertoire de vos données (renseignés dans le fichier texte "chemin_a_renseigner.txt"")

**Comment exécuter notre code ?**
Pour exécuter notre code, vous pouvez procéder de deux manières différentes. Vous pouvez l'exécuter : 
- **via "projet.R"** : Ouvrez le fichier "Parametres.R" et assurez-vous que la variable **execution_avec_RMarkdown** est égale à **FALSE** (l.19).  Placez-vous ensuite dans le code du fichier « Projet.R » avant de sélectionner et d'exécuter la totalité du code.
- **via "Projet.Rmd"** : Vous n'avez qu'à ouvrir le fichier "Parametres.R" et affecter la variable **execution_avec_RMarkdown** à **TRUE** (l.19). Après ça vous pourrez cliquer sur **Knit** dans le markdown et le markdown sera généré automatiquement en html. Pour cette partie **n'oubliez pas de préciser votre répertoire de données dans le fichier texte "chemin_a_renseigner.txt"**.

**Avertissement** : Le projet permet un téléchargement automatisé des librairies manquntes. Par conséquent, **il est obligatoire d'être connecté à internet lors de l'exécution des scripts**.

**Configuration minimale recommandée** : 
- Mémoire vive : 8 Go de RAM.
- Version de R : 3.5.2.
- Environnement de développement : RStudio version 1.1.463.
