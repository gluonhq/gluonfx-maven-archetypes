# Client Maven Archetype for simple Java application

The project is a Maven archetype for creating a simple Java application
which uses the [Gluon Client](https://docs.gluonhq.com/client/) plugin to create a native application.

### Prerequisites

* JDK 11
* Maven 3

### Create a project

You can create a new project, from the archetype, by executing the following command:

```
mvn archetype:generate \
        -DarchetypeGroupId=com.gluonhq \
        -DarchetypeArtifactId=gluonfx-archetype-java \
        -DarchetypeVersion=0.0.2 \
        -DgroupId=groupid \
        -DartifactId=artifactId \
        -Dversion=version
```

The following properties can be customized while creating the project:

| Property                     | Default Value |
| ---------------------------- | ------------- |
| gluonfx-maven-plugin-version | 0.9.0         |

For example:

```
mvn archetype:generate \
        -DarchetypeGroupId=com.gluonhq \
        -DarchetypeArtifactId=gluonfx-archetype-java \
        -DarchetypeVersion=0.0.2 \
        -DgroupId=groupid \
        -DartifactId=artifactId \
        -Dversion=version \
        -Dgluonfx-maven-plugin-version=0.9.0
```
