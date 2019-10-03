# chamionnatFoot
Feuille de calcul championnat OpenOffice Calc

A.1 Début de championnat
	À chaque début de championnat, plusieurs manipulations sont à faire :
- Modifier le tableau ‘Équipes’ et ‘Sigles’ de la feuille ‘Classement’, puis le trier par ordre alphabétique
- Supprimer tous les résultats et les rencontres de la feuille ‘Rencontres’ (enlever la protection de la feuille)
- Renseigner toutes les rencontres du championnat. Pour ce faire, il est préférable d’ouvrir deux fenêtres (Menu Fenêtre → Nouvelle fenêtre). Une fenêtre sur la feuille ‘Classement’, centrée sur les noms des équipes, l’autre fenêtre sur la feuille ‘Rencontres’. Pour chaque rencontre, il faudra sélectionner la case dans laquelle inscrire le nom d’une équipe, taper ‘=’, puis sélectionner dans la seconde fenêtre la cellule de l’équipe. Ceci pour une cohérence des noms d’équipes au sein du classeur. Sans cela, tout ne fonctionnera pas correctement.
- Supprimer les résultats de la feuille ‘Barrages’.


A.2 Feuille Classement	
	La feuille classement est principalement un feuille de consultation. Elle est composée de trois classements différents : Classement général, classement domicile et classement extérieur. Chaque classement est composé du tableau de classement, la meilleure attaque et défense, ainsi que la pire attaque et défense. Deux boutons sont aussi présents, pour se rendre aux deux autres classements (que l’on peut aussi atteindre en montant ou descendant la feuille). Ces boutons ont été calibrés pour un écran de 43,9 cm. Avec un écran d’une autre taille, ces boutons n’afficheront pas les autres classements en entier.
	À droite du classement général se trouve un bouton ‘Classement’. Ce bouton permet de classer les différents tableaux de la page. Si les chiffres sont mis à jour automatiquement, il est nécessaire de cliquer sur ce bouton pour avoir un classement à jour.
	À droite du bouton ‘Classement’ se trouve un tableau avec deux colonnes ‘Équipes’ et ‘Sigle’. La modification des noms des équipes ou de leur sigle se fait UNIQUEMENT dans ce tableau, et nulle part ailleurs dans le classeur. Attention à ne pas mettre deux fois le même nom d’équipe ou le même sigle.
	Pour pouvoir permettre le classement des tableaux, ceux-ci ne sont pas protégés. Il ne faut en aucun cas les modifier ! Tout se fait automatiquement.


A.3 Feuille Rencontres
	La feuille ‘Rencontres’ se compose comme suit :
- Une entête avec un curseur et un champ pour mettre en évidence une équipe.
- Les rencontres du championnat classés par journée.
- Un tableau récapitulatif de toutes les journées de la saison
	Le curseur sert à sélectionner la journée voulue. À utiliser principalement pour passer à une journée éloignée de celle affichée à l’écran.
	Le champ ‘Mettre en évidence’ sert à faire apparaître des flèches autour de chaque rencontre de l’équipe sélectionnée. Pour enlever la mise en évidences, sélectionner ‘Équipes’.
	Les rencontres du championnat sont à remplir par l’utilisateur. À chaque match, le score doit être inscrit.
	Le tableau récapitulatif se trouve en haut de la feuille, sur la droite. Il récapitule les scores pour chaque rencontre. Pour chaque rencontre, l’équipe en ordonnée (colonne) est l’équipe à domicile. L’équipe en abscisse (ligne) est l’équipe à l’extérieur. Sous ce tableau se trouve la légende des couleurs pour les victoires à domicile, les victoires à l’extérieur, ou les matchs nuls. Cette légende affiche aussi le pourcentage de résultats pour les matchs joués.


A.4 Feuille Équipe indiv
	La feuille ‘Équipe indiv’ est purement une feuille de consultation. En haut à droite de la feuille se trouve la sélection de une ou deux équipes à analyser. Le champ ‘Comparer à’ ne sera pas obligatoirement renseigné (dans ce cas, il faudra sélectionner ‘Équipes’).
	Sur cette feuille se trouvent deux tableaux récapitulatifs de la situation de chaque équipe sélectionnée. ‘Place max’ et ‘Place min’ sont calculées en fonction du nombre de points des équipes. Les rencontres particulières ne sont pas prises en compte (le classeur considère que toutes les équipes peuvent avoir trois points dans chaque journée restante, il ne fait pas attention au fait que deux équipes qui se rencontrent ne peuvent pas avoir trois points toutes les deux). Ce n’est donc qu’un indicateur.
	Le graphique du haut représente les points par journée, avec un tableau en dessous indiquant le résultat (‘V’ pour victoire, ‘N’ pour nul, ‘D’ pour défaite) de chaque journée.
	Le graphique du bas représente le classement par journée, avec un tableau au-dessus indiquant le classement par journée (pour plus de précision).
	Le bouton ‘Classement’ présent à côté du tableau du classement par journée sert à effectuer tous les classements par journée. Il ne classe pas les tableaux de la page ‘Classement’.
	Renseigner une deuxième équipe dans le champ ‘Comparer à’ permet de comparer les courbes de chaque équipe, pour une analyse confortable.
	En dessous de ces graphiques se trouvent deux tableaux indiquant les calendriers des équipes sélectionnées. Les lignes des rencontres peuvent être de couleurs différentes. Vert pour match gagné, jaune pour match nul, rouge pour match perdu, et blanc pour match non joué. Collé à ces tableaux, une colonne indique le classement de l’adversaire avant le match. Dans l’entête de cette colonne se trouve la moyenne du classement des adversaires rencontrés. Attention, ces tableaux utilisent les expressions régulières. Si les équipes ne s’affichent pas, faire la manipulation suivante : Outils → Options → LibreOffice Calc → Calcul → Cocher « Autoriser les expressions régulières dans les formules »


A.5 Feuille class par journée
	La feuille ‘class par journée’ résume tous les 28 tableaux de classement tout au long de la saison. Cette feuille a besoin de classer tous les tableaux, donc elle n’est pas protégée. Il ne faut surtout pas modifier quoi que ce soit. Un bouton ‘Classement’ est présent, pour classer tous les tableaux de cette feuille.


A.6 Feuille Barrages
	La feuille ‘Barrages’ permet de gérer les deux play-off et le barrage. Les équipes de play-off sont renseignées automatiquement. L’équipe de L2 pour le barrage se renseigne automatiquement aussi. Il faut indiquer dans le champ ‘18ème de L1’ l’équipe de ligue 1 qui aura fini 18ème.
