# Activite-Pratique-N-4

## Objectif de l'atelier :

objectifs de l'atelier:
Récupérer le code source de l'application non sécurisé qui permet de gérer les patients (résultat de l'activité pratique N°3). Sécuriser cette application en intégrant un système d'authentification basé sur Spring security avec les trois stratégies : -InMemoryAuthentication

-JdbcAuthentication

-UserDetailsService

# Les dependances utilisées dans cet atelier sont:

-Lombok : Un outil de bibliothèque Java qui génère du code pour minimiser le code ‘boilerplate’. La bibliothèque remplace le code ‘boilerplate’ par des annotations faciles à utiliser (Exemples : @NoArgsConstructor, @Getter, @Setter…).

-Spring Web : pour créer des applications Web, y compris RESTful, à l'aide de Spring MVC. Utilise Apache Tomcat comme conteneur intégré par défaut.

-Spring DATA JPA : Pour conserver les données dans ‘SQL stores‘ avec Java Persistance API à l’aide de Spring Data et Hibernate. C'est un module qui facilite le ORM basé sur JPA. Il est utilisé avec les bases de données relationnelles.

-H2 Database : Une base de données intégrée, open source et en mémoire. C'est un système de gestion de base de données relationnelle écrit en Java. C'est une application client/serveur et elle est généralement utilisée dans les tests unitaires.

# Capture d'écrant de l'atelier
* page d'authentification:
![image](https://user-images.githubusercontent.com/109347963/232800978-01454a79-5532-4674-b6bf-854b61e3c462.png)
* L'interface si le compte est un compte USER :
![image](https://user-images.githubusercontent.com/109347963/232802787-23d1add9-72e2-4bae-ae83-e1eda04868d2.png)
* User peut chercher un patient et naviguer la pagination :
![image](https://user-images.githubusercontent.com/109347963/232803275-8cdde560-feca-4af1-b939-335e813fd538.png)
* user Logout:
![image](https://user-images.githubusercontent.com/109347963/232805009-1dd5c98c-c746-45d5-9968-7c324f15371e.png)
* Un Admin peut chercher, ajouter, modifier ou supprimer un patient :
![image](https://user-images.githubusercontent.com/109347963/232805619-a5bef8d7-3723-4dea-b1fe-6ecde0661d61.png)

