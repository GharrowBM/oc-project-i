# Liste des tâches techniques pour la réalisation du projet

* Mettre à jour la BDD pour permettre le stockage des magasins de l'enseigne
* Ajout de la table des magasins (id, adresse, nom du gérant, prénom du gérant, sexe du gérant, email du gérant, téléphone du gérant)
* Ajout d'une table de jointure entre magasin et produits (id, id produit, id magasin, quantité disponible)

* Créer l'application Frontend via Angular
* Intercepter l'URL du site de vente en ligne et rediriger vers DeliveryFit

* Vérifier l'interception et la redirection de l'URL vers DeliveryFit

* Créer la page de validation du panier avec les informations d'expédition
* Créer des validators dans le but d'éviter l'envoi d'un formulaire incomplet ou dont l'adresse n'existe pas
* Créer un service permettant le transfert des informations de livraison au backend
* Créer des modèles de données pour faciliter la structure des DTOs
* Créer une méthode dans le service pour transmettre les informations de livraison (articles de la commande, contact, adresse de livraison)
* Création d'une page d'attente de la récupération d'un point d'expédition

* Réaliser les tests de la page du formulaire d'envoi des informations de livraison au backend

* Créer l'application Backend via Spring Boot
* Créer un repository permettant la récupération des établissements et de leurs stocks
* Créer un service permettant le traitement des établissement et de leurs stocks
* Créer une méthode permettant de récupérer en BDD les établissements disponibles pour une livraison dans un rayon pré-défini
* Comparer dans une méthode du service les distances entre les magasins et / ou le centre de livraison et le domicile
* Créer une méthode permettant le calcul du temps de trajet depuis chaque endroit vers le domicile de la personne et l'obtention de la route la plus rapide
* Créer un DTO d'un lieu d'expédition, d'une adresse de livraison, de la date potentielle d'expédition et estimation du temps de trajet / date d'arrivée
* Utiliser le DTO pour envoyer les informations au contrôleur
* Créer un contrôleur dans l'API pour, à partir d'un DTO d'informations de panier et d'une adresse client, retourner un DTO contenant la réponse appropriée 

* Réaliser les tests des méthodes du service de traitement des établissement et des stocks, des retours et des potentielles levées d'exceptions
* Réaliser les tests du contrôleur dans le but de vérifier les code de retour HTTP et les messages potentiels


* Créer la page de confirmation de la livraison possible (bouton confirmer la livraison / procéder au paiement)

* Créer une page d'erreur informant qu'il n'est pas possible d'effectuer la livraison pour l'adresse demandée (message d'erreur libre)

* Implémenter des tests de la page d'attente / confirmation de la commande potentielle, avec vérification de messages d'erreur en cas de soucis

* Créer la redirection de DeliveryFit vers le site de vente en ligne

* Vérifier la redirection en cas d'appui sur le bouton

* Créer un mécanisme de notification au magasin expéditeur de l'arrivée d'une nouvelle commande à préparer 
* Envoyer une notification au magasin expéditeur