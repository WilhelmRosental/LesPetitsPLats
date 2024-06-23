# Les-petits-plats

```mermaid
flowchart TD
    id1([Début]) --> id2[/Changement de valeur de la barre de recherche/]
    id2 --> B{valeurs < à 3}
    B -->|Oui| C[Retourne la liste complète de recettes]
    C --> D[Créé les cartes et les affiches]
    B ---->|Non| E[Filtre tableau recette]
    E --> F[Retourne le tableau filtré]
    F --> D
    D --> id3([Fin])
```
