# TP2-INTEGRITE-ET-HACHAGE
exo 1: effet d'avalanche 
exo2: 1) longueur fixe
2)32 octets l'affichage compte 64 caractères car 1 cotet = 2 caractères héxadécimaux
exo 3: la moindre altération modifie l'empreinte, ce qui permet de détecter immédiatement la falcification
exo 4: 1)l'(empreinte MD5 est plus courte ce qui réduit les possibilités et favorise les collisions
2) MD5 est déconseillé car il est vulnérable à ces collisions
exo 5: 1)non les contenus sont diférents
2)leur MD5 sont identiques mais leur SHA-256 différent
3)MD5 est définitivement cassé
') l'attaquant peut modifier le document sans altérer l'empreinte MDS
exo 6: 1) le texte change mais l'(empreinte SHA-1 reste identique 
2)la signature ne garantit plus rien
3)SHA-256 car il resiste toujours aux collision
