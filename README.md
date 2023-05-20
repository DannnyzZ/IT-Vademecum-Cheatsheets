# WELCOME TO MY REPOSITORY

<p align="center">
<img src="https://i.pinimg.com/originals/71/21/d5/7121d581f292b50843cd7f70d91dd9ef.gif" width="20%">
</p>

# IT Cheatsheets

This repository contains a collection of IT cheatsheets to help you quickly reference essential information.
> You can download the chosen file in PDF/doc.x format from the catalog provided above.

## Contents
1. OSI model
2. Domain hierarchy
3. Incident handling checklist
4. Network protocols
5. HTTP response codes
6. Cryptography standards
7. Wireless networking – authentication methods/frameworks, security/network access protocols

# 1. OSI MODEL

**The OSI Model** is a conceptual framework that defines how data is transmitted between devices on a network. This cheatsheet provides information about each layer of the OSI Model, including:
- number of layer;
- name;
- function;
- type of data processed;
- common protocols and standards.

![OSI-Model Cheatsheet](https://user-images.githubusercontent.com/119814239/224482500-51d8a238-b547-4ed4-94fb-8b70b14c1198.png)

### Sources
`https://github.com/vald-phoenix/the-osi-model`

`https://www.professormesser.com/network-plus/n10-008/n10-008-video/understanding-the-osi-model-3/`

`https://www.comptia.org/blog/open-systems-interconnection-reference-model`

`Computing Technology Industry Association (CompTIA). (2021). IT Fundamentals (FC0-U61) Student Guide. Section 3.3.2 "Domain Name System (DNS)."`

# 2. DOMAIN HIERARCHY

**A Domain Hierarchy** refers to the organization of internet domains in a hierarchical structure. The top-level domain (TLD) is at the root of the hierarchy and is followed by second-level domains, third-level domains, and so on. Each level represents a more specific subdomain of the previous level. The hierarchy can be used to provide structure and organization to the internet, making it easier to find and access information.

This cheatsheet contains the hierarchy models of domains. It includes:
- Hierarchic model of domains;
- Name, functions, definitions and examples of real domains;
- Model of URL (Uniform Resource Locator), with brief description of its parts.

**All of the components are tightly connected to each other with specific colors, so it's easier to distinguish certain parts of the schema. Colors play a big role in this model, so keep that in mind while reading it.**

![Domain-Hierarchy Cheatsheet](https://user-images.githubusercontent.com/119814239/224484316-17723fa3-2864-41ee-8c10-9a8845b169a3.png)

### Sources
`Computing Technology Industry Association (CompTIA). (2021). IT Fundamentals (FC0-U61) Student Guide. Section 3.3.2 "Domain Name System (DNS)."`

# 3. INCIDENT HANDLING CHECKLIST

**An Incident Handling Checklist** is a critical document that outlines the necessary steps and procedures for responding to a security incident, such as a cyber-attack, data breach, or other types of security breaches. The purpose of the checklist is to help incident responders promptly and efficiently respond to the incident, minimize its impact on the organization, and prevent future incidents from occurring.

The Incident Handling Checklist is typically structured into three main sections:
- Detection and Analysis: This section includes steps for detecting and analyzing the incident, identifying the type and scope of the incident, and assessing its impact on the organization. This section also outlines the communication procedures and escalation protocols to follow during the incident.

- Containment, Eradication, and Recovery: This section focuses on containing the incident, eradicating the threat, and restoring normal operations. It includes procedures for isolating affected systems, removing malware or malicious actors, restoring data and systems, and verifying the integrity of the systems.

- Post-Incident Activity: This section outlines the procedures for conducting a post-incident review, documenting lessons learned, and improving incident response capabilities for future incidents. This section also includes procedures for notifying relevant stakeholders, such as customers or regulatory bodies, and complying with any legal or regulatory requirements.

Having an Incident Handling Checklist in place is essential for organizations to quickly and effectively respond to security incidents. By following a structured and well-defined incident response process, organizations can minimize the impact of the incident, protect sensitive data and systems, and maintain customer trust.

![INCIDENT HANDLING CHECKLIST](https://user-images.githubusercontent.com/119814239/224511435-113180ab-3b19-4765-ba2e-3af466a77cf2.png)

### Sources
`NIST SP 800-61`

# 4. NETWORK PROTOCOLS

**Network protocols** are sets of rules or conventions that govern the communication between devices on a computer network. These protocols define the format, timing, sequencing, and error checking used during data transmission. Network protocols also determine how devices identify each other on the network and how they establish, maintain, and terminate connections. 

This cheatsheet contains essential protocols and standards, including:
- Name of the protocol;
- Port number;
- TCP or UDP port usage;
- OSI layer;
- Essential functions;
- Possible vectors of attack;
- State of security.

The cheatsheet recognizes two states of security:

**1. Insecure**: This state is considered outdated and prone to attacks. These protocols should not be used unless there are exceptional circumstances where they must be implemented. However, in such cases, plenty of other security measures must also be included to make them safe.

**2. Secure**: This state is considered safe and should be implemented in secure environments. However, even though a protocol is considered secure, it may still be vulnerable to some attacks.

**IT IS ESSENTIAL TO NOTE THAT A PROTOCOL BEING CONSIDERED SECURE DOES NOT MEAN THAT IT CANNOT BE EXPLOITED.**

![NPC (1)](https://user-images.githubusercontent.com/119814239/224710710-e3944124-5a3e-492f-a556-0938293d236b.png)
![NPC (2)](https://user-images.githubusercontent.com/119814239/224710722-8ca5e6e7-07b0-42c5-ba1e-b4a69b19469d.png)
![NPC (3)](https://user-images.githubusercontent.com/119814239/224710742-eccc778f-0352-4a77-a1d5-cc3a448a095c.png)
![NPC (4)](https://user-images.githubusercontent.com/119814239/224710760-db7e41f5-d71d-489f-b05e-1552be411251.png)

### Sources
`Computing Technology Industry Association (CompTIA). (2021). IT Fundamentals (FC0-U61) Student Guide. Section 3.3.2 "Domain Name System (DNS)."`

`National Institute of Standards and Technology. (2020). Security and privacy controls for information systems and organizations. https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r5.pdf`

`Computing Technology Industry Association. (2021). CompTIA Security+ Certification Exam Objectives. https://www.comptia.org/certifications/security`

`MITRE Corporation. (2021). ATT&CK for Enterprise. https://attack.mitre.org/`

`MITRE Corporation. (2021). D3FEND. https://d3fend.mitre.org/`

`National Security Agency. (2019). Security Configuration Guides. https://www.nsa.gov/ia/programs/security_configuration_guides/`

`OPSEC. (2021). Open Source Intelligence. https://www.opsec.com/`

`OWASP Foundation. (2021). OWASP Top Ten Project. https://owasp.org/Top10/`

# 5. HTTP RESPONSE CODES

**HTTP response codes** are standardized status codes returned by web servers to indicate the result of a client request. They are three-digit codes that provide information about the status of the requested resource or the outcome of the server's attempt to satisfy the client's request.

This cheatsheet provides information about:
- class of the response code;
- number;
- meaning/function.

Each HTTP response code is composed of a numeric code and a descriptive phrase, separated by a space. The first digit of the numeric code indicates the response class, while the second and third digits indicate more granular information about the status of the response.

There are five classes of HTTP response codes, each with its own set of numeric codes and meaning:
- Informational response (100-199): These codes indicate that the server has received the request and is continuing to process it.
- Successful response (200-299): These codes indicate that the server successfully processed the request and returned the requested resource.
- Redirection response (300-399): These codes indicate that further action needs to be taken by the client to complete the request.
- Client error response (400-499): These codes indicate that the server was unable to process the request due to an error or invalid request from the client.
- Server error response (500-599): These codes indicate that the server encountered an error while processing the request.

![HTTP Response Codes](https://user-images.githubusercontent.com/119814239/224755907-1351e369-a002-45f1-86ea-2c726f723bfb.png)

### Sources
`Hypertext Transfer Protocol (HTTP/1.1): Status Code Definitions. (2014). IETF. https://datatracker.ietf.org/doc/html/rfc7231#section-6`

`HTTP response status codes. (2022, January 13). Mozilla. https://developer.mozilla.org/en-US/docs/Web/HTTP/Status`

# 6. CRYPTOGRAPHY STANDARDS

**Cryptography standards** are a set of protocols, algorithms, and techniques used to ensure secure communication and information exchange. They are intended to provide data confidentiality, integrity, authentication, and non-repudiation. This cheat sheet includes the following information for each standard:
- Name: the name of the cryptographic standard;
- Symmetric or asymmetric: whether the standard is based on symmetric or asymmetric encryption;
- How it works: a brief explanation of how the standard processes data (e.g., block cipher, stream cipher);
- Variations: any known variations or versions of the standard;
- Possible vectors of attacks: potential vulnerabilities or weaknesses that could be exploited by an attacker to compromise the security of the standard.

![Cryptographic Standards Cheatsheet](https://user-images.githubusercontent.com/119814239/225092084-515f5fe3-e782-48a7-8fd9-30fe2cddcd49.png)

### Sources
`National Institute of Standards and Technology (NIST) - https://www.nist.gov/`

`International Organization for Standardization (ISO) - https://www.iso.org/`

`European Telecommunications Standards Institute (ETSI) - https://www.etsi.org/`

`Schneier on Security - https://www.schneier.com/`

`Cryptography Stack Exchange - https://crypto.stackexchange.com/`

# 7. Wireless networking – authentication methods/frameworks, security/network access protocols

**Wireless network security** encompasses a range of measures, including authentication methods, security protocols, authentication frameworks, and network access protocols, aimed at ensuring the secure and authorized access to wireless networks. These components collectively establish and verify the identities of devices or users, protect the confidentiality and integrity of data transmission, and govern the communication and interaction between devices and the network infrastructure. By implementing these measures, wireless network security safeguards against unauthorized access, data breaches, and other security threats, promoting the secure and reliable operation of wireless networks.
- Name: Identifies a wireless authentication method, security protocol, authentication framework, or network access protocol.
- Encryption: Specifies the encryption techniques used to secure wireless data transmission.
- Process and Authentication: Describes the steps and methods involved in verifying the identity of devices or users connecting to the network.
- Additional Security: Includes any extra security measures provided by the wireless mechanism to enhance protection.
- Compatibility: Indicates the compatibility of the wireless mechanism with different devices, networks, or protocols.
- Security: Represents the level of security provided by the wireless mechanism, considering factors such as encryption strength, authentication robustness, and additional security features.

![wireless_protocols_Page_1](https://github.com/DannnyzZ/Cheatsheets/assets/119814239/45182467-f6af-4f28-aa64-610b6ac3b97e)
![wireless_protocols_Page_2](https://github.com/DannnyzZ/Cheatsheets/assets/119814239/657a1e35-463a-403d-b1a1-89063aa92fb9)
![wireless_protocols_Page_3](https://github.com/DannnyzZ/Cheatsheets/assets/119814239/fb19c073-7598-4b07-ac4c-64fde8f4bd10)

### Sources

`IEEE Standards Association. (n.d.). Retrieved from https://standards.ieee.org/`

`Wi-Fi Alliance. (n.d.). Retrieved from https://www.wi-fi.org/`

`IEEE Xplore. (n.d.). Retrieved from https://ieeexplore.ieee.org`

`Google Scholar. (n.d.). Retrieved from https://scholar.google.com`

`FreeRADIUS. (n.d.). Retrieved from https://freeradius.org/`

`Stallings, W. (2017). Network Security Essentials: Applications and Standards (6th ed.). Pearson.`

`Smith, G. (2010). Wi-Fi Security: The Complete Guide. McGraw-Hill Education.`

## License

This repository is licensed under the MIT License.

## Contributing

If you would like to contribute to this repository, please feel free to submit a pull request. All contributions are welcome and appreciated.
