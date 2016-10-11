# External Entities
**Developer:** Employee in charge of uploading documents to the scanners and accessing policy documents

**Manager:** Company employee requesting vulnerability and license information, access, uplod, modify policy documents

# Processes
**Scanner:** Fossology scanner
**Scan Package License / Query NIST Database:** Send package to fossology to retrieve license infomration and query NIST database using package name

**Request OSS Software Information:** Queries OSS Software Components data store for relevant license and vulnerability information

**Request Policy Information:** Send a request to the Policy data store for policy documents

**Submit or Modify Policy Documents:** Allows manage to upload a new policy document or modify the existing documents

# Data Stores: 
**NIST Vulnerability Database:** Contains vulnerability information 

**OSS Software Components:** Contains vulnerability and license information

**Policy Database:** Contains policy documents

# Data Flows
**Software Package:** Package being submitted for scanning

**Package Name:** Name of package being submitted

**Vulnerability Information:** Vulnerability levels for given package

**Software License Information:** License information of a package from Fossology

**Project Name:** Name of the project 

**Project Information:** License and vulnerability information of a project

**License and Vulnerability Information:** Combined license and vulnerability information

**Policy Information Request:** Request for policy document by name

**Policy Document:** Document containing company policies

**New/Modify Document:** Manager uploading or modifying policy document
