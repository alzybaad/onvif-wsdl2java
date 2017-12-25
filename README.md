# onvif-wsdl2java

[ONVIF(Open Network Video Interface Forum)](https://www.onvif.org/) is a community to standardize communication between IP-based security products (like cameras).

[wsdl2java](http://cxf.apache.org/docs/wsdl-to-java.html) generates fully annotated Java code from WSDL/XSD document.

This project just download ONVIF WSDL/XSDs and generates Java files from them using Gradle.

Usage
===

### 1. Download ONVIF WSDL/XSD files
```
./gradlew downloadWsdls
```

### 2. Generate Java files
````
./gradlew wsdl2java
````
