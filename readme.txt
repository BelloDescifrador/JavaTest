
Package mvn project through docker
docker run -it --rm -v "$PWD":/app -w /app maven:3.3-jdk-8 mvn clean install

Run mvn project through docker
docker run -it --rm -v "$PWD":/app -w /app maven:3.3-jdk-8 java -cp target/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App

