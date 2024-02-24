# Docker Image

**tag name: bahmni/openmrs**
https://github.com/DIGIIND-Healthcare/openmrs-distro-bahmni/blob/331537658fbc80dbd6f364148448d3a03de0e7d9/.github/workflows/build_publish_openmrs.yml#L58


openmrs-distro-bahmni
==================

`./mvnw clean deploy` command to create artifacts.

This command will attempt to upload & publish artifacts to https://bahmnirepo.thoughtworks.com (maven repository). You will need authorization to upload (your public key needs to be on the server). 

This distribution also includes [FHIR CDSS module](https://github.com/Bahmni/openmrs-module-cdss) and [FHIR Terminology Service Module](https://github.com/Bahmni/openmrs-module-snomed) along with other modules bundled with standard Bahmni.
More details can be found [here](https://bahmni.atlassian.net/wiki/spaces/BAH/pages/3132686337/SNOMED+FHIR+Terminology+Server+Integration+with+Bahmni)
