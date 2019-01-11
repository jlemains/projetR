# Projet R 

*Auteurs : Thomas FONTAINE, Dan GOLDMAN, Juliette LEMAINS et Nicolas ROBIN*

Vous trouverez dans ce répertoire plusieurs fichiers permettant de répondre à l'énoncé donné en cours d'Outils et Méthodologie.

Voici la liste des fichiers :
- Un fichier "Projet.Rproj" à lancer pour se trouver dans le bon répertoire.
- Un fichier "Parametres.R" : ce fichier répertorie les différentes variables d'environnement, il inclut le chargement des bases de données de travail et également les variables nécessaires aux réponses des différentes questions.
- Un fichier "Projet.R" : ce fichier répertorie l'ensemble des fonctions qui répondent à chacune des questions. Nous avons choisis de créer une fonction par question, de manière à rendre le code plus structuré et faciliter le travail en groupe.
- Un fichier "Projet.Rmd" : ce fichier construit le rapport final grace à la librairie R-Markdown. Il génère un fichier .html.
- Le fichier "correspondance-code-insee-code-postal.csv" téléchargé à partir du site https://public.opendatasoft.com/explore/dataset/correspondance-code-insee-code-postal. 
- Une image "structure.png" : cette image est appelée dans le RMarkdown afin d'illustrer la structure de nos bases de données.
- **Un fichier chemin_a_renseigner.txt : c'est dans ce fichier que vous indiquerez le chemin du dossier dans lequel se trouve les données. Il doit absolument être completé avant de lancer l'exécution du code. (un exemple y est déjà)**
- Un fichier "Projet.html" : ce fichier est la sortie du R-Markdown. Ce fichier est considéré comme le **rapport final** de notre projet. Le rapport a aussi été téléchargé sur RPubs. Il peut être consulté en cliquant sur ce lien : http://rpubs.com/databisons/457573

**Comment executer notre code ?**
- Préliminaire : Décompresser le fichier "correspondance-code-insee-code-postal.csv" puis le placer dans le repertoire de vos données (renseignés dans chemin_a_renseigner.txt)
Pour exécuter notre code, vous pouvez procéder de deux manières différentes. Vous pouvez l'exécuter : 
- **via "projet.R"** : Si vous souhaitez regarder plus en détail notre code et les différentes executions, vous pouvez dans ce cas vous placer dans le code du fichier "Projet.R" . Avant de sélectionner et d'executer la totalité du code, il faudra vous rendre à la fin du fichier. Vous trouverez dans la partie **"EXECUTION DU CODE"** (l. 644) les appels à chacune des fonctions commentées. Pour évaluer chacune d'elle ou la totalité, vous devrez "décommenter" celles qui vous intéressent. Le fait de pouvoir sélectionner fonction par fonction permet d'examiner les visualisations en détails via RStudio.
- **via "Projet.Rmd"** : Vous n'avez qu'à ouvrir le fichier "Parametres.R" et affecter la variable **execution_avec_RMarkdown** à **TRUE** (l.19). Après ça vous pourrez cliquer sur **Knit** dans le markdown et le markdown sera généré automatiquement en html. Pour cette partie **n'oubliez pas de préciser votre répertoire de données dans le fichier texte "chemin_a_renseigner.txt"**.

