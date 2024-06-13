# JBullet
This is an adaptation of Martin Dvorak's 2008 Java port of Bullet Physics Library. Normen Hansen and others extended it for use in JMonkeyEngine3.

Martin Dvorak's "stack-alloc" is used to instrument the class files.
JBullet also depends on the "vecmath" library for vector arithmetic.

There are now 2 branches:
1. "master", which builds the class JAR using Apache Ant, and
2. "gradle", which builds the source/javadoc JARs, the Gradle module, and the POM, using Gradle.

I would prefer to build everything using Gradle, but "stack-alloc" is closely tied to Ant.  Someday ...

## External links
+ Pre-built Maven artifacts at the Maven Central Repository:  https://search.maven.org/artifact/com.github.stephengold/jbullet/1.0.3/jar
+ JBullet project:  http://jbullet.advel.cz (or browse an [archived copy](https://web.archive.org/web/20240115031002/http://jbullet.advel.cz/))
+ Bullet Physics project:  https://pybullet.org/wordpress/
+ Another fork of JBullet:  https://github.com/CasperPas/JBullet
