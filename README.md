# https://github.com/boilleym/mmi-tp-rgaa-2

# mmi-tp-rgaa-2

# Introduction
Vus êtes mandatés par l'organisation de la convention de Donjons et Dragons de l'IUT pour assurer un bon niveau d'accessibilité de leur formulaire d'inscription.

# Initialisation
+ Récuperer le fichier DND_MMI.zip, le décompresser dans un répertoire local de votre PC soit accessible en écriture. 
+ Ouvrir les trois fichiers **index.html**, **style.css** et **script.js** dans un IDE ou éditeur de code source ou bloc note de votre choix.
+ Ouvrir **index.html** dans un navigateur moderne de votre choix.

# Travaux

## Métadonnées
1- Completez les balises `<title>` et `<meta "description>` avec des libellés pertinents.

## Couleurs et illustrations
2- Avec l'outil de votre choix vérifiez que le contraste entre tous les textes et leurs arrières plans est bien au minimum 4.5:1<br />
Si ce n'est pas le cas, corrigez la couleur dans le CSS pour respecter le ratio minimal tout en restant le plus proche possible de la couleur initale.

3- Est ce que une ou plusieurs images ont besoin d'un texte alternatif ? Si besoin corrigez le code source en ajoutant un texte alternatif pertinent.<br />
Si aucun texte alternatif n'est utile, vérifier que l'attribut "alt" soit présent mais vide.

## Balisage 
4- Vérifier les attributs de langue (global et la page et local pour les phrases en langues étrangères)<br />
https://developer.mozilla.org/fr/docs/Web/HTML/Global_attributes/lang

5- Vérifier la non utilisation de paragraphes vides. Remplacez les paragraphes vides en utilisant du code css approprié.

6- Utiliser un balisage correct pour les citations.<br />
https://developer.mozilla.org/fr/docs/Web/HTML/Element/blockquote

7- Vérifiez la hiérarchie des titres. Modifiez le HTML en conséquence.

## Formulaire

8- Dans le formulaire, préciser, en complément du libellé, le format attendu pour chaque champ et/ou les contraintes de saisie.<br />
Si un champ est obligatoire il doit être identifié (par exemple avec un astérisque "*") et la règle doit être indiquée au début du formulaire, par exemple sous la forme d'une phrase d'information : "Les champs indiqués d'un * sont obligatoire".

9- Balisez le message d'erreur avec le bon rôle ARIA<br />
https://access42.net/live-regions-aria-live-analogues-alert-log-status/

10- Est ce que les messages d'erreur et de confirmation utilisent une balise HTML sémantique appropriée ? Si non corrigez le HTML.

11- Utilisez un attribut aria-label pour completer le libellé peu clair du bouton<br />
https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Attributes/aria-label

12- Utilisez les bons attributs autocomplete sur les champs nom, prénom et mail pour suggerer la saisie de valeurs déjà connues par le navigateur.<br />
https://developer.mozilla.org/fr/docs/Web/HTML/Attributes/autocomplete

## Navigation 

13- Naviguez au clavier dans la page, chaque élément recevant le focus doit être mis en évidence graphiquement. Si ce n'est pas le cas completez le CSS (en utilisant la pseudo classe :focus) pour ajouter un effet de bordure lors de la prise de focus des éléments. (1 point bonus si la couleur de la bordure est raccord avec la robe du mage de l'illustration).<br />
https://developer.mozilla.org/fr/docs/Web/CSS/outline<br />
https://developer.mozilla.org/fr/docs/Web/CSS/outline-offset

**Facultatif** Développer un bloc de liens d'évitement contenant un lien interne (ancre) vers la balise `<article>` et un autre lien interne vers la balise `<footer>`.<br />
Ce bloc est visible uniquement lorsque le focus clavier est positionné sur l'un des deux liens.<br />
https://a11y-guidelines.orange.com/fr/articles/liens-evitement/<br />
https://www.accede-web.com/notices/html-et-css/navigation-au-clavier/mettre-en-place-un-lien-devitement/

## Conformité W3C
14- Vérifiez la conformité de votre HTML en copiant / collant le contenu de **index.html** dans le champ de contrôle "Direct input" du *W3C Validator*.<br />
Corrigez les erreurs éventuelles.<br />
https://validator.w3.org/#validate_by_input





