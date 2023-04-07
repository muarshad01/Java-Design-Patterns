# Java-Design-Patterns
Java Design Patterns

***

## How to Install Java

Search [Java Downloads](https://www.oracle.com/java/technologies/downloads/)

```
$ java --version
$ /usr/libexec/java_home -V 

Matching Java Virtual Machines (1):
    20 (arm64) "Oracle Corporation" - "Java SE 20" /Library/Java/JavaVirtualMachines/jdk-20.jdk/Contents/Home
/Library/Java/JavaVirtualMachines/jdk-20.jdk/Contents/Home
```

```
$ /usr/libexec/java_home -v "20"

/Library/Java/JavaVirtualMachines/jdk-20.jdk/Contents/Home
```

## Export JAVA_HOME & PATH

```
unset JAVA_HOME
export JAVA_HOME=/usr/libexec/java_home
export PATH=$PATH:$JAVA_HOME/bin
```

```
$ which java

/use/bin/java
```

`/usr/bin/java` executes `$JAVA_HOME/bin/java`

***

## Useful Links

* [How to install java on mac m1 Install JDK](https://www.youtube.com/watch?v=2VxsPtZVfPE)

* [java_home and JAVA_HOME on macOS](https://medium.com/notes-for-geeks/java-home-and-java-home-on-macos-f246cab643bd)

* [Java in Visual Studio Code](https://code.visualstudio.com/docs/languages/java)

* [Java to UML Diagram using Eclipse Plugin](https://marketplace.eclipse.org/search/site/UML)

***
