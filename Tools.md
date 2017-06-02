# Code Scan Tools

Here is a list of scanning tools currently being used at GSA.  It is recommended that teams look at the ServiceNow and GEAR databases for the most up-to-date approved SW.

---

#### Static code analyzers

Static code analysis = "Static analysis refers to any process for assessing code without executing it. A static analysis tool can explore a large number of “what if” scenarios without having to go through all the computations necessary to execute the code for all the scenarios. (Chest & West, [Secure Programming with Static Analysis](https://www.amazon.com/Secure-Programming-Static-Analysis-Brian/dp/0321424778/ref=sr_1_1?ie=UTF8&qid=1496348632&sr=8-1&keywords=secure+programming+with+static+analysis))."

| Product      | What it does | How it is used | How to obtain | Additional notes |
| ------------ | ------------ | -------------- | ------------- | ---------------- |
| [Fortify](https://saas.hpe.com/en-us/software/sca) | Identifies source code vulnerabilities through development lifecycle | IQ currently uses with Jenkins to support their DevOps process; product should be run regularly | Obtain through IS team.  Consider acquisition timeline, onboard effort, and deployment | Responsibility of the project team to manage execution of the product, code scans, and fixes |
| [Checkmarx](https://www.checkmarx.com/) | Provides static code analysis through development lifecycle | IC uses to test Apex code in Salesforce | New users have to conduct their own purchase | Responsibility of the project team to manage execution of the product, code scans, and fixes |
| [Jenkins](https://jenkins.io/) | Automation server for Continuous Integration/Deployment with plugins for static code analysis | Currently used in PB-ITS data center, IQ, Data.gov, and 18F DevOps processes | Licenses purchased by project team as needed | Maintenance of plug-ins including IS approval responsibility of project team |


---

#### Dynamic code analyzers

Dynamic code analysis = "Analysis of computer software that is performed by executing programs on a real or virtual processor. For dynamic program analysis to be effective, the target program must be executed with sufficient test inputs to produce interesting behavior ([Wikipedia](https://en.wikipedia.org/wiki/Dynamic_program_analysis))."

---

#### Custom scripts
