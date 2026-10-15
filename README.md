# DNS-Security-Basics
study how DNS works and identify basic DNS security risks.


Project Overview :

This project explains the basics of the Domain Name System (DNS) and its importance in cybersecurity.
It covers how DNS resolution works, common DNS security risks, and basic techniques used to improve DNS security.

Objective :

To understand DNS from a security perspective and learn about DNS spoofing, DNSSEC, and common DNS protection methods.

Tools Used :

- Web Browser
- Google Docs

What Is DNS? 
DNS stands for Domain Name System. It translates human-readable domain names, such as "example.com", into IP addresses that computers use to communicate over the internet.

How DNS Resolution Works :

1. A user enters a domain name in a web browser.
2. The device checks its DNS cache.
3. If the answer is not cached, a DNS resolver looks up the required record.
4. The resolver obtains the answer from the appropriate DNS server.
5. The IP address is returned to the device.
6. The browser connects to the destination server.

Common DNS Security Risks :

- DNS Spoofing: Providing a false DNS response to redirect a user to an unintended destination.
- DNS Cache Poisoning: Attempting to place false DNS information in a resolver's cache.
- DNS Hijacking: Unauthorized changes to DNS settings or records.
- DNS Amplification: Abusing DNS services to contribute to denial-of-service attacks.
- DNS Tunneling: Misusing DNS queries and responses to carry hidden data.
- Phishing Domains: Using deceptive domain names to trick users.

What Is DNSSEC?
DNSSEC stands for Domain Name System Security Extensions. It uses digital signatures to help DNS resolvers verify the authenticity and integrity of DNS data.
DNSSEC does not encrypt DNS queries and does not prevent every type of cyberattack.

Basic DNS Security Practices :

- Use trusted DNS resolvers.
- Keep systems, browsers, and routers updated.
- Protect DNS provider accounts with strong passwords and multi-factor authentication.
- Enable DNSSEC where supported and configure it correctly.
- Monitor DNS logs for unusual activity.
- Use DNS filtering to block known malicious domains.
- Restrict DNS administration to authorized users.

Interview Questions :

1. What is DNS?
DNS is a system that translates domain names into IP addresses so devices can locate services on the internet.

2. What is DNS spoofing?
DNS spoofing is an attempt to provide false DNS information that may redirect a user to an unintended destination.

3. What is DNSSEC?
DNSSEC is a set of DNS security extensions that uses digital signatures to help verify DNS data.

Conclusion

DNS is an important part of internet communication.
Understanding DNS security risks helps users and organizations protect DNS records, identify suspicious activity, and improve network security.
