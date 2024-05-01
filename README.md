# Ant ivy example

This is a "Hello World" project for rapid compilation and testing of simple applications for java using ant

## Upgrade this project to Gradle
Need to migrate this project to Gradle `7.4` or above


## Getting Started

Start compile

```
ant compile
```

Start unit-tests (compile)

```
ant test
```

Start package jar (compile, test)

```
ant package 
```
or
```
ant 
```

Run jar (compile, test, package)

```
ant run 
```

Clear build dir

```
ant clean
```

## Built With

* [jUnit](https://junit.org/junit4/)
* [Ant](https://ant.apache.org/)
* [ivy](http://ant.apache.org/ivy/)

Running with Gradle after migration -

Clear build dir

```
gradle clean
```

Start compile

```
gradle build
```

Start unit-tests (compile)

```
gradle test
```
Run jar (compile, test, package)

```
gradle run 
```
