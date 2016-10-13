##Title: Determine License and vulnerability information
**Primary Actor:** Manager

**Goal in context:** The Manager is able to determine license and vulnerability information from provided project information.

**Stakeholders:**

Manager: To receive clear and relevant software project information

Developer: To provide the relevant package information


**Preconditions:**

Relevant file/package license and vulnerability information in the database.

Proper project information has been provided

**Main Success Scenario:**

Manager receives accurate and valid license and vulnerability information for the requested software packages.

**Failed End Conditions:**

Manager receives inaccurate or invalid license and vulnerability information for the requested software packages.


**Trigger:**
Manager provides information about project which he then get license and vulnerability information from.


##Title:Developer Submit Software Package for License and Vulnerability Scan.

**Primary Actor:** Developer

**Goal in context:**

To Submit Software package for license and vulnerability scan, and return information about license and vulnerabilityies associated with the software package.

**Stakeholders:**

Developer: to code and put together a software package that is recognised by the scanning software and gets the appropriate information.

**Preconditions:**

The software package need to be complete.

Connection to both license and vulnerability databases.



**Main Success Scenario:**

The package is sent and recognised by the scanner, recieved the correct information and recorded to the license and vulnerability DB.

**Failed End Conditions:**

Developer sends a package that is not recognised by scanner.

Scanner does not find the correct, or fails to attach the information, for specified package.

information not returned to sender.

**Trigger:**

Developer sends the package to the database to scan for licenses and vulnerabilities.

##Title: Retreieve project policy for licenses and vulnerabilities.

**Primary Actor:**

Manager

Developer

**Goal in context:**

For manager and developer to request and recieve correct project license and vulnerability policy.

**Stakeholders:**

Manager: to recieve information about project license and vulnerability policy.

Developer: to recieve information about project license and vulnerability policy.

**Preconditions:**

The policies are correct and up to date.

The requested policy information is in the database.

**Main Success Scenario:**

The Developer and Manager is able to send request and retrieve the correct policies about specified project.

**Failed End Conditions:**

Request is not recognised by project license and vulnerability policy database.

Project license and vulnerability policy database fail to give correct policy or is not up to date.



**Trigger:**

Developer or Manager send a request to retrieve information about the project policy.
