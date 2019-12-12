# nextdom-theme-design / menus multiples

## Description

Ce thème permet de créer un menu de type Hamburger pour naviguer entre les différents écrans de Design.
Son originalité est de proposer 2 menus différents en fonction des besoins de navigation.

## Mise en place

### Prérequis

- Avant toute chose, il vous faut connaitre la résolution d'écran de votre périphérique : Hauteur & Largeur

- Une fois noté, copier le contenu du fichier menu.html et renseigner pour chaque item des menus (ligne li) son nom et le lien vers la page de design souhaitée.

- Il faut ensuite copier le dossier /var/www/html/data/custom/montheme dans le répertoire /data/custom

### Configuration du thème

Pour appliquer ce "thème" à votre design sous NextDom, vous devez effectuer les actions suivantes :

- Créer un nouveau design (ou ouvrir un design existant)

- Clic droit -> Configurer le design

![](../adminLTE/doc/images/configurer_design.png)

- Dans la fenêtre de configuration, remplir la taille et la hauteur (pour un nouveau design)

- Ensuite ajouter un widget texte/html

![](../adminLTE/doc/images/ajouter_widget_text_html.png)

- Clic droit sur le nouveau widget ajouté , puis cliquer sur Paramètres d'affichage:

![](../adminLTE/doc/images/paramètre_widget_text_html.png)

- Dans la fenêtre de paramètrage, remplir comme suit :


&nbsp;
Profondeur : mettre au dernier plan (0)


&nbsp;
Position X et Position Y : mettre 0


&nbsp;
Largeur et Hauteur : adapter à la largeur et hauteur du design


&nbsp;
Transparent : activer la transparence


&nbsp;
Texte : coller le contenu modifié de menu.html

- Le design est terminé, il reste à l'alimenter avec vos équipements !
![](doc/images/theme_menusMultiples.png)
