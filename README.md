# exo-algo-henri-joel

Exercice 1:
1-
calculer le taux de contamination de la CI

2-Declaration des variables :
Var {nbre1, nbre2, taux} : reels
 
3-Traitement :

DEBUT
	Afficher ("Entrer le nombre de contamination partielle :") ;
	Saisir (nbre1) ;

	Afficher ("Entrer le nombre total de contamination :") ;
	Saisir (nbre2) ;

	taux = (Nbre1 X 100) /nbre2  ;
				   
	Afficher ("le taux de contamination est :"  + taux ) ;
	 
FIN







exercice2 :
1-
Montrer qu’une année donnée est non-bissextile
2-Declaration des variables :
Var {nbre } : reels

3-Traitement :

DEBUT

Afficher ("Entrer le nombre d'année:") ;
Saisir (nbre1) ;

         SI MODULO(nbre/4) =! 0  ALORS
		    afficher("l'année est non-bissextile") ;
		 
	     SINON 
		      
			 SI MODULO(nbre/100) =! 0 et MODULO(nbre/400) =! 0 ALORS
		        afficher("l'année est non-bissextile") 
			
		     FINSI
			
		 FINSI
			
		 
FIN

