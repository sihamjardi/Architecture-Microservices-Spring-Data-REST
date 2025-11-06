# Architecture-Microservices-Spring-Data-REST

## Structure du projet

<img width="225" height="394" alt="image" src="https://github.com/user-attachments/assets/c552f2cc-7274-4d41-b70e-9dd43ebdecc2" />

---

## Étape: Configuration du Service REST avec Spring Data REST

**Exposition Automatique des Repositories**

<img width="699" height="385" alt="Capture d&#39;écran 2025-11-05 111852" src="https://github.com/user-attachments/assets/7a42cf73-315c-4866-817b-1e923e3388ab" />

---

## Étape : Gestion des Projections avec Spring Data REST

**Utilisation des Projections dans les Requêtes**

***http://localhost:8082/api/comptes/1?projection=solde***

<img width="329" height="201" alt="Capture d&#39;écran 2025-11-05 112309" src="https://github.com/user-attachments/assets/9020c15f-eddc-4a24-87cb-e4cde6974bde" />

***http://localhost:8082/api/comptes/1?projection=mobile***

<img width="343" height="196" alt="Capture d&#39;écran 2025-11-05 112324" src="https://github.com/user-attachments/assets/cc9f61d0-6438-4172-b5da-f223b4795b89" />

--- 

## Étape : Configuration de la Pagination et du Tri

***http://localhost:8082/api/comptes?page=0&size=2\***

<img width="331" height="494" alt="Capture d&#39;écran 2025-11-05 112746" src="https://github.com/user-attachments/assets/9bd6f01a-28aa-41c6-b91e-e4debac95edf" />

***http://localhost:8082/api/comptes?page=0&size=2&sort=solde,desc***

<img width="336" height="488" alt="Capture d&#39;écran 2025-11-05 112816" src="https://github.com/user-attachments/assets/626c7608-5930-4bc9-8289-37d1db4037b0" />

---

## Étape : Gestion des Liens entre les Ressources Client et Compte

***Utilisation des Liens REST pour Naviguer entre les Ressources***

***http://localhost:8082/api/clients/1/comptes***

<img width="371" height="365" alt="Capture d&#39;écran 2025-11-06 115619" src="https://github.com/user-attachments/assets/d07e0243-100d-46fa-a2d3-dab3c254a6b0" />


***http://localhost:8082/api/comptes/1/client***

<img width="346" height="236" alt="Capture d&#39;écran 2025-11-06 115633" src="https://github.com/user-attachments/assets/f38e5527-e983-481d-8876-9d50bf1962d6" />

**Personnalisation des Relations avec les Projections**

***http://localhost:8082/api/comptes/1/client?projection=clientDetails***

<img width="679" height="292" alt="image" src="https://github.com/user-attachments/assets/1318ae53-bdd4-4e0f-a81e-db21e3c47d31" />

---

## Étape : Requêtes de Recherche par Type de Compte

**Utilisation de la Requête de Recherche par Type dans l'URL**

***http://localhost:8082/api/comptes/search/byType?t=EPARGNE***

<img width="613" height="499" alt="image" src="https://github.com/user-attachments/assets/f962c1ad-7548-4463-bec2-58fdb5dfe68a" />

***http://localhost:8082/api/comptes/search/byType?t=COURANT***

<img width="578" height="395" alt="image" src="https://github.com/user-attachments/assets/97308772-6088-4a00-b398-cca38c6b8a97" />







