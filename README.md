**Vulnerability:** Cross-Site Request Forgery (CSRF)
---------------------------------------------
### Affected Product
OpenKM Community Edition
### Affected Version
Before 6.3.12
### Vulnerable URL
/admin/DatabaseQuery
### Description
A Cross-Site Request Forgery (CSRF) vulnerability was discovered in OpenKM Community Edition before version 6.3.12. The vulnerability exists in the /admin/DatabaseQuery endpoint, which allows an attacker to manipulate a victim with administrative privileges to execute arbitrary SQL commands.
### Attack Vector
An attacker can craft a malicious CSRF payload that, when executed by an administrator, can execute arbitrary SQL commands on the vulnerable system. This can lead to unauthorized data modification, extraction, or destruction.
### Impact
* Unauthorized data modification
* Unauthorized data extraction
* Unauthorized data destruction
* Elevation of privileges
### References
* OpenKM Community Edition:
* https://www.openkm.com/
* https://github.com/openkm/document-management-system
* CWE: CWE-352 (Cross-Site Request Forgery)
