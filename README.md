# Calculateur de Contributions Égalitaires (Proportionnelles au Patrimoine)

Ce script Python calcule les contributions mensuelles de deux partenaires pour un compte commun, en s'assurant que chaque partenaire contribue à hauteur du *même pourcentage* de son patrimoine total.  Il ne s'agit pas d'une égalité des montants, mais d'une égalité *proportionnelle* des efforts financiers.

## Fonctionnement

1.  **Saisie des données :**
    *   Le script demande à l'utilisateur d'entrer le patrimoine total de chaque partenaire (en euros).
    *   Il demande ensuite d'entrer le montant total des dépenses mensuelles du compte commun (en euros).
    *   Des contrôles de saisie simples sont inclus pour éviter les valeurs négatives ou non numériques.

2.  **Calcul du pourcentage cible :**
    *   Le script calcule le pourcentage que représentent les dépenses totales par rapport au patrimoine total combiné des deux partenaires.
    *   Ce pourcentage est le "pourcentage cible" qui sera appliqué à chaque patrimoine individuel.
    * Si le patrimoine total est de 0, le pourcentage cible est également de 0, afin d'éviter les erreurs.

3.  **Calcul des contributions individuelles :**
    *   La contribution de chaque partenaire est calculée en appliquant le pourcentage cible à son patrimoine personnel.

4.  **Affichage des résultats :**
    *   Le script affiche un résumé clair et détaillé :
        *   Patrimoine de chaque partenaire.
        *   Pourcentage de contribution (identique pour les deux).
        *   Contribution mensuelle de chaque partenaire (en euros).
        *   Dépenses totales du compte commun.
        *   Somme des contributions (pour vérification).
        *   Rappel du pourcentage cible.

