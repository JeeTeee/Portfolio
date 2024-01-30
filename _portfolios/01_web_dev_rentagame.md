---
layout: portfolio
header_image: "/assets/images/bg/bg-rentagame.jpg"
title: "Rent A Game"
categories: ["Web"]
thumbnail: "/assets/images/portfolio/tbn-rentagame.jpg"
description: "Ce projet a été réalisé dans le cadre de ma formation Développeur Web Full-Stack au Wagon Marseille. <br>
C'est le tout premier projet réalisé en équipe et avec le framework Rails. Il avait pour objectif de nous familiariser avec ce framework et le travail collaboratif.<br>
Le but était de créer en 5 jours, un clone du site Airbnb, avec une interface utilisateur permettant de visualiser les produits et un système de réservations fonctionnel.
 <br><br>
Nous avons eu l'idée de développer une application de location de jeux de société entre particuliers."
---
<div class="col-lg-8 text-left pf-container">
	<h3 class="mb-3 mt-3 project-title">{{page.title}}</h3>
	<p>{{page.description}}</p>

  <hr class="my-5">

  <div class="row">
      <div class="col-lg-4 text-center">
        <p class="text-color font-weight-bold mb-2">Quoi</p>
        <p>Développement Web <br> Ruby on Rails</p>
      </div>
      <div class="col-lg-4 text-center">
        <p class="text-color font-weight-bold mb-2">Quand</p>
        <p>Août 2022</p>
      </div>
      <div class="col-lg-4 text-center">
        <p class="text-color font-weight-bold mb-2">Qui</p>
        <p>En équipe avec Marilou, <br> Mathieu & Jérôme </p>
      </div>
  </div>
</div>

<div class="col-lg-12 text-center my-5 p-5" style="background-color: #c9f1f978">
  <h4 class="mb-3" style="color: #00c8f2">Pourquoi ?</h4>
	<p class="project-caption">Rent A Game est une application web qui facilite le partage de jeux de société entre particuliers, en mettant en relation les joueurs désireux de louer des jeux avec ceux qui les possèdent à proximité. <br> Les utilisateurs peuvent facilement trouver et louer des jeux en fonction de leurs préférences et de leur emplacement grâce à une interface conviviale. <br> Fini les jeux qui prennent la poussière dans les placards, "Rent A Game" favorise le partage et l'accessibilité à une variété de jeux pour des moments de divertissement sans tracas.</p>
</div>

