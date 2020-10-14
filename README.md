# Lundergaard demo

## Installation

Download the application.
```
git clone https://github.com/ondramaz/lundergaarddemo.git  
```
or download and unzip the archive 

Build and run the application (Java 11 is required and has to be the active installation.)

```
./mvnw spring-boot:run
```

Alternatively a docker image can be built and the application can run in a docker container:

```
sudo ./mvnw spring-boot:build-image
sudo docker run -p 8080:8080 lundergaarddemo
```

## Usage

Open http://localhost:8080/