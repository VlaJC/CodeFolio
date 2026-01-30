Ce Projet est un site permettant d'écrire en ligne et de sauvegarder en local.
Le Code a été testé et fonctionne sur Chrome et Edge

Les objectifs:
- Définir les fonctions "ouvrir", "sauvegarder", "effacer"
- Mettre en place la sauvegarde localement et non en ligne

NB:
J'ai fait vérifié le code par L'IA et il m'a fait rajouter plusieurs choses:

Coté UX 
- Les "show status" pour les fonctions afin de montrer que tout s'est bien passé et inversèment
- Le "setTimeout" permet de retarder l'execution d'une fonction afin que les messages soient temporaires
- Le "event.target.value = '';" permet d'ouvrir le fichier plusieurs avec ou sans modification

Coté JS
- "CreateObjectURL" et "RevokeObjectURL" afin d'utiliser puis de libérer la mémoire après le télechargement
- "Blob" ou "Binary Large Object" qui transforme le texte JS en fichier téléchargeable