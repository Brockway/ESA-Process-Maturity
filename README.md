# ESA-Process-Maturity
Tools to measure the maturity of Enterprise Security Architecture processes

The Arctec Enterprise Security Blueprint paper defines Enterprise Security Architecture as having 3 primary components: 
  1) Risk Management
  2) Policy and Standards
  3) Security/Design Architecture
  
These three primary components are supported through Process, Defense in Depth controls and Metrics

There are 4 defined processes in this ESA model:

  1) SDLC
  2) Identity Management
  3) Vulnerability Management
  4) Threat Management
  
In 2014 OWASP released version 2 of their Application Security Verification Standard (ASVS, it has since been updated -  https://www.owasp.org/index.php/Category:OWASP_Application_Security_Verification_Standard_Project). The ASVS is an excellent and implementable measurement of SDLC maturity. SDLC happens to be the first of the above four processes, so the thought was to apply the ASVS framework to each of the other three processes to get a more detailed picture of the maturity of them.

Most audit frameworks ask questions like "Do you perform periodic vulnerability scans? (y/n)" and are not equiped to answer the more important and real-world question of "How mature is your vulnerability management process?"

This framework is licensed under the Apache 2 license.
