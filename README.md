# Knowledge Base

## Table of Contents
- [IntelliJ](#intellij)

## IntellIJ

### Tips (IntelliJ)

#### Project

In IntelliJ, when opening the project, select only the sub-folder of your repository that is the Java project you want to open. This will ensure IntelliJ is able to identify the roots (sources, maven, test, etc) correctly so that Intellisense is correct.

#### Sources folder

When using a Java project that is nested (e.g., within a mono-repo), you need to define the Java folder as `Sources` folder (via right-click). 

**Remark**: unmarking the Java project as source and re-marking it as such may solve build issues (unability to resolve some symbols). Similarly, `mvn compile` (if using maven) from the command line can also help in that respect. 

#### Maven
Similarly, if using maven, you need to right-click on the `pom.xml` to set it as a maven project. To build in IntelliJ using maven, one needs to delegate build tasks to maven (`File > Settings > Build, Execution, Deployment > Build Tools > Maven > Runner` and tick `Delegate IDE build/run actions to Maven`).

### Shortcuts (IntelliJ)

|Function|Key|
|--------|---|
|`Alt + Insert`|Used in `pom.xml`, allow to add a maven dependencies from the maven-central repo directly from IntelliJ|
