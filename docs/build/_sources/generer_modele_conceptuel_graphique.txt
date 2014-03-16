Générer le modèle conceptuel graphique
======================================

	.. image:: ./images/executermod.png

	*Figure 45 : fonction Exécuter et son sous-menu.*

L'action doModelGraph génère le modèle conceptuel graphique pour un modèle sélectionné.

Générer le modèle conceptuel graphique d'un modèle sélectionné
""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""

1. À partir de l'onglet **Modèle**, cliquez sur la ligne de la grille principale qui corresponde au modèle à générer.
2. Cliquez sur le bouton **Exécuter** du menu des fonctions ou sur le petit triangle noir situé du côté droit du même bouton. 
   Le petit triangle noir affiche les deux options disponibles pour Exécuter.
3. Cliquez sur l'option **doModelGraph** . Un message de confirmation de l'opération sera affiché sur l'interface 
   (voir `la barre de message <barre_message.html>`_ pour plus de détails).
4. Le modèle graphique généré est ouvert dans un nouvel onglet de votre fureteur. Le format de sortie de la graphique est 
   un fichier PDF.


Formalisme du modèle graphique
""""""""""""""""""""""""""""""

	.. image:: ./images/generermodele.png
	
	*Figure 46 : formalisme du modèle graphique.*

**Clé primaire** : la police du texte est grasse et sa couleur est noire. Exemples dans la figure : numero_ligne, numero_produit 
et date_expedition.

**Clé étrangère** : la police du texte est italique et sa couleur est gris pâle. Le nom de son entité enfant apparait du côté 
droit du nom de la clé. Exemple : li_prt -> produit ou cde_fact -> facture.

**Clé étrangère dépendante (obligatoire)** : la police du texte est grasse et sa couleur est noire. Le nom de son entité enfant 
apparait du côté droit du nom de la clé. Exemple : li_cde -> commande.

**Clé étrangère requise (obligatoire)** : la police du texte est grasse et sa couleur est gris pâle. Le nom de son entité enfant 
apparait du côté droit du nom de la clé. Exemple : pdt_fam -> famille.

**Propriété** : la police du texte est en italique et sa couleur est gris pâle. Exemples dans la figure : prix_vente, qte_vendue 
et prix_production.

**Propriété requise (obligatoire)** : la police du texte est grasse et sa couleur est gris pâle. Exemples dans la figure : 
nom_produit et numero_commande.

**Relation dépendante (obligatoire)** : la flèche est pleine.

**Entité parent** : la flèche pointe vers l'entité parent.
