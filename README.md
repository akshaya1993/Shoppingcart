The idea behind this demo project is to build some basic shopping cart web app.

It was made using Spring Boot, Spring Security, Thymeleaf, Spring Data JPA, Spring Data REST and Docker. Database is in memory H2.

There is a login and registration functionality included.

Users can shop for products. Each user has his own shopping cart (session functionality). Checkout is transactional.


%3CmxGraphModel%3E%3Croot%3E%3CmxCell%20id%3D%220%22%2F%3E%3CmxCell%20id%3D%221%22%20parent%3D%220%22%2F%3E%3CmxCell%20id%3D%222%22%20value%3D%22%22%20style%3D%22edgeStyle%3DorthogonalEdgeStyle%3Brounded%3D0%3BorthogonalLoop%3D1%3BjettySize%3Dauto%3Bhtml%3D1%3B%22%20edge%3D%221%22%20source%3D%223%22%20target%3D%225%22%20parent%3D%221%22%3E%3CmxGeometry%20relative%3D%221%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%223%22%20value%3D%22%26lt%3Bb%26gt%3BGithub%26lt%3B%2Fb%26gt%3B%22%20style%3D%22rounded%3D1%3BwhiteSpace%3Dwrap%3Bhtml%3D1%3B%22%20vertex%3D%221%22%20parent%3D%221%22%3E%3CmxGeometry%20x%3D%2280%22%20y%3D%2280%22%20width%3D%2270%22%20height%3D%2270%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%224%22%20value%3D%22%22%20style%3D%22edgeStyle%3DorthogonalEdgeStyle%3Brounded%3D0%3BorthogonalLoop%3D1%3BjettySize%3Dauto%3Bhtml%3D1%3B%22%20edge%3D%221%22%20source%3D%225%22%20target%3D%227%22%20parent%3D%221%22%3E%3CmxGeometry%20relative%3D%221%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%225%22%20value%3D%22%26lt%3Bb%26gt%3BAmazon%20EC2%26lt%3Bspan%20style%3D%26quot%3Bcolor%3A%20rgba(0%2C%200%2C%200%2C%200)%3B%20font-family%3A%20monospace%3B%20font-size%3A%200px%3B%20text-align%3A%20start%3B%20text-wrap-mode%3A%20nowrap%3B%26quot%3B%26gt%3B%253CmxGraphModel%253E%253Croot%253E%253CmxCell%2520id%253D%25220%2522%252F%253E%253CmxCell%2520id%253D%25221%2522%2520parent%253D%25220%2522%252F%253E%253CmxCell%2520id%253D%25222%2522%2520value%253D%2522Github%2522%2520style%253D%2522rounded%253D1%253BwhiteSpace%253Dwrap%253Bhtml%253D1%253B%2522%2520vertex%253D%25221%2522%2520parent%253D%25221%2522%253E%253CmxGeometry%2520x%253D%252280%2522%2520y%253D%252280%2522%2520width%253D%252270%2522%2520height%253D%252270%2522%2520as%253D%2522geometry%2522%252F%253E%253C%252FmxCell%253E%253C%252Froot%253E%253C%252FmxGraphModel%253E%26lt%3B%2Fspan%26gt%3B%26lt%3B%2Fb%26gt%3B%22%20style%3D%22rounded%3D1%3BwhiteSpace%3Dwrap%3Bhtml%3D1%3B%22%20vertex%3D%221%22%20parent%3D%221%22%3E%3CmxGeometry%20x%3D%22190%22%20y%3D%2280%22%20width%3D%2270%22%20height%3D%2270%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%226%22%20value%3D%22%22%20style%3D%22edgeStyle%3DorthogonalEdgeStyle%3Brounded%3D0%3BorthogonalLoop%3D1%3BjettySize%3Dauto%3Bhtml%3D1%3B%22%20edge%3D%221%22%20source%3D%227%22%20target%3D%229%22%20parent%3D%221%22%3E%3CmxGeometry%20relative%3D%221%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%227%22%20value%3D%22%26lt%3Bb%26gt%3BApache%20Maven%26lt%3B%2Fb%26gt%3B%20Compile%26lt%3Bdiv%26gt%3B%2B%26lt%3B%2Fdiv%26gt%3B%26lt%3Bdiv%26gt%3BPackage%26lt%3B%2Fdiv%26gt%3B%22%20style%3D%22rounded%3D1%3BwhiteSpace%3Dwrap%3Bhtml%3D1%3B%22%20vertex%3D%221%22%20parent%3D%221%22%3E%3CmxGeometry%20x%3D%22310%22%20y%3D%2280%22%20width%3D%2270%22%20height%3D%2270%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%228%22%20value%3D%22%22%20style%3D%22edgeStyle%3DorthogonalEdgeStyle%3Brounded%3D0%3BorthogonalLoop%3D1%3BjettySize%3Dauto%3Bhtml%3D1%3B%22%20edge%3D%221%22%20source%3D%229%22%20target%3D%2211%22%20parent%3D%221%22%3E%3CmxGeometry%20relative%3D%221%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%229%22%20value%3D%22ECR%22%20style%3D%22rounded%3D1%3BwhiteSpace%3Dwrap%3Bhtml%3D1%3B%22%20vertex%3D%221%22%20parent%3D%221%22%3E%3CmxGeometry%20x%3D%22430%22%20y%3D%2280%22%20width%3D%2270%22%20height%3D%2270%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2210%22%20value%3D%22%22%20style%3D%22edgeStyle%3DorthogonalEdgeStyle%3Brounded%3D0%3BorthogonalLoop%3D1%3BjettySize%3Dauto%3Bhtml%3D1%3B%22%20edge%3D%221%22%20source%3D%2211%22%20target%3D%2212%22%20parent%3D%221%22%3E%3CmxGeometry%20relative%3D%221%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2211%22%20value%3D%22Trivy%22%20style%3D%22rounded%3D1%3BwhiteSpace%3Dwrap%3Bhtml%3D1%3B%22%20vertex%3D%221%22%20parent%3D%221%22%3E%3CmxGeometry%20x%3D%22430%22%20y%3D%22230%22%20width%3D%2270%22%20height%3D%2270%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2212%22%20value%3D%22Docker%22%20style%3D%22whiteSpace%3Dwrap%3Bhtml%3D1%3Brounded%3D1%3B%22%20vertex%3D%221%22%20parent%3D%221%22%3E%3CmxGeometry%20x%3D%22255%22%20y%3D%22235%22%20width%3D%22120%22%20height%3D%2260%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2213%22%20value%3D%22Repo%22%20style%3D%22text%3Bhtml%3D1%3Balign%3Dcenter%3BverticalAlign%3Dmiddle%3BwhiteSpace%3Dwrap%3Brounded%3D0%3B%22%20vertex%3D%221%22%20parent%3D%221%22%3E%3CmxGeometry%20x%3D%2280%22%20y%3D%22160%22%20width%3D%2260%22%20height%3D%2230%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2214%22%20value%3D%22VM%26lt%3Bspan%20style%3D%26quot%3Bcolor%3A%20rgba(0%2C%200%2C%200%2C%200)%3B%20font-family%3A%20monospace%3B%20font-size%3A%200px%3B%20text-align%3A%20start%3B%20text-wrap-mode%3A%20nowrap%3B%26quot%3B%26gt%3B%253CmxGraphModel%253E%253Croot%253E%253CmxCell%2520id%253D%25220%2522%252F%253E%253CmxCell%2520id%253D%25221%2522%2520parent%253D%25220%2522%252F%253E%253CmxCell%2520id%253D%25222%2522%2520value%253D%2522Repo%2522%2520style%253D%2522text%253Bhtml%253D1%253Balign%253Dcenter%253BverticalAlign%253Dmiddle%253BwhiteSpace%253Dwrap%253Brounded%253D0%253B%2522%2520vertex%253D%25221%2522%2520parent%253D%25221%2522%253E%253CmxGeometry%2520x%253D%252280%2522%2520y%253D%2522160%2522%2520width%253D%252260%2522%2520height%253D%252230%2522%2520as%253D%2522geometry%2522%252F%253E%253C%252FmxCell%253E%253C%252Froot%253E%253C%252FmxGraphModel%253E%26lt%3B%2Fspan%26gt%3B%22%20style%3D%22text%3Bhtml%3D1%3Balign%3Dcenter%3BverticalAlign%3Dmiddle%3BwhiteSpace%3Dwrap%3Brounded%3D0%3B%22%20vertex%3D%221%22%20parent%3D%221%22%3E%3CmxGeometry%20x%3D%22195%22%20y%3D%22160%22%20width%3D%2260%22%20height%3D%2230%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2215%22%20value%3D%22ECR%22%20style%3D%22text%3Bhtml%3D1%3Balign%3Dcenter%3BverticalAlign%3Dmiddle%3BwhiteSpace%3Dwrap%3Brounded%3D0%3B%22%20vertex%3D%221%22%20parent%3D%221%22%3E%3CmxGeometry%20x%3D%22470%22%20y%3D%22160%22%20width%3D%2260%22%20height%3D%2230%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3CmxCell%20id%3D%2216%22%20value%3D%22Deploy%20to%20container%22%20style%3D%22text%3Bhtml%3D1%3Balign%3Dcenter%3BverticalAlign%3Dmiddle%3BwhiteSpace%3Dwrap%3Brounded%3D0%3B%22%20vertex%3D%221%22%20parent%3D%221%22%3E%3CmxGeometry%20x%3D%22285%22%20y%3D%22310%22%20width%3D%2260%22%20height%3D%2230%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3C%2Froot%3E%3C%2FmxGraphModel%3E


