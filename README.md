# PDF4J ICEPDF4

Fork of icepdf version 4.4.1 version with internal re-org and enhancements.

Part of re-org project has been moved to maven project structure. New modules introduced for better management and reuse.

### Project Modules

* _**core**_ - Main ICEPDF core API with enhancements, it is pure java implementation to view Acrobat PDF files.  
* _**viewer**_ - Java Swing based application to view Acrobat PDF files.
* _**viewerapp**_ - A bundled application of viewer, self contained jar with all dependent jars included.
* _**examples**_ - Some of java examples to use ICEPDF library
* _**webviewe**r_ - A JSF 2.x based web application which uses ICEPDF library to view and transform.

***

## CORE API

ICEPDF 4 API, as is from SVN repository. Additional support classes are added to give print support form java applications.

##### Maven dependency

```xml
<dependency>  
    <groupId>org.pdf4j.icepdf</groupId>  
    <artifactId>pdf4j-icepdf-core</artifactId>  
    <version>4.5.0</version>  
</dependency>  
```

##### Java Printing

```
java -jar pdf4j-icepdf-core-4.5.0.jar -file "PDF File name" -printer "Printer Name"

Parameter details:
        -file     "pdf file name", required field
        -printer  "printer name", Optional default printer used when ignored
        -help      Print this usage help.
```

***

## Java Viewer

ICEPDF Java Viewer, as is from SVN repository. 

##### Maven dependency

```xml
<dependency>  
    <groupId>org.pdf4j.icepdf</groupId>  
    <artifactId>pdf4j-icepdf-viewer</artifactId>  
    <version>4.5.0</version>  
</dependency>  
```
##### Using Standalone Java Viewer

```
java -jar pdf4j-icepdf-viewerapp-jar-with-dependencies.jar
```
***
