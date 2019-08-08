# camarket
Hosting page here: https://emiller-spring.herokuapp.com/

## Get started with camarket locally

``` bash
# Clone the repository.
$ git clone https://github.com/ethanmiller1/Spring-Heroku.git
# Build application.
$ mvn package
# Run application.
java -jar target/dependency/webapp-runner.jar target/*.war
```

## [Deploy your application to Heroku](https://devcenter.heroku.com/articles/java-webapp-runner)

### Create a Procfile

``` bash
web: java $JAVA_OPTS -jar target/dependency/webapp-runner.jar --port $PORT target/*.war
```