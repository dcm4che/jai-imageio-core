jai-imageio-core
================

This is a mavenized clone of the latest available version of the
[Java Advanced Imaging Image I/O Tools API Core][1] project. It
depends on native code and a JNI wrapper which binaries are
provided in the [dcm4che Maven Repository](http://www.dcm4che.org/maven2).

To build this project, use Apache Maven 3.0.5 or newer and run:
    mvn clean install


Maven repository
----------------

To use jai-imageio-core from a Maven project, add:

    <dependency>
        <groupId>com.sun.media</groupId> 
        <artifactId>jai_imageio</artifactId> 
        <version>1.2-pre-dr-b04</version> 
    </dependency>

and:

    <repositories>
        <repository>
            <id>www.dcm4che.org</id>
            <name>dcm4che Repository</name>
            <url>http://www.dcm4che.org/maven2</url>
        </repository>
    </repositories>

[1]: https://java.net/projects/jai-imageio-core
