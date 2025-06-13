# SuperMug-Shop
Acest proiect conține două aplicații: una de **backend** (Java + Spring Boot) și una de **frontend** (Angular). Ambele trebuie pornite separat.

---
## Backend: 
Deschide aplicația în IntelliJ IDEA(sau alt IDE).Rulează aplicația apăsând pe butonul **Run**.  
Pentru acces la baza de date trebuie sa ai o conexiune (ex: creezi o conexiune pe portul 3306 in MySQLWorkbench, sau alt tool).  
In aplicatia de java adauga in fisierul 'src/main/resources/' un fisier numit "application.properties" unde vei adauga dupa egal datele tale si portul corect in functie de cum l ai configurat in MySQL:
```
spring.datasource.url=jdbc:mysql://localhost:3306/shop_db
spring.datasource.username=
spring.datasource.password=
spring.jpa.show-sql=true
spring.jpa.hibernate.ddl-auto = update
server.port= 8082
```
---  
## Frontend:  
Deschide aplicația în IntelliJ IDEA.  
Executați comanda `ng build` pentru a construi proiectul de frontend. Artefactele de compilare vor fi stocate în directorul `dist/`.   
Pentu a porni aplicatia de frontend ruleaza 'ng serve' in terminal si acceseaza linkul  care apare (http://localhost:4200/).  

