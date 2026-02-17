<div align="center" style="position: relative; width: 100%;">

  <!-- GIF en arrière-plan -->
  <img src="gifs/avion.gif" width="100%" style="display: block;">

  <!-- Overlay texte -->
  <div style="
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  ">

    <div style="
      background-color: rgba(0, 0, 0, 0.6);
      padding: 30px 50px;
      border-radius: 6px;
      text-align: center;
    ">

      <h1 style="
        margin: 0;
        font-weight: 500;
        letter-spacing: 2px;
        color: white;
      ">
        Portfolio
      </h1>

      <p style="
        margin-top: 12px;
        color: #e0e0e0;
        font-size: 16px;
      ">
        Projets académiques & développement logiciel
      </p>

    </div>

  </div>

</div>

<br><br>

---

# Optimisation d’itinéraire  
### Livraison Pokémon – Java

<p align="center">
  <img src="assets/project-java-hero.png" width="85%">
</p>

<br>

## Présentation

Projet développé en Java dans le cadre d’un module d’exploration algorithmique.  
L’objectif était de modéliser un système de livraisons respectant des contraintes de précédence (vendeur → acheteur) tout en optimisant les distances parcourues.

<br>

## Approche technique

<p align="center">
  <img src="assets/java-architecture.png" width="70%">
</p>

- Modélisation par graphe orienté  
- Vérification des dépendances via tri topologique  
- Optimisation par algorithme A*  
- Calcul dynamique des distances  

<br>

## Structure

```bash
src/
 ├── Graphe.java
 ├── GrapheLivraison.java
 ├── LectureScenario.java
```

<br><br>

---

# Gestion de parc informatique  
### Application Web

<p align="center">
  <img src="assets/project-web-hero.png" width="85%">
</p>

<br>

## Présentation

Application web permettant la gestion complète d’un parc informatique :  
inventaire, comptes utilisateurs, import de données et suivi du matériel.

<br>

## Fonctionnalités

<p align="center">
  <img src="assets/web-interface-overview.png" width="70%">
</p>

- Authentification sécurisée  
- Gestion des techniciens  
- Ajout / suppression de matériel  
- Import CSV  
- Consultation centralisée de l’inventaire  

<br>

## Technologies

HTML · CSS · JavaScript · Backend · Base de données SQL  

<br><br>

---

<div align="center">

<img src="assets/footer-minimal.png" width="100%">

<br>

<sub>
Consultez les dépôts pour accéder aux détails techniques.
</sub>

</div>
