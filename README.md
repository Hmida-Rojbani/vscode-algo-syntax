# algoTACT README

Syntax reader for algorithm language. Code example:
```
// Correspond à la fonction Trouve disponible
FONCTION ENTIER RechercheFilm(Chaine: nomRecherche)
    VARIABLE
        ENTIER: i <- 0
        BOOLEAN: nonTrouve <- VRAI
    DEBUT
        FAIRE
            SI noms[i] = nomRecherche ALORS
                nonTrouve = FAUX
            SINON
                i <- i + 1
            FINSI
        TANTQUE nonTrouve Et i < NB_FILM

        SI nonTrouve ALORS
            i <- NULL
        FINSI

        Retourne i
    FIN
FINFONCTION
```