Configuration Files
Folder src/resources/ contains config files for shopping-cart Spring Boot application.

src/resources/application.properties - main configuration file. Here it is possible to change admin username/password, as well as change the port number.
How to run
There are several ways to run the application. You can run it from the command line with included Maven Wrapper, Maven or Docker.

Once the app starts, go to the web browser and visit http://localhost:8070/home

Admin username: admin

Admin password: admin

User username: user

User password: password

Maven Wrapper
Using the Maven Plugin
Go to the root folder of the application and type:

$ chmod +x scripts/mvnw
$ scripts/mvnw spring-boot:run
Using Executable Jar
Or you can build the JAR file with

$ scripts/mvnw clean package
Then you can run the JAR file:

$ java -jar target/shopping-cart-0.0.1-SNAPSHOT.jar
Maven
Open a terminal and run the following commands to ensure that you have valid versions of Java and Maven installed:

$ java -version
java version "1.8.0_102"
Java(TM) SE Runtime Environment (build 1.8.0_102-b14)
Java HotSpot(TM) 64-Bit Server VM (build 25.102-b14, mixed mode)
$ mvn -v
Apache Maven 3.3.9 (bb52d8502b132ec0a5a3f4c09453c07478323dc5; 2015-11-10T16:41:47+00:00)
Maven home: /usr/local/Cellar/maven/3.3.9/libexec
Java version: 1.8.0_102, vendor: Oracle Corporation
Using the Maven Plugin
The Spring Boot Maven plugin includes a run goal that can be used to quickly compile and run your application. Applications run in an exploded form, as they do in your IDE. The following example shows a typical Maven command to run a Spring Boot application:

