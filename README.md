# Knowledge Base

## Table of Contents
- [IntelliJ](#intellij)

## IntellIJ

### Tips (IntelliJ)

When using a Java project that is nested (e.g., within a mono-repo), you need to define the Java folder as `Sources` folder (via right-click). Similarly, if using maven, you need to right-click on the `pom.xml` to set it as a maven project.

**Remark**: unmarking the Java project as source and re-marking it as such may solve build issues (unability to resolve some symbols). Similarly, `mvn compile` from the command line can also help in that respect. 

### Shortcuts (IntelliJ)

|Function|Key|
|--------|---|
|`Alt + Insert`|Used in `pom.xml`, allow to add a maven dependencies from the maven-central repo directly from IntelliJ|
