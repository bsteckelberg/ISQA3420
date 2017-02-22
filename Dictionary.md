#DFD Dictionary
###External Entities
* Developer: A person who developes something.
* Manager: A person who oversees software and policies within a company.

###Data Processes
* Create/Upload: The Creation or uploading of new policy into the system.
* Edit Policy: Editing existing policy within the system.
* L/V Info Request:The process of requesting information from the License and Vulnerability DB.
* L/V Scanner: The process that scans for licenses and vulnerabilities in new software by cross referencing the NIST vulnerability DB.
* Manage Software Code Info: The process that manages file/package, package request, package response, lincense and vulnerability info.
* Retrieve Policy Info: The process that requests information from the policy database.

###Data Flows
* File/Package: New software.
* License and Vulnerability Info.
* L/V Results: Results requested by the manager from the license and vulnerability DB.
* New Policy: New policy introduced by the manager.
* Policy Info: Information on existing policy requested by the manager from the policy DB.
* Policy Name: The name of a specific policy.
* Policy Request: A request from manager to the policy database.
* Policy Updates: Updates or edits made to policy by the manager that are sent to the policy DB.
* Software Name: The name of a specific software.

###Data Stores
* License and Vulnerability DB: The database that stores information on software that has been previously scanned for license and vulnerabilities.
* NIST Vulnerbility DB: The databse that stores information on known licenses and vulnerabilities.
* Policy Database: The database that stores information on existing policy within the company.
