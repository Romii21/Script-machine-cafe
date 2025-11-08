# Script-machine-café

	`#!/bin/bash
		`# Execution d'une boucle tant qu'elle est fausse
		`while true; do

        	# Commande client
        	echo "Choisissez une boisson :"
        	echo "1. Café"
        	echo "2. Thé"
        	echo "3. Chocolat"
        	echo "x. Sortir"
        	read -p "Votre choix : " choix

        	# Vérifier le choix du client
        	if [ "$choix" = "1" ]; then
            	    echo "Voici votre café"
                	exit 0
        	elif [ "$choix" = "2" ]; then
             	   echo "Voici votre thé"
                	exit 0
			elif [ "$choix" = "3" ]; then
            	    echo "Voici votre chocolat"
                	exit 0
        	elif [ "$choix" = "x" ]; then
            	    echo "A bientôt"
                	exit 0
        	else
             	    echo "Commande invalide tapez 1, 2, 3, ou x"
        	fi
	`done

![Plan du script](machine_a_cafe.png)
