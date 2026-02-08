# Tree App

## Leírás
Egyszerű Spring Boot alkalmazás, amely lehetővé teszi egy kétszintű fa létrehozását, módosítását, törlését és átrendezését. Backend: Spring Boot + MongoDB. Frontend: Thymeleaf + Bootstrap + natív JavaScript.

## Követelmények
- Java 17
- Maven
- MongoDB (lokálisan vagy Docker)

## MongoDB Docker (ajánlott)
```bash
docker run -d -p 27017:27017 --name tree-mongo mongo:6.0
