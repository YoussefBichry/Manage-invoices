# Manage-invoices
### Une application basée sur une architecture micro-service qui permet de gérer les factures contenant des produits et appartenant à un client.
#### 1.Créer le micro-service customer-service qui permet de gérer les client :
![Capture d’écran 2022-12-08 150515](https://user-images.githubusercontent.com/75500068/206467993-6cee1c2e-bbcd-4f1c-b6f8-49dccd80aa7e.png)


  #####  . Les dependances :Spring Web,Spring Data JPA,H2DataBase,Lombook,Rest Repositories,Eureka Discovery Client,Spring Boot Actuator.
  #####  . Notre Base de donnees :
  
  ![Capture d’écran 2022-12-08 152209](https://user-images.githubusercontent.com/75500068/206470669-b5e46d2f-6c4c-4689-851f-d398f37a0fa3.png)

  #####  . Pour le test :http://localhost:8081/customers :
				
![Capture d’écran 2022-12-08 151637](https://user-images.githubusercontent.com/75500068/206469157-c9985eb0-993d-4a3b-a520-8465f19997fd.png)

#### 2.Créer le micro-service inventory-service qui permet de gérer les produits :

![Capture d’écran 2022-12-08 152910](https://user-images.githubusercontent.com/75500068/206472268-5e2bc872-8292-4f30-b657-1ccfa0b2ab0b.png)

  #####  . Les dependances :Spring Web,Spring Data JPA,H2DataBase,Lombook,Rest Repositories,Eureka Discovery Client,Spring Boot Actuator.
  #####  . Notre Base de donnees :
  
  ![Capture d’écran 2022-12-08 153043](https://user-images.githubusercontent.com/75500068/206472729-607c5606-6981-42e6-b646-40b051f8179e.png)

   #####  . Pour le test :http://localhost:8082/products :
   
   ![Capture d’écran 2022-12-08 153245](https://user-images.githubusercontent.com/75500068/206473252-0077eb3c-297f-49e3-b4c7-d953230fab9a.png)

#### 3. Créer la Gateway Spring cloud Gateway avec une Configuration statique du système de routage :

![Capture d’écran 2022-12-08 154038](https://user-images.githubusercontent.com/75500068/206475279-a9301f64-7488-498b-9d44-5aa7249e36e4.png)
 
   #####  . Les dependances :GateWay,Eureka Discovery Client,Spring Boot Actuator.

