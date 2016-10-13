
##Entities
**Developer** – Stakeholder who codes the software packages.

**Manager** – Stakeholder in charge of the software development.

##Processes
**Manage Software package for license and Vulnerabilities scanning** – Software is scanned for licenses and vulnerabilities.

**Request Software Package and License Information** – a request is submitted for Software package license and vulnerabilities information.

**Request Software Project Policy** – project policy is requested from the “Software project License and vulnerability Policy DB”.

**Modify Project Policy** – Manager submits a midified policy document.

**Scan for Licenses** – Scans for licenses to be found in the program.

##Data Flow
**Software package name** – the name of the software package.

**Package Vulnerability result** – the result of the NIST vulnerability scan.

**Software Package** – collection of files to make up the software.

**Software Package Information result** – the results given to developer after scanning.

**Software Package License resul**t – the result of scanning software for licenses.

**Software package vulnerability and license result** - the result of scanning for licenses and vulnerability sent to the “Project license and Vulnerability DB”.

**Project Software and vulnerability request** – the request to look at all the license and vulnerability information from the project.

**Project Software and vulnerability result** – the result of project license and vulnerability scan, sent from DB to Developer or Manager.

**Project Policy Result** – retrieved from policies “software project License and vulnerability Policy DB”.

**Project Policy request** – request from developer or manager to retrieve project policy from “software project License and vulnerability Policy DB”.

**Updated Policy Document** – the updated policy document returning to manager after modifying it.

**Modified Policy Document** – the modified policy document that is sent to “Software project License and vulnerability Policy”.

##Datastores

**Project License and Vulnerability DB** – database storing the license and vulnerability information about the software packages.

**NIST Vulnerability DB** – Database storing known vulnerabilities.

**Software project License and vulnerability Policy DB** – Database storing the policy documents for the software project.
