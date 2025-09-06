### Devoir : Calculateur de Pourboire Personnalisé

**Objectif**: Créer un programme Python qui calcule la facture totale pour un groupe de personnes dans un restaurant, incluant un pourboire, et salue chaque personne avec une salutation basée sur l'heure. Le programme doit utiliser des fonctions, des boucles et des entrées utilisateur, avec une gestion des erreurs pour la robustesse.

**Instructions**:

1.  Écrivez un programme qui :
    *   Demande à l'utilisateur le nombre de personnes dans le groupe.
    *   Demande le nom et le montant de la facture de chaque personne.
    *   Utilise une fonction pour calculer la facture totale, incluant un pourcentage de pourboire (par défaut 15 %).
    *   Utilise une fonction pour afficher une salutation personnalisée basée sur l'heure ("Bonjour" avant 18h, "Bonsoir" après 18h).
    *   Affiche la facture totale et le montant du pourboire pour le groupe.

2.  Exigences :
    *   Utilisez au moins deux fonctions : une pour calculer la facture et une pour la salutation.
    *   Utilisez une boucle pour collecter les noms et les montants des factures pour chaque personne.
    *   Gérez les entrées invalides (par exemple, montants non numériques, nombres négatifs, ou noms vides).
    *   Utilisez l'heure actuelle du système pour déterminer la salutation ("Bonjour" ou "Bonsoir").

3.  Affichez les résultats dans un format clair, montrant la salutation et la contribution à la facture de chaque personne, suivies de la facture totale et du pourboire du groupe.

**Exemple de sortie**:
Combien de personnes dans le groupe ? 3
Entrez le nom de la personne 1 : Alice
Entrez le montant de la facture pour Alice : 20
Entrez le nom de la personne 2 : Bob
Entrez le montant de la facture pour Bob : 15
Entrez le nom de la personne 3 : Charlie
Entrez le montant de la facture pour Charlie : 25
Bonjour Alice, votre contribution à la facture est de 20,00 €.
Bonjour Bob, votre contribution à la facture est de 15,00 €.
Bonjour Charlie, votre contribution à la facture est de 25,00 €.
Facture totale avant pourboire : 60,00 €
Pourboire (15 %) : 9,00 €
Facture totale avec pourboire : 69,00 €

**Entrée invalide**:
Combien de personnes dans le groupe ? abc
Veuillez entrer un nombre valide.
Entrez le nom de la personne 1 :
Veuillez entrer un nom valide.

**Défi (facultatif)**:
- Ajoutez une option permettant à l'utilisateur de spécifier un pourcentage de pourboire personnalisé (entre 0 % et 50 %).
- Validez le pourcentage de pourboire pour qu’il soit raisonnable.

**Soumission**:
- Soumettez le fichier Python (.py) avec votre code.
- Incluez des commentaires expliquant le but de chaque fonction.
- Testez votre programme avec au moins un cas valide et un cas invalide (par exemple, une entrée non numérique).


