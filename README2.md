L' application  est conçue pour aider une entreprise de location de véhicules à gérer son parc auto. Elle permet de gérer les véhicules disponibles, les clients, les locations, ainsi que les retours. Le système utilise la programmation orientée objet donc j'ai utiliser  l'héritage, le polymorphisme, l'encapsulation et la gestion des exceptions.


1. Gestion des véhicules : ajout de nouveaux véhicules (voitures ou camions) avec des attributs spécifiques.
2. Gestion des clients : ajout de clients avec des informations de permis et de contact.
3. Location et retour des véhicules:
   - Location de véhicules avec vérification de la disponibilité.
   - Retour de véhicules avec mise à jour du statut.
4. Affichage des véhicules :
   - Liste des véhicules disponibles et loués.
5. Exceptions personnalisées :
   - Gestion des erreurs comme la tentative de louer un véhicule déjà loué ou la tentative de location non autorisée.

 Structure du Code

Le code est organisé autour des classes principales suivantes :
- Vehicule : classe abstraite représentant un véhicule avec des attributs de base (immatriculation, marque, modèle, etc.).
- Voiture et Camion : sous-classes de Vehicule, chacune ayant des attributs spécifiques.
- Client : représente un client de l'entreprise, stockant ses informations de contact et ses locations en cours.
- ParcAuto : gère la collection de véhicules et de clients.
- Interface Louable: définit les méthodes louer() et retourner(), que les classes Voiture et Camion implémentent.
  
