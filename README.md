# MARCODETRABAJOanalisisWEB-uLock-
---------------------------------------------------------------
---------------------------------------------------------------
![photo_4970213542108179352_y](https://github.com/MammaniNelsonD/MARCODETRABAJOanalisisWEB-uLock-/assets/114308492/c1555554-d595-47ae-9552-29850dbec58b)

# Web Application Security Testing
---------------------------------------------------------------
---------------------------------------------------------------
![photo_4970213542108179351_x](https://github.com/MammaniNelsonD/MARCODETRABAJOanalisisWEB-uLock-/assets/114308492/8928057a-c879-474e-939a-4ae382412544)

4.0 [Introduction and Objectives](00-Introduction_and_Objectives/README.md)
---------------------------------------------------------------
---------------------------------------------------------------
![photo_4970213542108179356_x](https://github.com/MammaniNelsonD/MARCODETRABAJOanalisisWEB-uLock-/assets/114308492/dabe07b4-9da6-43df-8b9a-f08e3db0b388)

4.1 [Information Gathering](01-Information_Gathering/README.md)
---------------------------------------------------------------
---------------------------------------------------------------
![photo_4970213542108179357_x](https://github.com/MammaniNelsonD/MARCODETRABAJOanalisisWEB-uLock-/assets/114308492/7f9a5a0f-1bde-48bb-b736-cce227e51969)

4.2 [Configuration and Deployment Management Testing](02-Configuration_and_Deployment_Management_Testing/README.md)
---------------------------------------------------------------
---------------------------------------------------------------
![photo_4970213542108179358_y](https://github.com/MammaniNelsonD/MARCODETRABAJOanalisisWEB-uLock-/assets/114308492/0f43aeb3-a351-4deb-a328-0e03d5670775)

4.3 [Identity Management Testing](03-Identity_Management_Testing/README.md)
---------------------------------------------------------------
---------------------------------------------------------------
![photo_4970213542108179360_x](https://github.com/MammaniNelsonD/MARCODETRABAJOanalisisWEB-uLock-/assets/114308492/73331a0b-6b48-401c-82a3-b9e033ab9e90)

4.4 [Authentication Testing](04-Authentication_Testing/README.md)
---------------------------------------------------------------
---------------------------------------------------------------
![contraseña-insegura](https://github.com/MammaniNelsonD/MARCODETRABAJOanalisisWEB-uLock-/assets/114308492/4bad42d6-0057-4607-a6fe-95d051caf2f6)

4.5 [Authorization Testing](05-Authorization_Testing/README.md)
---------------------------------------------------------------
---------------------------------------------------------------
![OIG18](https://github.com/MammaniNelsonD/MARCODETRABAJOanalisisWEB-uLock-/assets/114308492/e8c712e5-5216-4ab1-ba70-1f8417095a80)

4.6 [Session Management Testing](06-Session_Management_Testing/README.md)
---------------------------------------------------------------
---------------------------------------------------------------
![OIG21](https://github.com/MammaniNelsonD/MARCODETRABAJOanalisisWEB-uLock-/assets/114308492/776b855e-3f68-4914-8da3-0f8f905046a5)

4.7 [Input Validation Testing](07-Input_Validation_Testing/README.md)
---------------------------------------------------------------
---------------------------------------------------------------
 ![photo_4970213542108179371_y (1)](https://github.com/MammaniNelsonD/MARCODETRABAJOanalisisWEB-uLock-/assets/114308492/1546c5fd-e1db-43bb-93c6-6d9c34766406)

4.8 [Testing for Error Handling](08-Testing_for_Error_Handling/README.md)
---------------------------------------------------------------
---------------------------------------------------------------
![synack-OWASP-top-10-blog-3 (1)](https://github.com/MammaniNelsonD/MARCODETRABAJOanalisisWEB-uLock-/assets/114308492/9f1666a9-63f5-4281-8c12-045ebba13b35)

4.9 [Testing for Weak Cryptography](09-Testing_for_Weak_Cryptography/README.md)
---------------------------------------------------------------
---------------------------------------------------------------
![business-logic-in-qa](https://github.com/MammaniNelsonD/MARCODETRABAJOanalisisWEB-uLock-/assets/114308492/5f118a18-ffc7-4fa2-93c7-45c032af23b9)

4.10 [Business Logic Testing](10-Business_Logic_Testing/README.md)
---------------------------------------------------------------
---------------------------------------------------------------
![Leonardo_Diffusion_Clientside_Testing_0](https://github.com/MammaniNelsonD/MARCODETRABAJOanalisisWEB-uLock-/assets/114308492/163aed78-27b2-4e71-ae5c-1e9b912a4678)

4.11 [Client-side Testing](11-Client-side_Testing/README.md)
---------------------------------------------------------------
---------------------------------------------------------------
![1655329582555](https://github.com/MammaniNelsonD/MARCODETRABAJOanalisisWEB-uLock-/assets/114308492/7bb0f203-912b-4239-9e4c-1e72c9019aa9)

4.12 [API Testing](12-API_Testing/README.md)
---------------------------------------------------------------
---------------------------------------------------------------



![photo_4970213542108179377_x](https://github.com/MammaniNelsonD/MARCODETRABAJOanalisisWEB-uLock-/assets/114308492/df718386-be72-43bf-9b6c-5e53ae57358e)

---------------------------------------------------------------
---------------------------------------------------------------
# Testing Tools Resource

## Introduction

This appendix is intended to provide a list of common tools that are used for web application testing. It does not aim to be a complete tool reference, and the inclusion of a tool here should not be seen as a specific endorsement of that tool by OWASP.

The list contains only tools that are freely available to download and use (although they may have licenses restricting their use for commercial activity).

## General Web Testing

### Web Proxies

- [ZAP](https://www.zaproxy.org)
    - The Zed Attack Proxy (ZAP) is an easy to use integrated penetration testing tool for finding vulnerabilities in web applications. It is designed to be used by people with a wide range of security experience and as such is ideal for developers and functional testers who are new to penetration testing.
    - ZAP provides automated scanners as well as a set of tools that allow you to find security vulnerabilities manually.
- [Burp Suite Community Edition](https://portswigger.net/burp/communitydownload)
    - Burp Suite is an intercepting proxy for security testing. It allows intercepting and modifying all HTTP(S) traffic passing in both directions, it can work with custom TLS certificates and non-proxy-aware clients.
- [Telerik Fiddler](https://www.telerik.com/fiddler)
    - Fiddler an intercepting web proxy that is primarily aimed at developers rather than penetration testers, but still provides useful functionality. It also hooks directly into the Windows HTTP APIs, allowing it to intercept traffic from some software that doesn't allow custom proxies to be set.

### Firefox Extensions

- [Firefox HTTP Header Live](https://addons.mozilla.org/en-US/firefox/addon/http-header-live)
    - View HTTP headers of a page and while browsing.
- [Firefox Multi-Account Containers](https://addons.mozilla.org/en-GB/firefox/addon/multi-account-containers/)
    - Create multiple containers, each of which have their own isolated cookies and sessions. Useful for testing access control between different users.
- [Firefox Tamper Data](https://addons.mozilla.org/en-US/firefox/addon/tamper-data-for-ff-quantum/)
    - Use Tamper Data to view and modify HTTP/HTTPS headers and post parameters
- [Firefox Web Developer](https://addons.mozilla.org/en-US/firefox/addon/web-developer/)
    - The Web Developer extension adds various web developer tools to the browser.

### Chrome Extensions

- [Chrome Web Developer](https://chrome.google.com/webstore/detail/bfbameneiokkgbdmiekhjnmfkcnldhhm)
    - The Web Developer extension adds a toolbar button to the browser with various web developer tools. This is the official port of the Web Developer extension for Chrome.
- [HTTP Request Maker](https://chrome.google.com/webstore/detail/kajfghlhfkcocafkcjlajldicbikpgnp?hl=en-US)
    - Request Maker is a tool for penetration testing. With it you can easily capture requests made by web pages, tamper with the URL, headers and POST data and, of course, make new requests
- [Cookie Editor](https://chrome.google.com/webstore/detail/fngmhnnpilhplaeedifhccceomclgfbg?hl=en-US)
    - Edit This Cookie is a cookie manager. You can add, delete, edit, search, protect and block cookies

### Testing for Specific Vulnerabilities

#### Testing for SQL Injection

- [sqlmap](http://sqlmap.org)

#### Testing TLS

- [OWASP O-Saft](https://owasp.org/www-project-o-saft/)
- [sslyze](https://github.com/nabla-c0d3/sslyze)
- [testssl.sh](https://github.com/drwetter/testssl.sh)
- [SSLScan](https://github.com/rbsec/sslscan)
- [SSLLabs](https://www.ssllabs.com/ssltest/)

#### Testing for Brute Force Attacks

##### Hash Crackers

- [John the Ripper](https://github.com/openwall/john)
- [hashcat](https://hashcat.net/hashcat/)

##### Remote Brute Force

- [ZAP](https://www.zaproxy.org)
- [Patator](https://github.com/lanjelot/patator)
- [THC Hydra](https://github.com/vanhauser-thc/thc-hydra)
- [Burp Suite Community Edition (Intruder)](https://portswigger.net/burp/communitydownload)

#### Fuzzers

- [Ffuf](https://github.com/ffuf/ffuf)
- [Wfuzz](https://github.com/xmendez/wfuzz)
- [Jdam](https://gitlab.com/michenriksen/jdam)

#### Google Hacking

- [Google Hacking database](https://www.exploit-db.com/google-hacking-database/)

#### Slow HTTP

- [Slowloris](https://github.com/gkbrk/slowloris)
- [slowhttptest](https://github.com/shekyan/slowhttptest)

### Site Mirroring

- [wget](https://www.gnu.org/software/wget/)
- [wget for windows](http://gnuwin32.sourceforge.net/packages/wget.htm)
- [curl](https://curl.haxx.se)

### Content Discovery

- [Gobuster](https://github.com/OJ/gobuster)

### Port and Service Discovery

- [Nmap](https://nmap.org/)

## Vulnerability Scanners

- [ZAP](https://www.zaproxy.org)
- [Nikto](https://cirt.net/Nikto2)
- [Nuclei](https://nuclei.projectdiscovery.io/)
- [SecOps Solution](https://secopsolution.com)

## Exploitation Frameworks

- [Metasploit](https://github.com/rapid7/metasploit-framework)
- [BeEF](https://github.com/beefproject/beef/)

## Linux Distributions

- [Kali](https://www.kali.org)
- [Parrot](https://www.parrotsec.org)
- [Samurai](https://github.com/SamuraiWTF/samuraiwtf)
- [Santoku](https://sourceforge.net/projects/santoku/)
- [BlackArch](https://blackarch.org/downloads.html)

## Source Code Analyzers

- [Spotbugs](https://spotbugs.github.io)
- [Find Security Bugs](https://find-sec-bugs.github.io)
- [phpcs-security-audit](https://github.com/squizlabs/PHP_CodeSniffer)
- [PMD](https://pmd.github.io)
- [Microsoft's .NET Analyzers](https://docs.microsoft.com/en-us/visualstudio/code-quality/install-net-analyzers)
- [SonarQube Community Edition](https://www.sonarqube.org)

## Browser Automation Tools

Browser Automation tools are used to validate the functionality of web applications. Some follow a scripted approach and typically make use of a Unit Testing framework to construct test suites and test cases. Most, if not all, can be adapted to perform security specific tests in addition to functional tests.

### Open Source Tools

- [HtmlUnit](http://htmlunit.sourceforge.net)
    - A Java and JUnit based framework that uses the Apache HttpClient as the transport.
    - Very robust and configurable and is used as the engine for a number of other testing tools.
- [Selenium](https://www.selenium.dev)
    - JavaScript based testing framework, cross-platform and provides a GUI for creating tests.
