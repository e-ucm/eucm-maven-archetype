# eUCM Maven Archetype

Includes plugin for eclipse formatter and Apache license.

## Installing

```
% git clone git://github.com/e-ucm/eucm-maven-archetype.git
% cd eucm-maven-archetype
% mvn install
```

## Creating a skeleton project

```
% mvn archetype:generate \
    -DarchetypeRepository=local \
    -DarchetypeRepository=$HOME/.m2/repository \
    -DarchetypeGroupId=es.e-ucm \
    -DarchetypeArtifactId=eucm-archetype \
    -DarchetypeVersion=1.0.0
```

This will then ask you a few questions:

  * Define value for property 'groupId': : **com.mytest**
  * Define value for property 'artifactId': : **artifact**
  * Define value for property 'version':  1.0-SNAPSHOT: : **<default>**
  * Define value for property 'package':  com.mytest: : **<default>**
  * Define value for property 'Year': : **Inception year of the project**