<div class="container">
  <div class="service-2 col-lg-12 mt-5">
    <h4>User Flow (Parcours Utilisateur)</h4>
  </div>
  <div class="user-flow mt-5">
    <p><strong>Problème :</strong> Alice une jeune Marseillaise, souhaite jouer au jeu "Les Aventuriers du Rail" avec ses amis le week-end prochain, mais elle ne possède pas le jeu et ne souhaite pas investir dans l'achat, et personne dans son entourage ne le possède.</p>
    <h6><span class="step">01</span> Recherche du Jeu</h6>
    <p>Alice se connecte à Rent A Game et peut utiliser la fonction de recherche pour trouver le jeu. <br> Cependant, elle préfère trouver un jeu qui soit près de chez elle, alors elle utilise la carte intégrée pour explorer les jeux disponibles dans son quartier.</p>
    <h6><span class="step">02</span> Vérification de la Disponibilité</h6>
    <p>Grâce à la géolocalisation, elle repère sur la carte que Franck propose le jeu à proximité de chez elle et qu'il est disponible le week end prochain.</p>
    <h6><span class="step">03</span> Demande de Location</h6>
    <p>Alice sélectionne le jeu puis choisi la date de location et fait une demande de réservation.</p>
    <h6><span class="step">04</span> Confirmation de la Location</h6>
    <p>Franck accepte la demande de location et confirme les détails avec Alice, y compris le lieu et l'heure de récupération du jeu.</p>
    <h6><span class="step">05</span> Récupération du Jeu</h6>
    <p>Alice récupère le jeu "Les Aventuriers du Rail" selon les arrangements convenus avec Franck.</p>
    <h6><span class="step">06</span> Retour du Jeu</h6>
    <p>Après avoir joué avec ses amis, Alice retourne le jeu à son propriétaire.</p>
    <div class="col mt-3 mb-5 px-0 paysage-container">
      <div class="fade-in animscroll">
        <img src="/assets/images/portfolio/rentagame/user-flow-rentagame.gif" alt="parcours utilisateur rent a game" class="project-img">
      </div>
      <p class="pt-4 mb-5"><strong>Solution :</strong> Avec Rent A Game, Alice peut facilement louer le jeu de son choix sans se ruiner, offrant ainsi une solution abordable à ses envies de jeu. </p>
    </div>
  </div>

  <div class="service-2 col-lg-12 mt-5">
    <h4>Développement du Projet</h4>
  </div>

  <div class="user-flow mt-5">
    <p>Rent A Game a été notre premier projet de groupe au Wagon, marquant notre initiation au framework <a href="https://rubyonrails.org/" target="_blank">Ruby on Rails</a> et au développement en équipe. En cinq jours, nous avons mis en place un système de réservation, permettant aux utilisateurs de créer des objets (les jeux), une barre de recherche et une fonction de géolocalisation avec Mapbox. Cette expérience nous a également appris à travailler efficacement sous pression, en préparant et présentant le projet devant notre promotion.</p>
    <h4><span class="step">01</span> Design</h4>
    <h6>Architecture de l'application</h6>
    <p>Nous avons défini le parcours utilisateur puis élaboré les user stories, conçu le schéma de la base de données et configuré les routes de l'application.</p>
    <div class="col my-3 px-0 justify-content-start">
      <div class="fade-in animscroll">
        <img src="/assets/images/portfolio/rentagame/rentagame-db-table.jpg" alt="tables base de données rent a game" class="project-img">
      </div>
    </div>
    <h6>Logo</h6>
    <p>Avec mon expérience en graphisme, j'ai conçu le logo de Rent A Game. En intégrant la lettre A dans un dé à 20 faces, évoquant la symbolique des jeux de société. J'ai choisi la police "Josefin Sans" pour sa lisibilité, son style à la fois moderne et rétro qui s'harmonise parfaitement avec l'imaginaire ludique et nostalgique des jeux de plateau.</p>
    <div class="col my-3 px-5 paysage-container">
      <div class="fade-in animscroll">
        <img src="/assets/images/portfolio/rentagame/logo-rent-a-game.png" alt="logo rent a game" class="logo-img">
      </div>
    </div>
    <h4><span class="step">02</span> Création</h4>
    <h6>Nouveau Projet Rails</h6>
    <p>Création de l'application Rails et du dépôt sur <a href="https://github.com/MatWebDev/rent_a_game" target="_blank">Github</a>. <br> Nous avons ensuite créé les modèles et leurs contrôleurs, en plus d'établir leurs associations et validations, tout en suivant le schéma de base de données.</p>
    <div class="col my-3 px-0 justify-content-start">
      <div class="fade-in animscroll">
        <img src="/assets/images/portfolio/rentagame/rentagame-code-sample.jpg" alt="échantillon du code de passengers" class="project-img">
      </div>
    </div>
    <h4><span class="step">03</span> Fonctionnalités</h4>
    <p>Au cours du développement, nous avons mis en pratique nos connaissances sur Rails en implémentant plusieurs fonctionnalités.</p>
    <h6 class="mt-5">Barre de recherche</h6>
    <div class="col my-3 px-0 paysage-container">
      <div class="fade-in animscroll">
        <img src="/assets/images/portfolio/rentagame/searchbar-rentagame.gif" alt="searchbar rent a game" class="project-img">
      </div>
    </div>
    <h6 class="mt-5">Création d'objets</h6>
    <div class="col my-3 px-0 paysage-container">
      <div class="fade-in animscroll">
        <img src="/assets/images/portfolio/rentagame/creation-rentagame.gif" alt="object creation rent a game" class="project-img">
      </div>
    </div>
    <h6 class="mt-5">Carte géolocalisée</h6>
    <div class="col my-3 px-0 paysage-container">
      <div class="fade-in animscroll">
        <img src="/assets/images/portfolio/rentagame/geoloc-rentagame.gif" alt="object creation rent a game" class="project-img">
      </div>
    </div>
  </div>
</div>
