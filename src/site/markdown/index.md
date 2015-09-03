## About CONGA AEM Definitions

wcm.io DevOps CONfiguration GenerAtor Roles and Templates for [Adobe Experience Manager (AEM)][aem].


### Maven Dependency

```xml
<plugin>
  <groupId>io.wcm.devops.conga</groupId>
  <artifactId>conga-maven-plugin</artifactId>
  <extensions>true</extensions>
  <dependencies>
    <dependency>
      <groupId>io.wcm.devops.conga.plugins</groupId>
      <artifactId>io.wcm.devops.conga.definitions.aem</artifactId>
      <version>0.6.2</version>
    </dependency>
  </dependencies>
</plugin>
```

### Documentation

* [Usage][usage]
* [Changelog][changelog]


### Overview

This repository contains generic role definitions and templates for CONGA-based AEM configurations. 

The definitions can be used by [CONGA - CONfiguration GenerAtor][conga] for configuring [Adobe Experience Manager (AEM)][aem] environments.

The [CONGA AEM Plugin][conga-aem] is required.



[usage]: usage.html
[changelog]: changes-report.html
[conga]: http://devops.wcm.io/conga/
[conga-aem]: http://devops.wcm.io/conga/plugins/aem/
[aem]: http://www.adobe.com/solutions/web-experience-management.html
