# Client Maven Archetype for simple JavaFX application

The project is a Maven archetype for creating a simple JavaFX application
which uses the [Gluon Client](https://docs.gluonhq.com/client/) plugin to create a native application.

### Prerequisites

* JDK 11
* Maven 3

### Create a project from a local repository

Once you have installed the archetype locally, you can use it to create a new project using:

```
mvn archetype:generate \
        -DarchetypeGroupId=com.gluonhq \
        -DarchetypeArtifactId=client-archetype-javafx \
        -DarchetypeVersion=0.0.1 \
        -DgroupId=groupid \
        -DartifactId=artifactId \
        -Dversion=version
```

The following properties can be customized while creating the project:

| Property                    | Default Value |
| --------------------------- | ------------- |
| javafx-version              | 11            |
| javafx-maven-plugin-version | 0.0.3         |
| client-maven-plugin-version | 0.1.1         |

For example:

```
mvn archetype:generate \
        -DarchetypeGroupId=com.gluonhq \
        -DarchetypeArtifactId=client-archetype-javafx \
        -DarchetypeVersion=0.0.1 \
        -DgroupId=groupid \
        -DartifactId=artifactId \
        -Dversion=version
```
