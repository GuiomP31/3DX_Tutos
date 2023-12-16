
![Sans titre](https://github.com/GuiomP31/3DX_Tutos/assets/101930653/6f6b20ad-0bff-4b78-95c4-af43a52441b8)


Exos entrainement EKL-Library pour prise en main de 3DEXPERIENCE | CATIA
Eurodrone_Design

/* Action créé(e) par GPAS3I3W 22/11/2023 */

# Faire une roue et la greffer à une Product Structure   

    Roue => Y43XE9638-292
    Product Structure => Y78UI1664-859 A.1
    Planche Bis => Y29NF1567-300
    Roulements => Y36B19391-200
    Roue Bis => Y18577914-340 A.1

   
## Avant aller sur Action et créer un fichier de code.
    Engineering Rules Capture

### Afficher les APN et les attributs de chaque pièces du skate.

#### Setter un attribut avec une condition
    - Rajouter deux Storable Assembly (SA)

    - Rajouter un EHI (Electrical Harness Installation) previously called Electrical Design
        C' est un produit dédié à la conception de harnais physiques dans le cadre de la maquette 3D. La conception du harnais est totalement intégrée à l’ensemble mécanique. Ce produit fournit un ensemble d'objets possédant à la fois des propriétés mécaniques et électriques.

    - Rajouter un Project Definition 
        Définition du projet Données utilisées pour faciliter la coordination entre Airbus et ses partenaires et sous-traitants en ce qui concerne la conception future. En particulier au début de la phase du projet, une définition de projet soutiendra les activités de conception et de conception préliminaire pour convenir des lignes de base du projet.

     - Parcourir la Product Structure et mettre à jour la description si l'objet est un SA.

     - SA => ADS_StorableAssembly_CPT

     
