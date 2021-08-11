# Maven Archetypes for GluonFX plugin

Maven archetypes for creating different types of Java(FX) application,
which can be compiled and run natively using [GluonFX plugin](https://docs.gluonhq.com/).

The project is a multi-module Maven project. Each module contains an archetype for creating a Java(FX) application.

### Prerequisites

* JDK 11
* Maven 3

### Install archetype locally

All archetypes are published to Maven Central. However, if you wish to install the archetypes in your local repository execute the following commands:

```
git clone https://github.com/gluonhq/gluonfx-maven-archetypes.git
cd gluonfx-maven-archetypes
mvn clean install
```

This will install all the client archetypes in your local repository.

If you wish to install just one of the archetypes, you can add the name of the project by using `-pl`:

```
mvn clean install -pl gluonfx-archetype-java
```

For more information on how to create a project from a local repository, please refer to
individual module's README.
