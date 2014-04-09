Créer une propriété
===================

La quatrième étape pour construire un prototype consiste à créer les propriétés des entités du modèle conceptuel de données. 
Vous allez créer les propriétés à l'intérieur de chacune des entités créées à l'étape antérieure. Une entité peut être définie 
par une ou plusieurs propriétés, mais une propriété définie à une seule entité.

Il y a deux façons de créer les propriétés d'une entité. La première façon est de les créer au même moment qu'une nouvelle entité. 
Quand une nouvelle entité est créée, les contrôles d'édition s'activent sur la grille des « propriétés de l'entité » du même 
formulaire. En cliquant sur le bouton ajouter de cette grille, un nouveau formulaire s'ouvrira pour remplir les informations 
concernant les propriétés. Les propriétés sont créées une par une.

La deuxième façon de créer les propriétés est à partir du menu principal. Nous allons explorer les deux façons dans le texte qui 
suit.

Créer une nouvelle propriété à partir du menu principal
"""""""""""""""""""""""""""""""""""""""""""""""""""""""

	.. image:: ./images/proprietes.png
	
	*Figure 40 : créer une propriété.*

1. À partir du menu principal, cliquez deux fois sur Propriété pour ouvrir l'onglet « Propriété » qui donne accès à la grille 
   principale.
   
2. Cliquez sur le bouton **Éditer** du menu de fonctionnalités pour rentrer en mode d'édition ( voir 
   `la fonction Éditer :doc:<menu_editer>` pour plus détails ).
   
3. Cliquez sur le bouton **Ajouter**, un formulaire sera affiché sur l'écran.

4. Dans le formulaire, remplissez (voir figure plus bas) :

 - le nom de la propriété (information obligatoire);

 - le nom de l'entité (information obligatoire); Cliquez sur le bouton |img1| pour sélectionner l'entité de la liste;

 - la description de l'entité (information optionnelle);

 - cochez la caisse de la clé primaire si la propriété est la clé de l'entité. Quand vous cochez cette caisse, la caisse de 
   Réquis est crochée automatiquement. Si la propriété n'est pas une clé primaire, mais que la propriété est obligatoire, 
   cochez la caisse Réquis. La caisse Clé étrangère est crochée automatiquement par l'application et elle est disponible en 
   lecture seulement;

 - sélectionnez le Type de base (information optionnelle). Le type de base par défaut est string. Si le choix de type de base 
   est décimal, remplissez le champ Décimales. Si le choix de type de base est combo, remplissez le champ Valeurs de la liste 
   déroulante et le champ Valeur par défaut;

 - la Longueur (information optionnelle).

 - la Valeur par défaut (information optionnelle). Ce champ est utilisé en combinaison avec le type de base combo. Inscrivez 
   dans ce champ la valeur par défaut de votre liste de valeurs. Par exemple, si vous avez une liste de provinces et que votre 
   projet est pour les gens de Québec, inscrivez QC dans la valeur par défaut. Cette valeur sera le premier choix montré à 
   l'usager;

 - les Décimales (information optionnelle). Ce champ est utilisé en combinaison avec le type de base décimal. Inscrivez dans 
   ce champ le nombre de positions après la virgule pour un chiffre;

 - les Valeurs liste déroulante (information optionnelle). Ce champ est utilisé en combinaison avec le type de base combo. 
   Inscrivez la liste de valeurs pour une propriété. Les mots doivent être séparés par des virgules sans espaces en blanc. 
   Exemple: QC,ON,NS,NB,BC...
    
5. Cliquez sur le bouton **Enregistrer** de la fenêtre.

.. |img1| image:: ./images/lupa.png

Créer une nouvelle propriété à partir du formulaire de l'entité
"""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""

	.. image:: ./images/proprietes1.png
	
	*Figure 41 : créer une propriété détails.*

1. À partir du formulaire de l'entité, cliquez sur le bouton **Ajouter** de la grille « propriétés filtrées par " " » ;

2. Un nouveau formulaire (comme celui de la figure à gauche) s'affichera dans l'interface ;

3. Dans le formulaire, remplissez :

 - le nom de la propriété (information obligatoire)

 - le nom de l'entité (information obligatoire). Cliquez sur le bouton pour sélectionner l'entité de la liste;

 - la description de l'entité (information optionnelle);

 - Cochez la caisse de la clé primaire si la propriété est la clé de l'entité. Quand vous cochez cette caisse, la caisse de 
   Réquis est crochée automatiquement. Si la propriété n'est pas une clé primaire, mais que la propriété est obligatoire, 
   cochez la caisse Réquis. La caisse Clé étrangère est crochée automatiquement par l'application et elle est disponible en 
   lecture seulement;

 - Sélectionnez le Type de base (information optionnelle). Le type de base par défaut est string. Si le choix de type de base 
   est décimal, remplissez le champ Décimales. Si le choix de type de base est combo, remplissez le champ « Valeurs de la liste 
   déroulante » et le champ Valeur par défaut;

 - la Longueur (information optionnelle);

 - la Valeur par défaut (information optionnelle). Ce champ est utilisé en combinaison avec le type de base combo. Inscrivez 
   dans ce champ la valeur par défaut de votre liste de valeurs. Par exemple, si vous avez une liste de provinces et que votre 
   est pour les gens de Québec, inscrivez QC dans la valeur par défaut. Cette valeur sera le premier choix montré à l'usager;

 - les Décimales (information optionnelle). Ce champ est utilisé en combinaison avec le type de base décimal. Inscrivez dans 
   ce champ le nombre de positions après la virgule pour un chiffre;

 - les Valeurs liste déroulante (information optionnelle). Ce champ est utilisé en combinaison avec le type de base combo. 
   Inscrivez la liste de valeurs pour une propriété. Les mots doivent être séparés par des virgules sans espaces en blanc. 
   Exemple: QC,ON,NS,NB,BC...
   
4. Cliquez sur le bouton **Enregistrer** de la fenêtre.

Notez dans la deuxième façon présentée dans ce texte que quand vous cliquez sur le bouton Enregistrer, la grille 
« Relation filtrées par " "» située en bas de la grille « Propriétés filtrées par " "» affiche les contrôles d'édition 
(voir figure 42). À partir de cette grille, il est possible de créer les relations entre les entités en cliquant sur le bouton 
Ajouter du menu de contrôles. Ceci est une de deux façons de créer les relations entre les entités.
Passez à l'étape :doc:`créer les relations <creer_relation>` entre les entités pour continuer avec la démarche.
	
	.. image:: ./images/proprietes2.png
	
	*Figure 42 : creéer une relation.*
