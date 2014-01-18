Cet exercice vise à ajouter une deuxième page JQueryMobile dans le fichier base/multipage.html pour pouvoir faire une navigation entre 2 pages définies dans un seul fichier html.
Cela reprend le mécanisme de Multi-Page template structure de Jquery Mobile : http://demos.jquerymobile.com/1.4.0/pages/#Multi-pagetemplatestructure
 
Pré-requis
----------------
Une connexion internet

Installation
----------------
Télécharger le fichier ([base/multipage.html](https://github.com/pilerou/masterdosi-jquerymobile-multipagestemplates/blob/master/base/multipage.html)) en local
 
Vérification de l'installation
----------------
Ouvrir le fichier dans un navigateur. La page s'affiche.

Développement
----------------
Le lien "page 2" ne fonctionne pas. C'est normal la page associée à `#page_deux` n'existe pas. Il convient donc de la rajouter dans le même fichier à la place de 
`<!-- Ajouter une deuxième page JQueryMobile ici -->`

La page 2 devra disposer d'un lien permettant de revenir à l'accueil

Correction
----------------
La correction est visible en suivant le lien : ([correction/multipage.html](https://github.com/pilerou/masterdosi-jquerymobile-multipagestemplates/blob/master/correction/multipage.html))
