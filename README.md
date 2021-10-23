# Mini Framework CSS
Framewok CSS by Guillaume

Exemple site : https://guillaume1415.github.io/Td9/

## Options de grille

|          | Mobile | tablet | large desktop |
| -------- | :----: | :----: | :-----------: |
| largeur  |  auto  | 640px  |    1024px     |
| Préfixe  |   s    |   m    |      xl       |
| colonnes |   12   |        |               |
| gutter   |  10px  |        |               |
-------

**Exemple**

    <div class="container">
        <div class="row">
            <div class="col l-6 col m-6">text</div>
            <div class="col l-6 col m-6">text</div>
            <div class="col l-12 col m-12">text</div>
        </div>
    </div>

## Les Colonnes de Décalages

**offset**
> Déplacez les colonnes vers la droite en utilisant les `.col-m-offset-colonnes`. Ces classes augmentent la marge gauche de *colonne

* **offset-1**
* **offset-2**
* **offset-3**
* **offset-4**
* **offset-5**
* **offset-6**
* **offset-7**
* **offset-8**
* **offset-9**
* **offset-10**
* **offset-11**
* **offset-12**

**Exemple**

    <div class="row">
        <div class="col offset-m-2">.col m-4</div>
        <div class="col m-8">.col m-4 .ml-auto</div>
    </div>

-------
## Navbar
> Les barres de navigation sont fluid par défaut, ne nécessite que une stucture d'une liste classique

**Option de couleur** 

* **.navbar-white**
* **.navbar-dark**

        <div class="navbar-dark">
    <nav>
      <ul>
        <li><a href="#">petit déjeuner</a></li>
        <li><a href="#">Goûter</a></li>
        <li><a href="#">déjeuner</a></li>
        <li><a href="#">diner</a></li>
      </ul>
    </nav>
  </div>

## Les Boutons
> La classe `.btn` est conçues pour être utilisées avec la balise  `<button>`. Vous pouvez également utiliser cette classe sur des balise `<a>`.

    <a class="btn btn-blue" href="#" role="button">Link</a>
    <button class="btn btn-blue" type="submit">Button</button>
----
**bouton outline** 

**.btn-outline**

**Exemple** 

    <button class="btn-outline-*color">button</button>
---- 
**les tailles bouton**

* **.btn-xl**
* **.btn-s** 

**Exemple**

    <button class="btn btn-s">button</button>
    <button class="btn btn-xl">button</button>
----
## Les Ombres

**.shadow-s**

## Alert

> La classe `.btn` est conçues pour être utilisées avec la structure div > p.

<div class="alert alert-success-m">
    <p>Bravo ! vous avez gagné un panda géant</p>
  </div>

  <div class="alert alert-error">
    <h4>alerte rouge</h4>
    <p>ceci est une alerte rouge de 1er niveau, tout va péter dans 30s si vous ne faites rien !</p>
  </div>

**.alert type**

* **.btn-success**
* **.btn-error**

**.alert taille**

* **.btn-success-m**
* **.btn-error-l**
