# Code Scan Tools

Beginning the initial thoughts around tools for code scanning.

Consider:

- application vs. code scans
- static code scans
- dynamic code scans
- open source tools, cloud tools
- 18F tools
- custom scripts by GSA CTO, others
- other tools at GSA approved for use or in process
- DHS SWAMP

---

#### The following are approved tools at GSA to use for code scanning:

---

#### Static code analyzers

| Product      | What it does | How it is used | How to obtain | Additional notes |
| ------------ | ------------ | -------------- | ------------- | ---------------- |
| [Fortify](https://saas.hpe.com/en-us/software/sca) | Identifies source code vulnerabilities in the software development lifecycle. | IQ currently uses with Jenkins to support their DevOps process.  Needs to be integrated in development process to not get inundated with irregular code scan output, teams will want to conduct regular and frequent scans. | Obtain through IS team.  Consider acquisition timeline, onboard effort, and deployment. | Responsibility of the project team using the product to manage execution of the product, code scans, and fixes.  IS can support assist but will not maintain on regular basis. |
| [Checkmarx](https://www.checkmarx.com/) | Provides static code analysis and implemented to interact with full software development lifecycle. | Primarily used to test Apex code in Salesforce. | Salesforce team as 10 licenses.  New users would need to consider their own purchase through acquisition. | Responsibility of the project team. Consider acquisition and implementation time. |

#### Other analysis tools (TBD)


#### Custom scripts




---

#### The following tools are being used at GSA and are working through approval process:
