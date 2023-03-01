# go-playground

#### 00 - Définir un object Account ayant deux types de cartes credit et debit (considerer qu'on peut avoir plus d'une carte de debit)

#### 01 - Définir un object Account ayant les propriétés

       -ReferenceId, 
       -type
       -AmountLimit. 
       -Balance

###### Les attributs de comptes doivent avoir une visibilite outre package

#### 03 - Logger au format Json le contenu d'un object Account

#### 04 - "marshall" en json and implement stuff to allow to inscrease amount Limit

#### 05 - Ajouter une contrainte de validation sur la propriete  ReferenceId [Accepeter que des valeurs numerics]

#### 06 - Business

    - Definir une operation permettant d'effectuer une operation depense et qui  retourne une erreur lorsque le montant de la dépense depasse la limite de credit disponible

#### 05 - L'opération devrait s'appliquer aux cartes de credit et de débit

#### 06 - Exposer l'operation via une interface au client appellant

#### 07 - Ecrire un test unitaire  permettant de valider que l'operation de check
