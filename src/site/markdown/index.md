## About CONGA AEM Definitions

wcm.io DevOps CONfiguration GenerAtor Roles and Templates for [Adobe Experience Manager (AEM)][aem].

The current version of AEM Definitions is 1.x. Guideline for migration from AEM Definitions 0.x: [Migrate from wcm.io CONGA AEM Definitions 0.x to 1.x][aem-definitions-migration]

[![Maven Central](https://img.shields.io/maven-central/v/io.wcm.devops.conga.definitions/io.wcm.devops.conga.definitions.aem)](https://repo1.maven.org/maven2/io/wcm/devops/conga/definitions/io.wcm.devops.conga.definitions.aem)


### Documentation

* [Usage][usage]
* [Changelog][changelog]


### Overview

This repository contains generic role definitions and templates for CONGA-based AEM configurations:

* [aem-cms][role-aem-cms]: Configures AEM Author and Publish instances
* [aem-dispatcher][role-aem-dispatcher]: Configures Webserver with Dispatcher module for On Premises hosting
* [aem-dispatcher-ams][role-aem-dispatcher-ams]: Configures Webserver with Dispatcher module following the Adobe Cloud Manager conventions for AMS
* [aem-dispatcher-cloud][role-aem-dispatcher-cloud]: Configures Webserver with Dispatcher module following the Adobe Cloud Manager conventions for AEM as a Cloud Service

The definitions can be used by [CONGA - CONfiguration GenerAtor][conga] for configuring [Adobe Experience Manager (AEM)][aem] environments.

The plugins [CONGA Sling Plugin][conga-sling] and [CONGA AEM Plugin][conga-aem] are required.


### Further Resources

* [wcm.io CONGA training material with exercises](https://training.wcm.io/conga/)
* [adaptTo() 2015 Talk: CONGA - Configuration generation for Sling and AEM](https://adapt.to/2015/en/schedule/conga---configuration-generation-for-sling-and-aem.html)
* [adaptTo() 2017 Talk: Automate AEM Deployment with Ansible and wcm.io CONGA](https://adapt.to/2017/en/schedule/automate-aem-deployment-with-ansible-and-wcm-io-conga.html)
* [adaptTo() 2018 Talk: Maven Archetypes for AEM & Cloud Deployment](https://adapt.to/2018/en/schedule/maven-archetypes-for-aem.html)
* [adaptTo() 2020 Talk: Use Cloud Manager to deploy CONGA-based AEM Applications](https://adapt.to/2020/en/schedule/use-cloud-manager-to-deploy-conga-based-aem-applications.html)



[usage]: usage.html
[changelog]: changes-report.html
[conga]: https://devops.wcm.io/conga/
[conga-sling]: https://devops.wcm.io/conga/plugins/sling/
[conga-aem]: https://devops.wcm.io/conga/plugins/aem/
[aem]: http://www.adobe.com/solutions/web-experience-management.html
[aem-definitions-migration]: https://wcm-io.atlassian.net/wiki/x/AQDRAw
[role-aem-cms]: https://github.com/wcm-io-devops/conga-aem-definitions/blob/develop/conga-aem-definitions/src/main/roles/aem-cms.yaml
[role-aem-dispatcher]: https://github.com/wcm-io-devops/conga-aem-definitions/blob/develop/conga-aem-definitions/src/main/roles/aem-dispatcher.yaml
[role-aem-dispatcher-ams]: https://github.com/wcm-io-devops/conga-aem-definitions/blob/develop/conga-aem-definitions/src/main/roles/aem-dispatcher-ams.yaml
[role-aem-dispatcher-cloud]: https://github.com/wcm-io-devops/conga-aem-definitions/blob/develop/conga-aem-definitions/src/main/roles/aem-dispatcher-cloud.yaml
