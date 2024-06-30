# Les-petits-plats

```mermaid
flowchart TD
    id1([Début]) --> id2[/Changement de valeur de la barre de recherche/]
    id2 --> B{valeurs < à 3}
    B -->|Oui| C[Retourne la liste complète de recettes]
    C --> H
    B ---->|Non| E[Filtre tableau recette]
    E --> F{tableau vide ?}
    F --> |Oui| G[Affiche message d'erreur]
    F --> |Non| H[Affiche les cartes des recettes]
    H --> id3
    G --> id3([Fin])
```
