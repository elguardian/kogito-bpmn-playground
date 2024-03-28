docker run --name postgres -e POSTGRES_PASSWORD=kogito-pass -e POSTGRES_USER=kogito-user -e POSTGRES_DB=kogito -p 5432:5432 -d postgres

mvn clean install -DskipTests

mvn quarkus:run


