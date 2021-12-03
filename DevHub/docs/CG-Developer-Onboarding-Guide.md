General Development Guidelines
==============================

[Open Knowledge](https://confluence.capgroup.com/display/OPEN/open.knowledge) \- Home for architectural patterns, design guidance and technology standards

[App Technology Software Stack](https://confluence.capgroup.com/display/OPEN/App+Technology+Software+Stack) - Provide a view of Capital's technology stack for building custom applications targeting deployment to public cloud or on-premise environments

  

Basic Developer Setup
=====================

##### 1\. New associate Checklist 

*   [Getting Started with Technology at Capital](http://communities/TechTrainResCenter/tipsheets/new_associate/getting_started_checklist.pdf)

##### 2\. Remote Access to CG Network

*   All ITG associates are granted VPN access by default allowing connection to CG network from home. For contractors or offshore resources, submit an [Access Central](https://accesscentral.capgroup.com/identityiq/home.jsf) request for **_SecurID RSA Token Production CBYO VDI Access_** (designated for those without CG issued laptop only)

##### 3\. Workstation Elevated Privilege

*   As a developer, you might need to run certain applications with elevated permissions or modify system-protected files/folders. CG does not provides elevated permission by default, but you can request it if this is needed to perform your daily job duties. To request elevated permission, login to [Access Central](https://accesscentral.capgroup.com/identityiq/home.jsf) and submit a request for **_Win7PLA Production Elevated User (Priv\_Level\_3)_.**  For Mac Users, submit a request for _**Mac Developer Admin Access**_ to get admin access to your Mac.

##### 4\. Business Roles

*   For access to the application portfolio your team is supporting, submit a request for the team _business role_ which will grant you all the application access across all environments. Consult your manager/team lead on the business role name you should be requesting. You can also look up the [complete list of business roles](http://teams/sites/PARC/Pages/BRDefinition.aspx) available for ITG teams which typically begins with the naming convention of _BR-ITG-xxx_

##### 5\. Source Code Control

*   Setup source code control access, Bitbucket is the CG standard for on-prem applications and GitHub is for cloud applications. 
*   For [Bitbuckets](https://atm.capgroup.com/Product/PP00003549/#top), read-only access is auto-provisioned to all developers with Solutions Engineer or Data Engineer job titles. Everyone else should request for **_Production SCM Read Only Access_** in Access Central. Additional access is required for write/update access to team specific project, which in most cases have been included in your team's business role.
*   For [GitHub](https://atm.capgroup.com/Product/PP00003965/#top), follow Instructions detailed on [GHE - New User On-boarding](https://confluence.capgroup.com/display/DE/GHE+-+New+User+On-boarding)

##### 6\. Cloud - AWS

*   If your team supports AWS applications, refer to [AWS User Guide](https://confluence.capgroup.com/display/IAM/AWS+Access+User+Guide)[Cloud Developer Quick Start Guide](https://confluence.capgroup.com/x/7xzLGQ) for instructions on how to request AWS access and list of supported tools.

  

Links to Commonly Used Tools/Services
=====================================

The following are links to most commonly tools and services used by developers.

<table class="wrapped confluenceTable"><colgroup><col></col></colgroup><tbody><tr><th class="confluenceTh">Tools/Services Name</th><th class="confluenceTh">Description</th></tr><tr><td class="confluenceTd"><a href="https://accesscentral.capgroup.com" class="external-link" rel="nofollow">Access Central</a></td><td class="confluenceTd">Access Management System for access request, access request and password reset for network and databases. See your team's onboarding checklist for the appropriate business role to or application role(s) to request.</td></tr><tr><td class="confluenceTd"><a href="http://autorep-oz:8000/autorep_dv1.html" class="external-link" rel="nofollow">Autorep Browser</a></td><td class="confluenceTd"><span style="color: rgb(23,43,77);">Batch jobs' statuses in respective environments (contains links to WCC&nbsp;– CA Workload Automation AE for batch job execution in lower environments). Note the links for each Autorep Browser environment in the left panel to navigate between environments.</span></td></tr><tr><td class="confluenceTd"><a href="https://atm.capgroup.com/" class="external-link" rel="nofollow">ATM</a></td><td class="confluenceTd">Application Technology Management - a repository of all business applications and platforms and products used in CG environment</td></tr><tr><td colspan="1" class="confluenceTd"><a href="https://bamboo.capgroup.com/allPlans.action" class="external-link" rel="nofollow">Bamboo</a></td><td colspan="1" class="confluenceTd">CG's source code build platform</td></tr><tr><td colspan="1" class="confluenceTd"><a href="https://bitbucket.capgroup.com/dashboard" class="external-link" rel="nofollow">Bitbucket</a></td><td colspan="1" class="confluenceTd">CG's source code repository</td></tr><tr><td class="confluenceTd"><a href="http://cgappstore/" class="external-link" rel="nofollow">CG AppStore</a></td><td class="confluenceTd">Repository of all CG supported applications and tools. Allows user to submit orders for tools to be deployed to and installed on their workstation</td></tr><tr><td colspan="1" class="confluenceTd"><a href="https://capgroup.okta.com/home/bookmark/0oa1fvtcsshzm0JCw1d8/2557" class="external-link" rel="nofollow">Ceridian Dayforce</a></td><td colspan="1" class="confluenceTd">Link for timesheet keeping</td></tr><tr><td class="confluenceTd"><a href="https://ark.capgroup.com/" class="external-link" rel="nofollow">CyberArk</a></td><td class="confluenceTd">Access to application vaulted accounts</td></tr><tr><td class="confluenceTd"><a href="https://confluence.capgroup.com/" rel="nofollow">Confluence</a></td><td class="confluenceTd">Content Management system</td></tr><tr><td colspan="1" class="confluenceTd"><a href="https://dgms/" class="external-link" rel="nofollow">DGMS</a></td><td colspan="1" class="confluenceTd">Distribution Group Management System - use this to manage your distribution group membership</td></tr><tr><td colspan="1" class="confluenceTd"><a href="https://github.com/The-Capital-Group-Companies-Inc" class="external-link" rel="nofollow">GitHub</a></td><td colspan="1" class="confluenceTd">Source code control tool&nbsp;</td></tr><tr><td class="confluenceTd"><a class="external-link" href="https://jira.capgroup.com/" style="text-align: left;" rel="nofollow">Jira</a></td><td class="confluenceTd">Application Issue Management system and Agile Project Management</td></tr><tr><td class="confluenceTd"><a class="external-link" href="https://capitalgroup.service-now.com/" style="text-align: left;" rel="nofollow">Service Now</a><a href="https://capitalgroup.service-now.com/nav_to.do?uri=%2Fcom.glideapp.servicecatalog_cat_item_view.do%3Fv%3D1%26sysparm_id%3D1162700edbb813408ef07c1ebf9619af%26sysparm_link_parent%3D453087b4db123b008ef07c1ebf9619eb%26sysparm_catalog%3De0d08b13c3330100c8b837659bba8fb4%26sysparm_catalog_view%3Dcatalog_default%26sysparm_view%3Dtext_search" class="external-link" rel="nofollow"> - IT Request</a></td><td class="confluenceTd">used by ITG associates when requesting a product/service from another ITG team</td></tr><tr><td colspan="1" class="confluenceTd"><a href="https://capitalgroup.service-now.com/nav_to.do?uri=%2Fcatalog_home.do%3Fv%3D1%26sysparm_catalog%3De0d08b13c3330100c8b837659bba8fb4%26sysparm_catalog_view%3Dcatalog_default%26sysparm_view%3Dtext_search" class="external-link" rel="nofollow">Service Now - Service Catalog</a></td><td colspan="1" class="confluenceTd">service catalog of all services available to be request or report through Service Now</td></tr><tr><td colspan="1" class="confluenceTd"><a href="http://communities/default.aspx" class="external-link" rel="nofollow">Sharepoint Communities</a></td><td colspan="1" class="confluenceTd"><br/></td></tr><tr><td colspan="1" class="confluenceTd"><a href="https://entlogmgmt.capgroup.com/en-US/app/launcher/home" class="external-link" rel="nofollow">Splunk</a></td><td colspan="1" class="confluenceTd">Application data Logging system <span style="color: rgb(23,43,77);">enables you to search, analyze, and visualize the data gathered from the components of your IT infrastructure or busines</span></td></tr><tr><td class="confluenceTd"><a class="external-link" href="http://wcc-oz:8080/" style="text-align: left;" rel="nofollow">WCC - CA Workload Automation AE</a></td><td class="confluenceTd">Link from appropriate environment in Autorep Browser (OZ is provided to the left for reference)</td></tr><tr><td colspan="1" class="confluenceTd"><a href="https://xldeploy.capgroup.com/" class="external-link" rel="nofollow">XLDeploy</a></td><td colspan="1" class="confluenceTd">CG's source code deployment platform</td></tr><tr><td class="confluenceTd"><a href="https://xlrelease.capgroup.com/" class="external-link" rel="nofollow">XLRelease</a></td><td class="confluenceTd">CG's code release platform</td></tr></tbody></table>

  

Commonly Used Software
======================

Software listed below are commonly used by developers in CG

Microsoft Windows User: You may request the software listed below thru [CG App Store](http://cgappstore/). Upon approval, the software will be deployed remotely and installed onto your Windows workstation.

Mac OS users: You may request the software listed below thru the native Self-Service app found on your Mac desktop.

  

| Category | 
Software

 | 

Use Case

 |
| --- | --- | --- |
| Framework | [Oracle JDK 11](http://cgappstore/esd/Items/Details?PackageId=11262) | Java Developer Kit including a JVM standard class libraries and tools required to create compile and debug Java programs to machine independent byte code. |
|   
 | [.NET Core SDK](http://cgappstore/esd/Items/Details?PackageId=11250) | .NET Core is a set of runtime library and compiler components which can be used in various configurations for device and cloud workloads. Cross platform and open source .NET Core provides a light weight development model and the flexibility to work a variety of development tools OS platforms. .NET Core is available on GitHub under the MIT license..NET Core refers to several technologies including .NET Core ASP.NET Core and Entity Framework Core. |
|   
 | [Python 3.8](http://cgappstore/esd/Items/Details?PackageId=11274) | High level general purpose programming language. |
| IDE/Editor | 

[Visual Studio Enterprise 2019](http://cgappstore/esd/Items/Details?PackageId=11424) 

 | Integrated Development Environment for technologies on the Microsoft platform C VB.NET C SQL Server etc |
|   
 | [Oracle JRE](http://cgappstore/esd/Items/Details?PackageId=11265) | Standard Java libraries and Java Virtual Machine used to execute a Java program. The JRE interprets compiled Java byte code to execute as machine specific code. |
|   
 | [SpringSource Tool suite](http://cgappstore/esd/Items/Details?PackageId=9943) | Eclipse based tool for development of Spring based applications for SpringSource Server, Apache Tomcat IBM WebShere and Oracle WebLogic. |
|   
 | [Jetbrains Toolsuite](https://miro.com/app/board/o9J_lYsTL4g=/) | The tool suite includes IDE and tools such as IntelliJ, DataGrip and PyCharm. Refer to [Jetbrain ATM entry](https://atm.capgroup.com/Product/PP00003981/#top) for more instructions and license information. For CG documentation on Jetbrains, refer to [Jetbrains All Products Pack](https://confluence.capgroup.com/x/n5FgEg) confluence page. |
|   
 | [Visual Studio Code](http://cgappstore/esd/Items/Details?PackageId=11371) | Visual Studio Code is a source code editor developed by Microsoft for Windows Linux and OS X i.e. cross platform js text editing. It includes support for debugging embedded Git control syntax highlighting intelligent code completion snippets and code refactoring. |
|   
 | [Notepad](http://cgappstore/esd/Items/Details?PackageId=8703)++ | Notepad is a free source code editor and Notepad replacement that supports several languages. Running in the MS Windows environment its use is governed by GPL License.  |
| Source Code Management | [Git](http://cgappstore/esd/Items/Details?PackageId=11074) | Open source distributed version control system. This record is for the client tool only. See Bitbucket for the on-prem Git server or GitHub for the cloud based server. |
|   
 | [Atlassian Sourcetree](http://cgappstore/esd/Items/Details?PackageId=11168) | End user GUI tool for managing source code in Git repositories. |
|   
 | [Git Credentials Manager](http://cgappstore/esd/Items/Details?PackageId=7842) |   
 |
| Diff Tool | [Beyond Compare](http://cgappstore/esd/Items/Details?PackageId=8608) | Versatile file/content comparison tool |
| Database Client | 

[Oracle 19c](http://cgappstore/esd/Items/Details?PackageId=8145)

 | 

Oracle drivers and client utilities for database connectivity

 |
|   
 | [SQL Server Database for Visual Studio 2019](http://cgappstore/esd/Items/Details?PackageId=7866) | Integrated Development Environment for technologies on the Microsoft platform (C#, VB.NET, C++, SQL Server, etc) |
|   
 | 

[Toad Data Point](http://cgappstore/esd/Items/Details?PackageId=8238)

 | Required to connect to Oracle RDBMS |
|   
 | 

[PostgreSQL ODBC](http://cgappstore/esd/Items/Details?PackageId=7820)

[PgAdmin](http://cgappstore/esd/Items/Details?PackageId=9939)

 | 

PostgreSQL ODBC allows connectivity to Cloud databases

pgAdmin is a graphical Open Source management development and administration toolor PostgreSQL Open Source Database.

 |
| Build Tool | [Nodejs](http://cgappstore/esd/Items/Details?PackageId=11433) | NodeJS is currently approved for build task managers and not approved for production Node JS Webservers. Node.js is a JavaScript runtime built on Chromes V8 JavaScript engine. Node.js uses an event driven nonblocking IO model that makes it lightweight and efficient.  |
|   
 | 

[Apache Maven](http://cgappstore/esd/Items/Details?PackageId=7064)

 | Maven can manage a project's build, reporting and documentation from a central piece of information. Use to build Java applications that require external components with transient dependencies. |
| API | [Postdot Postman](http://cgappstore/esd/Items/Details?PackageId=7395) | Postman is a tool for testing REST APIs. It provides an intuitive interface to send requests, save responses, add tests cases and create testing workflows |
| Container Tool | [Docker Desktop](http://cgappstore/esd/Items/Details?PackageId=11159) | Docker uses OS level virtualization to deliver software in packages called containers. Containers are isolated from one another and bundle their own software libraries and configuration files they can communicate with each other through well defined channels. Note that Docker desktop client is not supported on VDI and requires a physical laptop and Docker desktop requires additional prerequisites on a Windows laptop |
|   
 | [OpenShift Client 3.11](http://cgappstore/esd/Items/Details?PackageId=7810) | OpenShift Container Platform OCP formerly OpenShift Enterprise is a PaaS solution providing a container platform that brings Docker and Kubernetes to the enterprise. OCP improves developer agility and productivity, increase infrastructure and operational efficiency, and accelerate application delivery in on premise and cloud environments. |
| SSH/File Transfer Client | [VanDyke Software SecureCRT + FX 9.0.2 - User](http://cgappstore/esd/Items/Details?PackageId=11087) | SecureCRTFX provides integrated SSH client and file transfer client capabilities SFTP FTP. Provides support for SSH2 SSH1 Telnet TelnetSSL and serial protocols. |

  

  

ITG Core Access
---------------

Capital Group grants standard birthright access such as Network Domain access, Email/Outlook, Jabber and OneDrive automatically to all newly onboarded CG associates and contractors. In addition, majority of the following core/foundation access required for all ITG associates and contractors are also auto-provisioned as part of our enterprise role. For those that are listed as not auto-provisioned, an access request needs to be submitted through [Access Central](https://accesscentral.capgroup.com/identityiq/home.jsf) accordingly.

**Legend:**  

*    - Auto-provisioned
*    - Request is needed to obtain access

  

<table class="fixed-table wrapped confluenceTable"><colgroup><col style="width: 359.0px;"/><col style="width: 158.0px;"/><col style="width: 102.0px;"/><col style="width: 105.0px;"/><col style="width: 543.0px;"/></colgroup><tbody><tr><th class="confluenceTh">App Roles Granted</th><th class="confluenceTh">System</th><th colspan="1" class="confluenceTh">Associate</th><th colspan="1" class="confluenceTh">Contractors</th><th colspan="1" class="confluenceTh">Additional Comments</th></tr><tr><td class="confluenceTd"><p>Sharepoint ITG Users</p></td><td class="confluenceTd"><a href="https://atm.capgroup.com/Product/PP00002755/#top" class="external-link" rel="nofollow">Sharepoint</a></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-tick" src="images/icons/emoticons/check.svg" data-emoticon-name="tick" alt="(tick)"/></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-tick" src="images/icons/emoticons/check.svg" data-emoticon-name="tick" alt="(tick)"/></td><td colspan="1" class="confluenceTd">Additional access is required for write/update access to team specific sites depending on the site permission.</td></tr><tr><td class="confluenceTd">ITR_CG_ServiceNow_IT_Basic_Access</td><td class="confluenceTd"><a href="https://atm.capgroup.com/Application/AA00002677/#top" class="external-link" rel="nofollow">ServiceNow</a></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-tick" src="images/icons/emoticons/check.svg" data-emoticon-name="tick" alt="(tick)"/></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-tick" src="images/icons/emoticons/check.svg" data-emoticon-name="tick" alt="(tick)"/></td><td colspan="1" class="confluenceTd"><br/></td></tr><tr><td class="confluenceTd">Slack ITG Workspace User</td><td class="confluenceTd"><a href="https://atm.capgroup.com/Application/AA00002809/#top" class="external-link" rel="nofollow">SLACK</a></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-tick" src="images/icons/emoticons/check.svg" data-emoticon-name="tick" alt="(tick)"/></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-tick" src="images/icons/emoticons/check.svg" data-emoticon-name="tick" alt="(tick)"/></td><td colspan="1" class="confluenceTd"><br/></td></tr><tr><td colspan="1" class="confluenceTd">Production Splunk Foundation Access</td><td colspan="1" class="confluenceTd"><a href="https://atm.capgroup.com/Product/PP00003239/#top" class="external-link" rel="nofollow">Splunk</a></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-tick" src="images/icons/emoticons/check.svg" data-emoticon-name="tick" alt="(tick)"/></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-tick" src="images/icons/emoticons/check.svg" data-emoticon-name="tick" alt="(tick)"/></td><td colspan="1" class="confluenceTd">Additional access is required for access to app or platform specific splunk data depending on on the permission</td></tr><tr><td colspan="1" class="confluenceTd"><p>Workload Automation DEV WCC frontend Read Write Exec</p><p><br/></p></td><td colspan="1" class="confluenceTd"><p><a href="https://atm.capgroup.com/Bundle/BB00000016/#top" class="external-link" rel="nofollow">Workload Automation</a></p><p>(Autosys)</p></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-tick" src="images/icons/emoticons/check.svg" data-emoticon-name="tick" alt="(tick)"/></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-tick" src="images/icons/emoticons/check.svg" data-emoticon-name="tick" alt="(tick)"/></td><td colspan="1" class="confluenceTd"><br/></td></tr><tr><td colspan="1" class="confluenceTd">Workload Automation Acceptance Infrastructure Frontend RX Access</td><td colspan="1" class="confluenceTd"><p><a href="https://atm.capgroup.com/Bundle/BB00000016/#top" class="external-link" rel="nofollow">Workload Automation</a></p><p>(Autosys)</p></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-tick" src="images/icons/emoticons/check.svg" data-emoticon-name="tick" alt="(tick)"/></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-tick" src="images/icons/emoticons/check.svg" data-emoticon-name="tick" alt="(tick)"/></td><td colspan="1" class="confluenceTd"><br/></td></tr><tr><td colspan="1" class="confluenceTd">Production XL Release Read Only</td><td colspan="1" class="confluenceTd"><a href="https://atm.capgroup.com/Product/PP00003717/#top" class="external-link" rel="nofollow">XL Release</a></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-tick" src="images/icons/emoticons/check.svg" data-emoticon-name="tick" alt="(tick)"/></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-tick" src="images/icons/emoticons/check.svg" data-emoticon-name="tick" alt="(tick)"/></td><td colspan="1" class="confluenceTd">Additional access is required for write/update access to team specific project</td></tr><tr><td colspan="1" class="confluenceTd">Soteria Production Read Only</td><td colspan="1" class="confluenceTd"><a href="https://atm.capgroup.com/Application/AA00002871/#top" class="external-link" rel="nofollow">Soteria</a></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-tick" src="images/icons/emoticons/check.svg" data-emoticon-name="tick" alt="(tick)"/></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-tick" src="images/icons/emoticons/check.svg" data-emoticon-name="tick" alt="(tick)"/></td><td colspan="1" class="confluenceTd"><br/></td></tr><tr><td colspan="1" class="confluenceTd">SLM User Access</td><td colspan="1" class="confluenceTd"><a href="https://atm.capgroup.com/Product/PP00003965/#top" class="external-link" rel="nofollow">Atlassian Confluence</a>/<a href="https://atm.capgroup.com/Product/PP00001971/#top" class="external-link" rel="nofollow">JIRA</a></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-tick" src="images/icons/emoticons/check.svg" data-emoticon-name="tick" alt="(tick)"/></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-tick" src="images/icons/emoticons/check.svg" data-emoticon-name="tick" alt="(tick)"/></td><td colspan="1" class="confluenceTd"><br/></td></tr><tr><td colspan="1" class="confluenceTd">Google Cloud Identity Production User</td><td colspan="1" class="confluenceTd"><a href="https://atm.capgroup.com/Application/AA00002977/#top" class="external-link" rel="nofollow">Google Cloud</a></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-tick" src="images/icons/emoticons/check.svg" data-emoticon-name="tick" alt="(tick)"/></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-tick" src="images/icons/emoticons/check.svg" data-emoticon-name="tick" alt="(tick)"/></td><td colspan="1" class="confluenceTd"><br/></td></tr><tr><td colspan="1" class="confluenceTd">SecurID Production APPL SecurID CG VPN</td><td colspan="1" class="confluenceTd"><a href="https://atm.capgroup.com/Product/PP00002157/#top" class="external-link" rel="nofollow">VPN</a></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-tick" src="images/icons/emoticons/check.svg" data-emoticon-name="tick" alt="(tick)"/></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-warning" src="images/icons/emoticons/warning.svg" data-emoticon-name="warning" alt="(warning)"/></td><td colspan="1" class="confluenceTd">For Contractors, submit request for "<em>SecurID RSA Token Production CBYO VDI Access</em>" (designated for those without CG issued laptop only)</td></tr><tr><td colspan="1" class="confluenceTd">WebEx Meeting and Hosting</td><td colspan="1" class="confluenceTd"><a href="https://atm.capgroup.com/Product/PP00002159/#top" class="external-link" rel="nofollow">Cisco Webex</a></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-tick" src="images/icons/emoticons/check.svg" data-emoticon-name="tick" alt="(tick)"/></td><td colspan="1" style="text-align: center;" class="confluenceTd"><img class="emoticon emoticon-warning" src="images/icons/emoticons/warning.svg" data-emoticon-name="warning" alt="(warning)"/></td><td colspan="1" class="confluenceTd">For Contractors, submit request for "<em>WebEx Production WebEx Contractor Access</em>" to have meeting hosting privilege.</td></tr></tbody></table>