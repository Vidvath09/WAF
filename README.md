
# Masters-Dissertation
# Title: Evaluating web Application Firewalls (WAFs) Against Modern Cyber Threats

# Abstract
These days, virtually all organizations have web applications as prime targets for cyberattack, mainly because of their widespread usage, and access over the internet, which exposes sensitive data. Since SQL injections, cross site scripting (XSS), DDoS attacks to name a few, continue to evolve as a threat to application security, we must constantly look for new measures and migrate to new ones because existing measures are insufficient. Web Application Firewalls (WAFs) are an important layer of defense that is designed to scan, filter and block malicious http/s data from reaching the application layer. Yet, how well WAFs can detect and abate advanced and real world attacks, strongly depends on the underlying architecture, deployment configuration and detection mechanisms of these solutions. The main contribution of this project is to empirically evaluate the detection accuracy, performance impact, and operational efficiency of numerous widely used WAF’s, including both open source and commercial WAF’s, under a multitude of modern attacks. 
To simulate real attack traffic in attempt to find susceptibility, it designed a controlled testbed environment in which tools such as LOIC, SQLMap, and custom XSS payloads are run against vulnerable applications behind WAF. Metrics for evaluation of WAF are latency, detection rate, false positive and negative rate, as well as System resource consumption. The overall contribution of this work is to offer cyber security practitioners and organizations an evidence basis for which WAFs provide the best protection practices at specific threat model and deployment context. This research also adds to the realm of cybersecurity by placing such tradeoffs in a practical light and offering a standardized methodology for WAF evaluation. In the end, this work provides a basis for more knowledgeable decisions regarding the protection of web applications in a time when such threats are becoming even more intricate.

# Introduction

With the rapid rise of web-based technologies, correspondingly, there is an unprecedented rise in numbers as well as complexities of cyber threats that are targeted at web applications. SQL Injection (SQLi), Cross-Site Scripting (XSS), and Distributed Denial of Service (DDoS) attacks draw the most weight and are still by far some of the most commonly executed and damaging forms of attacks facing any web infrastructure. The availability of automated attack tools and further entrenchment of exploit kits in an ever-growing public domain have leveled the playing field for attackers wishing to use past exploits to attack, exfiltrate, and disrupt web operations. In thwarting these threats, the Web application firewall provides an approach that has become an indispensable security mechanism. The operation of a WAF involves filtering, logging, monitoring, and blocking HTTP/S traffic to and from a web application, based on a set of rules or conditions that an administrator or security officer has defined. 







## Screenshots

[https://github.com/vidvath-99/WAF-/blob/11fb694bc258ef8b15b8c41aeb00e11106e5adc4/pic9.png](https://github.com/Vidvath09/WAF/blob/f39790f7eea1d638f1b6d5cc81398c7c138b50f0/pic9.png)
![Image](https://github.com/user-attachments/assets/3598d927-0060-47da-994c-6c9c61916701)

Demonstration of a Forbidden Access (403 Error) Response Triggered During SQL Injection Attempt on a Test Web Application

![Image](https://github.com/user-attachments/assets/1eef0f38-cc47-4f14-98a3-4d83bf2c6f98)

Web Application Firewall (WAF) Configuration Interface Showing Web Application Setup and Source Identity Settings in a Vulnerability Testing Environment

![Image](https://github.com/user-attachments/assets/7e513ed7-eb0d-4441-9d53-3bdc16d10a43)

Configuration of NGINX Agent Deployment Using Open-AppSec for Web Application Security in the Vulnerable Application Testbed.

![Image](https://github.com/user-attachments/assets/9d40fa17-611d-4258-9720-10f2db08b2c4)

Open-AppSec Dashboard Showing Active Linux Embedded Agent Deployment for NGINX Platform in the Vulnerable Application Environment.



