# Risk Events

Risk events are events that can occur and may cause consequences. 

We use Level 1 risk events to provide a convenient grouping of Level 2 events. We reccomend using the framework at the appropriate level of granularity with regards to the risk scenarios being considered. 

Indicative impacts on the information security goals of Confidentiality, Integrity and Availability have been added where appropriate.

## External Risk Events

External Risk Events are events that may occur outside your scope of control but may still cause consequences for your organisation or it's stakeholders.

|Level 1 Events|Level 2 Events|CIA|
|-------|------|---|
|Supplier|Service Unavailability|Availability|
||Service Compromise|Confidentiality, Integrity|
||Information Breach|Confidentiality|
||Access to Our System Breach|Confidentiality, Integrity|
||Compliance Failure||
|Regulatory|Rules Change||
|Research|Critical Vulnerability Published||

## Internal Risk Events

Internal Risk Events are events that may occur within your scope of control and cause consequences for your organisation or it's stakeholders.

The Internal Risk Events are largely derived from this [ENISA](https://www.enisa.europa.eu/publications/reference-incident-classification-taxonomy/at_download/fullReport) [PDF] review of CSIRT incident taxonomies across Europe.


|Level 1 Events|Level 2 Events|CIA|
|-------|-------|---|
|Abusive Content|Harmful Speech||
||Child / Sexual / Violent Content|
||Harassment|
|Malware|Ransomware|Availability|
||Worm|Confidentiality, Integrity, Availability|
||Spyware|Confidentiality|
||Rootkit|Confidentiality, Integrity, Availability|
||Dialler||
|Availability Interuption|Distributed / Denial of Service|Availability|
||Sabotage|Integrity, Availability|
|Information Gathering|Open Source Intelligence Analysis|Confidentiality|
||Network Scanning||
||Network Sniffing|Confidentiality|
||
Social Engineering|Lies|Confidentiality, Integrity|
||Threats|Confidentiality, Integrity|
||Phishing|Confidentiality, Integrity|
||Bribes|Confidentiality, Integrity|
|Information Breach|Unathorised access to system / component|Confidentiality, Integrity|
||Unauthorised access to information|Confidentiality|
||Unauthorised sharing of information|Confidentiality|
||Unauthorised modification of information|Integrity|
||Unauthorised deletion of information|Integrity, Availability|
|Fraud|Misappropriation / misuse of resources||
||False representation||
||Theft of money||
|System Intrusion|Software Exploit|Confidentiality, Integrity|
||SQL injection|Confidentiality, Integrity|
||Cross-site scripting (XSS)|Confidentiality, Integrity|
||File Inclusion|Confidentiality, Integrity|
||Control System Bypass|Confidentiality, Integrity|
||Use of stolen credentials|Confidentiality, Integrity|
||Password brute force|Confidentiality, Integrity|
|Governance Failure|Process failure|Confidentiality, Integrity|
||Audit Failure|Confidentiality, Integrity|

