# repo_springboot_angular4_mongodb_rest

- Rodar Mongo Server
  mongod --dbpath "c:\desenv\gabriel\mongodb"
  
- Rodar Angular-cli
  ng serve --open
  
- Rodar backend
  Run as Java Application(TodoAplication.java)
  
  
  # Spring Boot, MongoDB, Angular-4 Restful API Tutorial

Build a Fully-Fledged Todo App with Spring Boot & MongoDB in the Backend and Angular 4 in the frontend.

## Requirements

1. Java - 1.8.x

2. Maven - 3.x.x

3. MongoDB - 3.x.x

## Steps to Setup

**1. Clone the application**

```bash
git clone git@github.com:callicoder/spring-boot-mongodb-angular-4.git
```

**2. Build and run the backend app using maven**

```bash
cd spring-boot-backend
mvn package
java -jar target/todoapp-1.0.0.jar
```

Alternatively, you can run the app without packaging it using -

```bash
mvn spring-boot:run
```

The backend server will start at <http://localhost:8080>.

**3. Run the frontend app using npm**

```bash
cd angular4-frontend
npm install
```

```bash
npm start
```

Frontend server will run on <http://localhost:4200>

## Learn more

You can find the tutorial for this application on my blog -

<https://www.callicoder.com/spring-boot-mongodb-angular-js-rest-api-tutorial/>
