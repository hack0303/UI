#project ref
## maven
``
REF:https://openjfx.io/openjfx-docs/#maven``
```
<plugins>
    <plugin>
        <groupId>org.openjfx</groupId>
        <artifactId>javafx-maven-plugin</artifactId>
        <version>0.0.4</version>
        <configuration>
            <mainClass>HelloFX</mainClass>
        </configuration>
    </plugin>
</plugins>
```
````
Add the maven dependencies:


<dependencies>
  <dependency>
    <groupId>org.openjfx</groupId>
    <artifactId>javafx-controls</artifactId>
    <version>14</version>
  </dependency>
</dependencies>
````
````
Run the application (e.g. based on the HelloFX.java from the referred sample):
mvn clean javafx:run
````
###