$ mvn spring-boot:run
Using Executable Jar
To create an executable jar run:

$ mvn clean package
To run that application, use the java -jar command, as follows:

$ java -jar target/shopping-cart-0.0.1-SNAPSHOT.jar
To exit the application, press ctrl-c.

Docker
It is possible to run shopping-cart using Docker:

Build Docker image:

$ mvn clean package
$ docker build -t shopping-cart:dev -f docker/Dockerfile .
Run Docker container:

$ docker run --rm -i -p 8070:8070 \
      --name shopping-cart \
      shopping-cart:dev
Helper script
It is possible to run all of the above with helper script:

$ chmod +x scripts/run_docker.sh
$ scripts/run_docker.sh
Docker
Folder docker contains:

docker/shopping-cart/Dockerfile - Docker build file for executing shopping-cart Docker image. Instructions to build artifacts, copy build artifacts to docker image and then run app on proper port with proper configuration file.
Util Scripts
scripts/run_docker.sh.sh - util script for running shopping-cart Docker container using docker/Dockerfile
Tests
Tests can be run by executing following command from the root of the project:

$ mvn test
Helper Tools
HAL REST Browser
Go to the web browser and visit http://localhost:8070/

You will need to be authenticated to be able to see this page.

H2 Database web interface
Go to the web browser and visit http://localhost:8070/h2-console

In field JDBC URL put

jdbc:h2:mem:shopping_cart_db
In /src/main/resources/application.properties file it is possible to change both web interface url path, as well as the datasource url.
