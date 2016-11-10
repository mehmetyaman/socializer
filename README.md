# socializer

Touching people via social channels

## Building

gradle clean build

## Testing

The application is tested using [vertx-unit](http://vertx.io/docs/vertx-unit/java/).

## Packaging

The application is packaged as a _fat jar_, using the 
[Maven Shade Plugin](https://maven.apache.org/plugins/maven-shade-plugin/).

## Running

Once packaged, just launch the _fat jar_ as follows:

```
java -jar target/socializer-1.0-SNAPSHOT-fat.jar
```

Then, open a browser to http://localhost:8080.

# socializer
