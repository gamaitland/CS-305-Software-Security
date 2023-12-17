# CS-305-Software-Security

My client Artemis Financial specializes in creating individual finance plans for its customers, including retirement, savings, insurance, and investments. As a result of modernization, Artemis Financial sought help in assessing their security vulnerabilities and potential threats.

When I found my client’s software security vulnerabilities, I explained the best next steps and recommendations to them. It is important to code securely to avoid any leaks in sensitive information or potential backdoors for attackers to exploit. Software security adds an additional layer of trustworthiness to a company’s overall wellbeing, helping their customers to feel safe who interacting with anything related to the company.

In the vulnerability assessment, it was helpful to go through the Maven Dependency Check Report to understand the software’s weaknesses. The report gave very detailed information in regards to the vulnerabilities found, and it even included links to external resources that went further in-depth.

I increased layers of security by updating extremely outdated package versions and by implementing SHA-256 to hash sensitive information sent from client to the site. In the future, I would continue to use the Dependency Check to assess vulnerabilities and start from there to decide mitigation techniques.

To make certain the code and software application were functional and secure, I initially ran the code to ensure that it built properly and securely implemented TLS. After refactoring the code, I then ran the dependency check again to cross reference any new vs old vulnerabilities,

Resources that might be helpful in the future for related tasks are resources from Oracle, the National Vulnerability Database, NIST resources, and CVE resources.

I might show future employers the final vulnerability assessment to display that I can clearly communicate vulnerabilities with specific examples and in easy to understand language for those who may not be familiar with terms.
