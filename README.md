# Recommandation_Produit
Ce projet est un POC, l’idée étant, avec les données fournies par l’entreprise, de démontrer la faisabilité d’une recommandation de produit et du ROI sur le chiffre d’affaires de l’entreprise.


### Veille

Faire une veille, sur les systèmes de recommandation, avec tout d’abord la différence entre :
les algorithmes de filtrage collaboratif
les algorithmes basés sur des règles
les algorithmes basés sur le contenu

Puis ces algorithmes :
Apriori
FPGrowth

Et bonus : https://maciejkula.github.io/spotlight/


### Sujet 

L’entreprise MiniMarket vous a contacté car elle souhaite mieux conseiller les consommateurs qui viennent sur leur site pour un produit spécifique, mais qui ne peuvent l’acheter car celui-ci est indisponible (soit hors stock au moment de l’achat, soit indisponible car plus vendu, …).
Avant cela de travailler la partie recommandation, vous devrez mieux appréhendez le problème, faire un état des lieux des attentes du consommateur ou client et de ce qui peut être amélioré par/pour l’entreprise.
Ce projet est un POC, l’idée étant, avec les données fournies par l’entreprise, de démontrer la faisabilité d’une recommandation de produit et du ROI sur le chiffre d’affaires de l’entreprise.


### Explication des variables du jeu de données :

InvoiceNo : Numéro de facture où ont été commandés les produits
StockCode : Identifiant produit
Description : Description du produit acheté
Quantity : Quantité du produit acheté
InvoiceDate : Date de commande (01/12/2010 au 09/12/2011)
UnitPrice : Prix unitaire du produit
CustomerID : Identifiant du client
Country : Pays où la commande a été effectuée par le client
GroupPrice : Prix de tous les produits achetés (Quantité x UnitPrice)
