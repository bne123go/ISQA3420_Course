//Each of the listed terms contain a classification tag based on how its classified in the Data Flow Diagram (ex. Entity, Process, Data Flow, Data Repository, etc.). Order is from A to Z. //

Corporate Manager: Entity: Ensures that the developer is developing the product that reach organizational needs and goals. Observes and identifies the software packages within OSS Database, conducts review of policies, provides updates and changes to policies, and ultimately updates the policy records in Policy Databases. 

Implementation of Open Source Software: DFD Document: The DFD design documentation used to describe the implementation of Open Source Software within our organizational structure. This DFD focuses on the initial implementation of a new software package.

License Results: Data Flow: During the software package validation process, these results from the Fossology application scan is reported back as this data. Results are a list of all the validated and invalidated licenses that make up that software package. 

NIST Vulnerability Database: Data Repository: During the software package validation process, the information delivered and received for a vulnerability scan is submitted to this database per validation review. 

OSS Compound Database: Data Repository: Once the software package validation process is complete, the vulnerability and license results are submitted to this database. It is a composite site that contains all the previously validated OSS packages. Managers and Developers can review packages (by name) and then receive that packages content report.  

Package Report: Data Flow: The request of package content (to include licenses, vulnerabilities, and policies). Can be requested for review and updating by the manager or by the developer to aid in development. 

Package Report Requests: Process: Per review of items listed in the OSS Compound Database, manager or developer can request individual packages based off their name, and review the package content. Managers typically compare and update policies from this process, developers may request for development aid.

Policy Compare & Review: Process: Managers may request package reports, more specifically the policy report and conduct reviews of that policy. They may implement changes or update the package report as ‘no changes’ made. 

Policy Database: Data Repository: When a manager is conducting a compare and review of package policies, they will review the current package policies with the policies reported in this database. This insures up-to-date policies for each software package. 

Policy Updates: Data Flow: Whenever the corporate manager decides to do a policy compare and review, the policy report will be updated (with possible changes) and this data is then pushed back to the OSS Compound DB. 

Policy Report: Data Flow: Whenever the corporate manager decides to do a policy compare and review, the policy report will be requested as this data and is then pushed to the policy DB. 

Scanner (Fossology Application): Process: During the software package validation process, the software package is ran through this additional process to obtain the license results. Will return license results to the validation process.

Software Name: Data Flow: The means of software package identification. Many applications require the submission of this data name to then proceed with the necessary processes. 

Software Package: Data Flow: The physical content of a software package that is pushed from the developer, reviewed in the software package validation process, and then in the scanner process. 

Software Package Validation: Process: Per review of licenses and vulnerabilities for a submitted software package. Developers will request a review on package content and once this process is complete it will deliver a confirmation report to the developer. Information is distributed amongst the NIST Vulnerability DB and the Fossology scanner. 

Submission Confirmation: Data Flow: The data that is delivered to the developer once software package validation has been completed. 

System Developer: Entity: Develops the necessary products for organizational needs and goals. Will deliver the necessary data to conduct validation process, and can also request a review of policies.

Vulnerability Results: Data Flow: During the software package validation process, after the NIST Vulnerabilities DB has completed its review on package vulnerabilities, it will push this report back to the validation process. 
