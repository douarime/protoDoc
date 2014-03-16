Personnaliser la grille
=======================

::

	Les exemples de personnalisation suivants montrent comment réaliser la configuration de base pour réussir une interface 
	fonctionnelle et présentable. Vous êtes invités à explorer dans votre espace travail de l'application les propriétés non 
	mentionnées dans cette guide.
	
**Propriété gridConfig**
	
	.. image:: ./images/metagridconf.png
	
	*Figure 30 : personnalisation de la grille.*

1. Ouvrez le contenu du dossier gridConfig en cliquant sur le triangle blanc situé à gauche du dossier;
2. Sélectionnez de la liste la valeur à personnaliser;
3. Modifiez les valeurs;
4. Ensuite, enregistrez les changements en cliquant sur le bouton |img| Mettre à jour la méta.


**Valeurs :**

**gridConfig -> hideRowNumbers** valeur booléenne qui sert à afficher ou cacher sur la grille les numéros de lignes.

**gridConfig -> exportCsv** valeur booléenne qui sert à activer ou désactiver la fonctionnalité d'exportation en format CSV. 
Notez que la fonction exportCsv exporte la liste complète de résultats et non seulement ceux qui sont affichés dans la page active. 
La fonction « exportCsv » apparaît à l'intérieur de la fonction « imprimer » du menu de fonctions. (voir `imprimer <menu_imprimer.html>`_).

**listDisplay** sert à personnaliser l'affichage et l'ordre d'apparition de champs sur la grille (voir `option configuration <option_configuration.html>`_).

**searchFields** sert à choisir les champs qui seront pris en compte au moment de faire une recherche sur le contenu de la grille. 
Cette propriété est utilisée avec la propriété « searchable » d'un champ.

**sortFields** sert à choisir les champs qui seront pris en compte au moment de faire le classement du contenu de la grille. 
Cette propriété est utilisée avec la propriété « sortable » d'un champ.

**hiddenFields** sert à choisir les champs qui ne seront pas affichés dans la grille. Notez que cette fonctionnalité cache un 
champ à l'affichage, elle ne l'efface pas de l'application.

.. |img| image:: ./images/saveform.png