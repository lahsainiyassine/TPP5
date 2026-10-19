## Architecture des packages

* ma.projet.entities : Modèles de données (entités JPA, clés composites, énumérations)
* ma.projet.dao : Interface générique IDao<T> pour les opérations de base
* ma.projet.services : Logique métier et classe AbstractFacade<T> (opérations CRUD génériques)
* ma.projet.util : Initialisation de la SessionFactory (HibernateUtil)
* ma.projet.presentation : Classe principale exécutable et scénarios de test (TestApp.java / Test.java)
* src/main/resources/config : Configuration de connexion et mapping (hibernate.cfg.xml)

Execution 1 : 
<img width="956" height="781" alt="de tp 5" src="https://github.com/user-attachments/assets/5224354f-c8fa-4d3b-aa65-673907367c36" />
Execution 2 : 
<img width="1156" height="802" alt="de tp 5 5 " src="https://github.com/user-attachments/assets/6bf274cb-10fd-497c-bb6e-8eac8f9242ac" />
Execution 3 : 
<img width="1235" height="452" alt="tp 5 5" src="https://github.com/user-attachments/assets/892b7526-fa00-4bab-b88c-d78a75b26ce5" />
