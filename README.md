# List of Contents
1. [Job Roles](#job-roles)

2. [Improving Cybersecurity](#improving-cybersecurity)

3. [Security Models](#security-models)
      1. [CIA Triad](#cia-triad)
      2. [DAD Triad](#dad-triad)
      3. [The Bell-La Padula Model](#the-bell-la-padula-model)
      
4. [Trust and Access Control](#trust-and-access-control)
      1. [Principles of Privileges](#principles-of-privileges)
      2. [Zero Trust versus Trust but Verify](#zero-trust-versus-trust-but-verify)

5. [Threat Identification and Management](#threat-identification-and-management)
      1. [Threat Modeling and Incident Response](#threat-modeling-and-incident-response)
      2. [Vulnerability vs Threat vs Risk](#vulnerability-vs-threat-vs-risk)
      3. [Threat Intelligence Tools](#threat-intelligence-tools)
   
6. [Security Assessment Frameworks and Methodologies](#security-assessment-frameworks-and-methodologies)
      1. [Black, Grey, & White Box Testing](#black-grey--white-box-testing)
      2. [OWASP](#owasp)
      3. [NIST](#nist-cybersecurity-framework-11)

7. [Global Security Standards](#global-security-standards)
      1. [ISO/IEC 19249](#isoiec-19249)
      2. [ISO27001](#iso27001)

8.  [Tools (GUI)](#tools-gui)
    1.  [Autopsy](#autopsy)
    2.  [Burp Suite](#burp)
    3.  [Nessus](#nessus)
    4.  [Wireshark](#wireshark)

9. [Networking](#networking) 
    1.  [Internet Protocol (IP)](#internet-protocol-ip)
    2.  [The Router](#the-router)
    3.  [IPv4 Classes](#ipv4-classes)
    4.  [Subnetting](#subnetting)
  
10. [Web Exploitation](#web-exploitation)
    1.  [Content Discovery](#content-discovery)
    2.  [SQL Injection](#sql-injection)
    3.  [Command Injection](#command-injection)
    4.  [Directory Traversal](#directory-traversal)

11. [Reverse Engineering](#reverse-engineering)
    1.  [Assembly](#assembly)
    2.  [Disassemblers](#disassemblers)
    3.  [Decompilers](#decompilers)

12. [Cryptography](#cryptography)
    1.  [Generate Keys](#generate-keys)
    2.  [Cryptographic Methods](#cryptographic-methods)
    3.  [Encoding](#encoding)
    4.  [Hashing](#hashing)
    5.  [Ciphers](#ciphers)
    6.  [Encryption (RSA)](#encryption-rsa)

13. [Cheat Sheets](#cheat-sheets)

## Job Roles

Here are different job roles you can pursue in cybersecurity:

| Job Role                 | Average Salary (PHP) | Average Salary (USD) (Converted to PHP) | Average Salary (AUD) (Converted to PHP) |
|--------------------------|----------------------|----------------------------------------|----------------------------------------|
| Network Security Engineer| ₱900,000             | ₱4,500,000                           | ₱3,150,000                           |
| Penetration Tester       | ₱800,000             | ₱4,000,000                           | ₱2,800,000                           |
| Incident Responder       | ₱950,000             | ₱4,750,000                           | ₱3,325,000                           |
| Security Analyst         | ₱750,000             | ₱3,750,000                           | ₱2,625,000                           |
| Security Consultant      | ₱1,100,000           | ₱5,500,000                           | ₱3,850,000                           |
| Cryptographer            | ₱1,000,000           | ₱5,000,000                           | ₱3,500,000                           |
| Security Auditor         | ₱850,000             | ₱4,250,000                           | ₱2,975,000                           |
| Security Architect       | ₱1,200,000           | ₱6,000,000                           | ₱4,200,000                           |

(Note: Average salaries are approximate and can vary based on experience, location, and other factors.)

## Improving Cybersecurity

- **Practice Secure Online Behavior**
  - Be cautious while clicking on links or downloading attachments.
  - Use strong and unique passwords for each account.
  - Enable two-factor authentication whenever possible.

- **Keep Software Up to Date**
  - Regularly update operating systems, applications, and antivirus software.

- **Secure Your Network**
  - Use strong encryption and change default router passwords.
  - Enable a firewall to filter incoming and outgoing traffic.

## Finding a Job

- **Build a Strong Online Presence**
  - Create a LinkedIn profile showcasing your skills and experience.
  - Contribute to cybersecurity forums and discussions to showcase your expertise.

- **Networking**
  - Attend cybersecurity conferences, workshops, and meetups.
  - Connect with professionals in the field and learn about job opportunities.

- **Apply for Internships and Entry-Level Positions**
  - Gain practical experience through internships to enhance your resume.
  - Look for entry-level roles such as security analyst or junior penetration tester.

## Certifications

Certifications can play a significant role in your cybersecurity career. Here are some certifications tailored for both landing your first job and upskilling:

### Certifications for Landing a Job:

- **CompTIA Security+**
  - A foundational certification covering network security, cryptography, and security risk management.
  - [Learn more](https://www.comptia.org/certifications/security)

- **Certified Information Systems Security Professional (CISSP)**
  - An advanced certification focused on security architecture, engineering, and management.
  - [Learn more](https://www.isc2.org/Certifications/CISSP)

- **Certified Ethical Hacker (CEH)**
  - Designed for ethical hackers, this certification demonstrates knowledge of hacking tools and techniques.
  - [Learn more](https://www.eccouncil.org/programs/certified-ethical-hacker-ceh/)

### Certifications for Upskilling:

- **Certified Cloud Security Professional (CCSP)**
  - Focuses on cloud security, covering cloud concepts, architecture, governance, risk management, and compliance.
  - [Learn more](https://www.isc2.org/Certifications/CCSP)

- **Certified Information Security Manager (CISM)**
  - Emphasizes information risk management and governance, suitable for those interested in security policy and strategy.
  - [Learn more](https://www.isaca.org/credentialing/cism)

- **Certified Incident Handler (GCIH)**
  - Specializes in incident response and handling techniques.
  - [Learn more](https://www.giac.org/certification/certified-incident-handler-gcih)

Remember, the certifications you pursue should align with your career goals and interests. They can not only enhance your knowledge but also make you a more attractive candidate in the job market and help you stay relevant in the field.

# Principles and Standards

## Security Models
### CIA Triad
CIA Triad is a model designed to guide policies for information security within an organisation. It consists of three core principles being: Confidentiality, Integrity, and Availability.

- **Confidentiality** ensures that only the intended persons or recipients can access the data.
- **Integrity** aims to ensure that the data cannot be altered; moreover, we can detect any alteration if it occurs.
- **Availability** aims to ensure that the system or service is available when needed.

### DAD Triad
The security of a system is attacked through one of several means. It can be via the disclosure of secret data, alteration of data, or destruction of data. It is the opposite of the CIA triad.

- **Disclosure**: Unauthorized access to information. Is the opposite of confidentiality.
- **Alteration**: Unauthorized changes to information. Is the opposite of Integrity
- **Destruction**: Unauthorized or intentional destruction of information. Is the opposite of Availability

Protecting against disclosure, alteration, and destruction/denial is very important, as this protection is equivalent to working to maintain confidentiality, integrity and availability.

### The Bell-La Padula Model
The Bell-LaPadula Model aims to achieve **confidentiality** by specifying three rules:

1. **Simple Security Property**: This property is referred to as “no read up”; it states that a subject at a lower security level cannot read an object at a higher security level. This rule prevents access to sensitive information above the authorized level.
2. **Star Security Property**: This property is referred to as “no write down”; it states that a subject at a higher security level cannot write to an object at a lower security level. This rule prevents the disclosure of sensitive information to a subject of lower security level.
3. **Discretionary-Security Property**: This property uses an access matrix to allow read and write operations. An example access matrix is shown in the table below and used in conjunction with the first two properties.

The first two properties can be summarized as “write up, read down.” You can share confidential information with people of higher security clearance (write up), and you can receive confidential information from people with lower security clearance (read down).

| Subjects | Object A | Object B |
| --- | --- | --- |
| Subject 1 | Write | No access |
| Subject 2 | Read/Write | Read |

**Limitation**: It was not designed to handle file-sharing.

## Trust and Access Control
### Principles of Privileges
It is vital to administrate and correctly define the various levels of access to an individuals require. These levels are determined on two primary factors:
1. The individual's role/function within the organisation
2. The sensitivity of the information being stored on the system

When managing access rights, two crucial concepts are used: Privileged Identity Management (PIM) and Privileged Access Management (PAM).

- **PIM** is used to translate a user's role within an organisation into an access role on a system. 
- **PAM** is the management of the privileges a system's access role has, amongst other things.

What is essential when discussing privilege and access controls is the principle of least privilege. Simply, users should be given the minimum amount of privileges, and only those that are absolutely necessary for them to perform their duties. 

### Zero Trust versus Trust but Verify
Trust in cybersecurity is addressed through two key principles:

1. **Trust but Verify**: Verify the actions of trusted entities through automated security mechanisms like logs and intrusion detection.
2. **Zero Trust**: Assume no  trust and require authentication and authorization for all access, reducing the potential impact of breaches. Implementations like microsegmentation enhance security.

## Threat Identification and Management
### Threat Modeling and Incident Response
Threat modelling is the process of reviewing, improving, and testing the security protocols in place in an organisation's information technology infrastructure and services.

The threat modelling process is very similar to a risk assessment made in workplaces for employees and customers. The principles all return to:
* Preparation
* Identification
* Mitigations
* Review
  
It is, however, a complex process that needs constant review and discussion with a dedicated team. An effective threat model includes:

* Threat intelligence
* Asset identification
* Mitigation capabilities
* Risk assessment

To help with this, there are frameworks such as **STRIDE** (Spoofing identity, Tampering with data, Repudiation threats, Information disclosure, Denial of Service and Elevation of privileges) and **PASTA** (Process for Attack Simulation and Threat Analysis)

### Vulnerability vs Threat vs Risk
1. **Vulnerability**: Vulnerabilities are weaknesses that can be exploited.
2. **Threat**: A threat represents the possibility of harm resulting from the exploitation of a vulnerability.
3. **Risk**: Concerned with the likelihood of a threat actor exploiting a vulnerability and the potential impact on the business. Risk assessment involves evaluating the probability and consequences of security incidents.

### Threat intelligence Tools
- Using [UrlScan.io](https://urlscan.io/) to scan for malicious URLs.
- Using [Abuse.ch](https://abuse.ch/) to track malware and botnet indicators.
- Investigate phishing emails using [PhishTool](https://www.phishtool.com/).
- Using [Cisco's Talos Intelligence platform](https://www.talosintelligence.com/) for intel gathering.


## Security Assessment Frameworks and Methodologies

### Black, Grey & White Box Testing
There are three primary scopes when testing an application or service. 

| Box | Description |
|---|---|
| Black | This testing process is a high-level process where the tester is not given any information about the inner workings of the application or service. |
| Grey | The tester will have some limited knowledge of the internal components of the application or piece of software. |
| White | The tester will have full knowledge of the application and its expected behaviour. |

### OWASP
OWASP, the [Open Web Application Security Project](https://owasp.org/), is a nonprofit foundation that works to improve software security. It provides free, openly available articles, methodologies, documentation, tools, and technologies in the field of web application security. 

OWASP is known for its widely-referenced [OWASP Top 10](https://owasp.org/www-project-top-ten/), a standard awareness document for developers and web application security that lists the most critical security risks to web applications.

### NIST Cybersecurity Framework 1.1
The [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework) is a popular framework used to improve an organisations cybersecurity standards and manage the risk of cyber threats.

## Global Security Standards
### ISO/IEC 19249
ISO/IEC 19249 outlines architectural and design principles for creating secure IT products and systems
1. **Least Privilege**: This principle emphasizes providing the minimum permissions necessary for individuals or entities to perform their tasks. (Design Principle: 1)
2. **Attack Surface Minimization**: It focuses on reducing the potential points of attack by eliminating unnecessary services and reducing vulnerabilities. (Design Principle: 2)
3. **Centralized Parameter Validation**: This principle suggests centralizing the validation of input parameters to prevent threats that may exploit vulnerabilities. (Design Principle: 3)
4. **Centralized General Security Services**: It advocates for centralizing security services such as authentication to enhance control and reduce potential points of failure. (Design Principle: 4)
5. **Preparing for Error and Exception Handling**: This principle emphasizes designing systems to handle errors and exceptions gracefully and securely, ensuring they do not leak sensitive information. (Design Principle: 5)

The five architectural principles outlined in ISO/IEC 19249:

1. **Domain Separation**: Components are grouped into distinct entities, each with its own domain and set of security attributes. This separation helps control access and privileges. (Architectural Principle: 1)
2. **Layering**: The system is structured into abstract levels or layers, enabling the imposition of security policies at different levels and facilitating validation of system operations. (Architectural Principle: 2)
3. **Encapsulation**: Involves hiding low-level implementations and preventing direct manipulation of data by providing specific methods, similar to object-oriented programming, to ensure data integrity. (Architectural Principle: 3)
4. **Redundancy**: Ensures availability and integrity by implementing redundancy measures. Examples include redundant power supplies or RAID configurations in data storage. (Architectural Principle: 4)
5. **Virtualization**: Sharing a single set of hardware among multiple operating systems, which enhances security boundaries and containment of malicious programs, particularly relevant in the context of cloud services. (Architectural Principle: 5)

### ISO27001
ISO (the International Organization for Standardization) is a worldwide federation of national standards bodies (ISO member bodies), where ISO27001 is an international standard on how to manage information security.

An ISMS consists of the policies, procedures, guidelines, and associated resources and activities, collectively managed by an organization, in the pursuit of protecting its information assets. 

It is a systematic approach for establishing, implementing, operating, monitoring, reviewing, maintaining and improving an organization’s information security to achieve business objectives. It is based on a risk assessment and the organization’s risk acceptance levels designed to effectively treat and manage risks.

# Tools (GUI) 
## Autopsy
`TO BE ADDED`

## Burp 
[Burp Suite](https://portswigger.net/burp), a framework of web application pentesting tools, is widely regarded as the de facto tool to use when performing web app testing

### Setting up Burp Suite
Download Burp Suite [here](https://portswigger.net/burp/communitydownload).  
Burp Suite requires Java JRE in order to run. Download and install Java [here](https://www.java.com/en/download/).

### Gettin' CA Certified
We need to install a CA certificate as BurpSuite acts as a proxy between your browser and sending it through the internet - It allows the BurpSuite Application to read and send on HTTPS data. 

1. Download [Foxy Proxy](https://addons.mozilla.org/en-US/firefox/addon/foxyproxy-standard/) in order to fully leverage the proxy, we'll have to install the CA certificate included with Burp Suite (otherwise we won't be able to load anything with SSL).
2. Now click on the extension -> Options -> Add -> Fill in the fields with the following values:  
   1. Title = Burp  
   2. Proxy type = HTTP  
   3. Proxy IP adress or DNS name = `127.0.0.1`  
   4. Port = `8080`  
   5. Username and password is optional.  
3. And hit save.  
4. Finally, click on the FoxyProxy extension icon again and select 'Burp'.
5. With Firefox, navigate to the following address: `http://localhost:8080`
6. Click on 'CA Certificate' in the top right to download and save the CA Certificate.
7. Now that we've downloaded the CA Certificate, move over to the settings menu in Firefox. Search for 'Certificates' in the search bar.
8. Click on 'View Certificates'. Next, in the Authorities tab click on 'Import' and then OK.

### Overview of Features
* **Proxy** - Burp Proxy allows us to intercept and modify requests/responses when interacting with web applications.
* **Target** - How we set the scope of our project. We can also use this to effectively create a site map of the application we are testing.
* **Intruder** - Incredibly powerful tool for everything from field fuzzing to credential stuffing and more
* **Repeater** - Allows us to capture, modify, then resend the same request numerous times. This feature can be absolutely invaluable, especially when we need to craft a payload through trial and error (e.g. in an SQLi -- Structured Query Language Injection) or when testing the functionality of an endpoint for flaws.
* **Sequencer** - Analyzes the 'randomness' present in parts of the web app which are intended to be unpredictable. This is commonly used for testing session cookies.
* **Decoder** - As the name suggests, Decoder is a tool that allows us to perform various transforms on pieces of data. These transforms vary from decoding/encoding to various bases or URL encoding.
* **Comparer** - Comparer as you might have guessed is a tool we can use to compare different responses or other pieces of data such as site maps or proxy histories (awesome for access control issue testing). This is very similar to the Linux tool diff.
* **Extender** - Similar to adding mods to a game like Minecraft, Extender allows us to add components such as tool integrations, additional scan definitions, and more!
* **Scanner** - Automated web vulnerability scanner that can highlight areas of the application for further manual investigation or possible exploitation with another section of Burp. This feature, while not in the community edition of Burp Suite, is still a key facet of performing a web application test.

### Benefits
1. Requests will by default require our authorization to be sent.
2. We can modify our requests in-line similar to what you might see in a man-in-the-middle attack and then send them on.
3. We can also drop requests we don't want to be sent. This can be useful to see the request attempt after clicking a button or performing another action on the website. 
4. And last but not least, we can send these requests to other tools such as Repeater and Intruder for modification and manipulation to induce vulnerabilities

### Notes
* URL Encode with Burp Suite: `Ctrl + U` to make a payload safe to send.
* Intruder attack types:
  * **Sniper**: Sends a single request to each selected item, typically used for targeted attacks. (e.g. a password bruteforce if we know the username)
  * **Battering ram**: Sends multiple identical requests to selected items, ideal for brute force attacks.
  * **Pitchfork**: Sends a combination of two payloads, one to the first item and another to the second item, useful for testing parameter-level vulnerabilities. (e.g. we know the username and password for a user)
  * **Cluster bomb**: Sends multiple payloads to each selected item, useful for discovering new vulnerabilities. (tries every combination of values)
* Python modules can be installed from the BApp Store, by downloading [Jython Jar file](https://www.jython.org/download) and placing it in the extender -> options -> python environment.
* Extensions can be created using the [Burp Extender API](https://portswigger.net/burp/extender/api) with either Java, Python or Ruby.

## Nessus
[Nessus](https://www.tenable.com/products/nessus) is a GUI based vulnerability scanner

### Download and installation
1. Click [here](https://www.tenable.com/products/nessus/nessus-essentials) and register an account.
2. Download the Nessus-#.##.#-debian6_amd64.deb file
3. Navigate to the download and run the following command: `sudo dpkg -i package_file.deb`
4. Start the nessus service wit the command: `sudo /bin/systemctl start nessusd.service` 
5. Open up Firefox and goto the following URL: `https://localhost:8834/` (Accept risk in case you get prompted)
6. Choose "Nessus Essentials" and click next. Skip when asked for a activation code
7. Login with your account
8. Wait for installation and then login again

### Navigation and Scans
Launch a scan = Hit the "New Scan"    
Side menu option that allows us to create custom templates = Policies    
Change plugin properties such as hiding them or changing their severity = Plugin rules  

### Scans
![Nessus Scans](Images/Nessus.png)

## Wireshark
[Wireshark](https://www.wireshark.org) is a tool used for creating and analyzing PCAPs (network packet capture files)  

Since this section is very large, I've created an individual page for this, which can be found inside this repository by clicking [here](More/Wireshark/README.md).

# Networking  
This section will cover the basics of networking, such as IP addresses, ports, protocols, etc.

## IP
An IP address is a unique address that identifies a device on the internet or a local network. IP stands for "Internet Protocol," which is the set of rules governing the format of data sent via the internet or local network.

Example: 192.168.1.204

**Reserved local IP addresses**  
192.168.1.0 = The network address  
192.168.1.1 = The default getaway (router)  
192.168.1.255 = The broadcast address  

If you send something to the broadcast address, the message will be broadcasted to everybody else on the network.

### IPv4
IP addresses consists of 32 bits:   
11000000.10101000.00000001.11001100 = 192.168.1.204

Or in hex  
c0.a8.01.cc = 192.168.1.204

So a full IP address is made up by 8x4 bits(32-bits), where they are seperated by a dot after every 8 bits meaning there are 4 groups which is also called "octets". 

Since an octet consists of 8 bits and there are 4 octets, a valid IP address can only be a number between 0 and 255, meaning it can be 256 different numbers:  
(0-255).(0-255).(0-255).(0-255)

This makes the IP pool to have 2^32 = 4,294,967,296 different IP addresses that can be assigned.

## The router
One of the primary jobs of a router is to assign IP addresses to the computers on a home network. The router has a “pool” of IP addresses that it keeps track of.   
When a computer connects to it and asks for an IP address, the router picks an IP address from the pool and assigns it to the computer. The router makes sure that two computers are not assigned the same IP address. This process of computers asking for an IP address from the router is called “dynamic” IP address assignment. It uses a network protocol called DHCP (Dynamic Host Configuration Protocol).

When a host wants to connect to another host on a completely different IP outside the network, the host calls the default getaway(the router) for help. 

The default getaway: 192.168.1.1

## IPv4 Classes
| Class | Range | Subnet | Number of networks | Usage | For |
|---|---|---|---|---|---|
| A | 1.0.0.0 - 126.255.255.255 | 255.0.0.0 | 16,777,214 | Host Assigning | Big Companies and Government |
| B | 128.0.0.0 - 191.255.20.0 | 255.255.0.0 | 65,534 | Host Assigning | Organizations |
| C | 192.0.0.0 - 223.255.255.0 | 255.255.255.0 | 254 | Host Assigning | Networks with few hosts |
| D | 224.0.0.0 - 239.255.255.255 |  |  | Special Purpose | Multicasting applications |
| E | 240.0.0.0. - 255.255.255.255 |  |  | Special Purpose | Experimental(Illegal) |

**Notes**  
- 127.0.0.0 is missing from the IP classes (16 million addresses) because they are loopback addresses on your local device. Normally used for network testing
- Class C gives us the the most networks and smaller hosts per network. 

## Subnetting
### Subnet mask
A subnet mask can look like this:  
255.255.255.0

If there is a 255, then the corresponding octet in the IP address will stay the same, but if the number is 0, then that octet can anything in between 0-255. Example:  
Subnet mask = **255.255.255**.0  
IP address = **192.168.1**.204

The first 3 octets of the IP address 192.168.1.* will stay the same where the last octet "*" in our case is 204, which in fact is valid since the number can be anything in between 0-255

So the octets that never change is called the "Network portion" where the octet on a subnet mask zero is called the "Host".



# Web Exploitation
This section will cover the basics of web exploitation. 

## Content Discovery
Content discovery is divided into four parts, being manual, automated, OSINT and subdomain enumeration.

### Manual
1. Check the robots.txt file for disallowed/hiddenpages  
2. Check if there is /admin/ page
3. Check if there is any pages ( `~` and `.bak` and `.swp`
4. Check for git repositories /.git/. [GitTools](https://github.com/internetwache/GitTools) can be used in order to automatically scrape and download a git repository hosted online with a given URL.
5. Check favicon to find the website frameworks (only works if the website developer doesn't replace this with a custom one)  
Run this to find its md5 hash:  
`curl https://static-labs.tryhackme.cloud/sites/favicon/images/favicon.ico | md5sum`  
Check [this](https://wiki.owasp.org/index.php/OWASP_favicon_database) database to find the framework.
6. Check the sitemap file for disallowed/hidden files
7. Curl HTTP Headers to find potential information about the webserver software and possibly the programming/scripting language in use. `curl http://10.10.134.48 -v` The `-v` switch enables verbose mode, which will output the headers
8. Look out for cookie values and change them if possible. Look after Base64 encoded values, JWT tokens, or maybe case folded values that can be used to bypass authentication with simply using casefold(). (Example: 'ß' -> 'ss')
9. Test for Cross-site scripting
10. Test with SQL injection methods
11. Try Flask Template Injection (SSTI) with `{{config}}` in the url. If it works, try `{{ get_user_file("/etc/passwd") }}`
12. Check `.htaccess` file for apache server configurations.
13. Grab banners/headers for framework, authentication and misconfiguration discovery `curl -IL https://www.inlanefreight.com`
14. Check the source code for any comments or hidden information in the inspector view.

When successfully finding a framework using on of the methods, Framework Stacking can be used afterwards where you check the framework documentation for potential admin portals etc.

### Automated
**What is Automated Discovery?**  
Automated discovery is the process of using tools to discover content rather than doing it manually. This process is automated as it usually contains hundreds, thousands or even millions of requests to a web server. These requests check whether a file or directory exists on a website, giving us access to resources we didn't previously know existed. This process is made possible by using a resource called wordlists.

**What are wordlists?**  
Wordlists are just text files that contain a long list of commonly used words; they can cover many different use cases. For example, a password wordlist would include the most frequently used passwords, whereas we're looking for content in our case, so we'd require a list containing the most commonly used directory and file names.

**Most common Automation tools**   
`ffuf`, `dirb` and `gobuster`.   
I personally use gobuster the most.

Example use for all three tools:
```bash
$ ffuf -w <wordlist>:FUZZ -u <IP>/FUZZ
$ dirb http://<IP>
$ gobuster dir -u http://<IP> -w <wordlist>
```

### OSINT
**Google Hacking / Dorking**   
Google hacking / Dorking utilizes Google's advanced search engine features, which allow you to pick out custom content.  
| Filter | Example | Description |
|---|---|---|
| site | site:berkankutuk.dk | returns results only from the specified website address |
| inurl | inurl:admin | returns results that have the specified word in the URL |
| filetype | filetype:pdf | returns results which are a particular file extension |
| intitle | intitle:admin | returns results that contain the specified word in the title |  

Find many more operators [here](https://ahrefs.com/blog/google-advanced-search-operators/).

**Wappalyzer**  
Wappalyzer is an online tool and browser extension that helps identify what technologies a website uses, such as frameworks, Content Management Systems (CMS), payment processors and much more, and it can even find version numbers as well. Read more [here](https://www.wappalyzer.com/).  

**Wayback Machine**  
The Wayback Machine is a historical archive of websites that dates back to the late 90s. You can search a domain name, and it will show you all the times the service scraped the web page and saved the contents. This service can help uncover old pages that may still be active on the current website. Find the website [here](https://archive.org/web/).

**Email Harvesting**  
Email harvesting is the process of gathering email addresses from a website. This can be done manually by searching for email addresses in the source code of a website, or by using a tools such as [Hunter.io](https://hunter.io/) and [Phonebook](https://phonebook.cz/). In order to verify the email addresses, you can use [EmailHippo](https://tools.emailhippo.com/). 

### Subdomain enumeration

**SSL/TLS Certificates**  
When an SSL/TLS (Secure Sockets Layer/Transport Layer Security) certificate is created for a domain by a CA (Certificate Authority), CA's take part in what's called "Certificate Transparency (CT) logs". These are publicly accessible logs of every SSL/TLS certificate created for a domain name.
The following site consists of a searchable database of certificates that shows current and historical results. [Link](crt.sh) 

**Search Engines**
The following search would only contain results from subdomain names belonging to domain.com:  
`-site:www.domain.com site:*.domain.com` 

**DNS Bruteforce**  
Bruteforce DNS (Domain Name System) enumeration is the method of trying tens, hundreds, thousands or even millions of different possible subdomains from a pre-defined list of commonly used subdomains. For this method, the tool [DNSrecon](https://www.kali.org/tools/dnsrecon/), [Sublist3r](https://github.com/aboul3la/Sublist3r) or [Turbolist3r](https://github.com/fleetcaptain/Turbolist3r) can be used. A more modern but slower alternative is [Amass](https://github.com/owasp-amass/amass).

It is usually also a good idea to probe for HTTP and HTTPS services on the discovered subdomains to filter out any false positives. This can be done with the tool [httprobe](https://github.com/tomnomnom/httprobe).

**Virtual Hosts**  
Some subdomains aren't always hosted in publically accessible DNS results, such as development versions of a web application or administration portals. Instead, the DNS record could be kept on a private DNS server or recorded on the developer's machines in their /etc/hosts file (or c:\windows\system32\drivers\etc\hosts file for Windows users) which maps domain names to IP addresses. 

Because web servers can host multiple websites from one server when a website is requested from a client, the server knows which website the client wants from the Host header. We can utilise this host header by making changes to it and monitoring the response to see if we've discovered a new website.

Bruteforce by using the following command:   
`ffuf -w /usr/share/wordlists/SecLists/Discovery/DNS/namelist.txt -H "Host: {domain}" -u http://{IP} -fs {size}`
### Cookie Manipulation
1. Check for JWT tokens at [JWT.io](https://jwt.io/)
2. Flask cookies can be unsigned by using the following tool [flask-unsign](https://pypi.org/project/flask-unsign/)
3. Flask cookies can be decoded/encoded using the following tool: [Flask Session Cookie Decoder/Encoder](https://github.com/noraj/flask-session-cookie-manager). See example usage [here](https://github.com/Berkanktk/CTFWriteups/tree/master/PicoCTF/Web%20Exploitation/MostCookies)
## SQL Injection
SQL (Structured Query Language) Injection occurs when user controlled input is passed to SQL queries without validation/sanitization. As a result, an attacker can pass in SQL queries to manipulate the outcome of such queries. 

If an attacker is able to successfully pass input that is interpreted correctly, they would be able to do the following:

* Access, Modify and Delete information in a database when this input is passed into database queries. This would mean that an attacker can steal sensitive information such as personal details and credentials.
* Execute Arbitrary system commands on a server that would allow an attacker to gain access to users’ systems. This would enable them to steal sensitive data and carry out more attacks against infrastructure linked to the server on which the command is executed.

### SQL Injection Types
**In-band SQLi (Classic SQLi)**   
In-band SQLi is the most common and easy-to-exploit of SQL injection attacks. In-band SQLi attacks rely on the fact that the same communication channel is used for both the attack and the result. There are two types of in-band SQLi attacks:
  * **Error-based SQLi** - This type of SQL injection relies on error messages thrown by the database server to obtain information about the structure of the database. This information can then be used to formulate more attacks.
  * **Union-based SQLi** - This type of SQL injection relies on using the UNION SQL operator to combine the results of two or more SELECT statements into a single result which is then returned as part of the HTTP response.

**Inferential SQLi (Blind SQLi)**   
Inferential SQLi is also known as blind SQL injection. As the name suggests, the vulnerability itself is not directly present in the application but can be inferred from the behaviour of the application. There are two types of inferential SQLi attacks being:
  * **Boolean-based SQLi** - This type of SQL injection relies on sending SQL queries to the database which evaluate to either TRUE or FALSE. Depending on the result, the content within the HTTP response will change, or remain the same.
  * **Time-based SQLi** - This type of SQL injection relies on sending SQL queries to the database which cause a time delay in the response. The time delay is used to infer if the result of the query is TRUE or FALSE.


See much more database and SQLi related information [here](/More/Databases/).

### Tool for SQL Injection
[sqlmap](https://sqlmap.org/) is a tool that automates the process of detecting and exploiting SQL injection flaws and taking over of database servers. See how to use it [here](#SQLMap).

### Examples of SQL Injection
* `' OR 1=1 --`
* `1' OR 1=1 --`
* `1' OR 1=1#`
* `1' OR 1=1--`
* `1' OR 1=1;--`
* `1" or "1"="1"-- -`
## Command Injection
Command injection is the abuse of an application's behaviour to execute commands on the operating system, using the same privileges that the application on a device is running with.

A command injection vulnerability is also known as a "Remote Code Execution" (RCE) because an attacker can trick the application into executing a series of payloads that they provide, without direct access to the machine itself (i.e. an interactive shell). The webserver will process this code and execute it under the privileges and access controls of the user who is running that application.  

### Discovering Command Injection
This vulnerability exists because applications often use functions in programming languages such as PHP, Python and NodeJS to pass data to and to make system calls on the machine’s operating system. For example, taking input from a field and searching for an entry into a file.

Example of a vulnerable code in PHP:  
```php
<?php
    $file = $_GET['file'];
    $command = "cat $file";
    system($command);
?>
```

Example of a vulnerable code in Python (Flask):  
```python
@app.route('/search')
def search():
    query = request.args.get('query')
    command = "grep -r " + query + " /var/www/html"
    output = subprocess.check_output(command, shell=True)
    return output
```

Command Injection can be detected in mostly one of two ways:
| Method | Description |
|:---:|---|
| Blind | This type of injection is where there is no direct output from the application when testing payloads. You will have to investigate the behaviours of the application to determine whether or not your payload was successful. |
| Verbose | This type of injection is where there is direct feedback from the application once you have tested a payload. For example, running the `whoami` command to see what user the application is running under. The web application will output the username on the page directly. |

#### Detecting Blind Command Injection
For this type of command injection, we will need to use payloads that will cause some time delay. For example, the `ping` and `sleep` commands are significant payloads to test with. Using `ping` as an example, the application will hang for x seconds in relation to how many pings you have specified.

Another method of detecting blind command injection is by forcing some output. This can be done by using redirection operators such as `>`. For example, we can tell the web application to execute commands such as whoami and redirect that to a file. We can then use a command such as cat to read this newly created file’s contents.

The curl command is a great way to test for command injection. This is because you are able to use curl to deliver data to and from an application in your payload. Take this code snippet below as an example, a simple curl payload to an application is possible for command injection.

`curl http://vulnerable.app/process.php%3Fsearch%3DThe%20Beatles%3B%20whoami`

#### Detecting Verbose Command Injection
Detecting command injection this way is arguably the easiest method of the two. Verbose command injection is when the application gives you feedback or output as to what is happening or being executed.

For example, the output of commands such as `ping` or `whoami` is directly displayed on the web application.

### Exploiting Command Injection
Applications that use user input to populate system commands with data can often be combined in unintended behaviour. For example, the shell operators `;`, `&` and `&&` will combine two (or more) system commands and execute them bot

Useful payloads for command injection (linux):
| Payload | Description |
|:---:|:---:|
| whoami | See what user the application is running under. |
| ls | List the contents of the current directory. You may be able to find files such as configuration files, environment files (tokens and application keys), and many more valuable things. |
| ping | This command will invoke the application to hang. This will be useful in testing an application for blind command injection. |
| sleep | This is another useful payload in testing an application for blind command injection, where the machine does not have ping installed. |
| nc | Netcat can be used to spawn a reverse shell onto the vulnerable application. You can use this foothold to navigate around the target machine for other services, files, or potential means of escalating privileges. |

Useful payloads for command injection (windows):
| Payload | Description |
|:---:|:---:|
| whoami | See what user the application is running under. |
| dir | List the contents of the current directory. You may be able to find files such as configuration files, environment files (tokens and application keys), and many more valuable things. |
| ping | This command will invoke the application to hang. This will be useful in testing an application for blind command injection. |
| timeout | This command will also invoke the application to hang. It is also useful for testing an application for blind command injection if the ping command is not installed. |

Commands that quickly can be tested:
```bash
whoami
| whoami
; whoami
' whoami
' || whoami
' & whoami
' && whoami
'; whoami
" whoami
" || whoami
" | whoami
" & whoami
" && whoami
"; whoami
$(`whoami`)
& whoami
&& whoami
```	

See [this](https://github.com/payloadbox/command-injection-payload-list) cheatsheet for more.

### Remediating Command Injection
Command injection can be prevented in a variety of ways. Everything from minimal use of potentially dangerous functions or libraries in a programming language to filtering input without relying on a user’s input.

#### Vulnerable functions
In PHP, many functions interact with the operating system to execute commands via shell; these include:

* Exec
* Passthru
* System

Snippet for a code that only accept and process numbers between 0-9 as input:
```php
<input type="text" id="ping" name="ping" pattern="[0-9]+"</input>
<?php
echo passthru("/bin/ping -c 4 "$_GET["ping"]"); 
?>
```

#### Input sanitisation
Sanitising any input from a user that an application uses is a great way to prevent command injection. This is a process of specifying the formats or types of data that a user can submit. For example, an input field that only accepts numerical data or removes any special characters such as `>`, `&` and `/`.

```php
<?php
if (!filter_input (INPUT_GET, "number", FILTER_VALIDATE_NUMBER)) {
  ...
}
...
```

Read more about the function filter_input() [here](https://www.php.net/manual/en/function.filter-input.php).

#### Bypassing filters
Applications will employ numerous techniques in filtering and sanitising data that is taken from a  user's input. These filters will restrict you to specific payloads; however, we can abuse the logic behind an application to bypass these filters. For example, an application may strip out quotation marks; we can instead use the hexadecimal value of this to achieve the same result.

When executed, although the data given will be in a different format than what is expected, it can still be interpreted and will have the same result.

```php
$payload = "\x2f|\x65 \x74 \x63\x2f\x70\x61 \x73 \x73 \x77\x64"
```
## Directory Traversal
`TO BE ADDED`
## Authentication Bypass
These vulnerabilities can be some of the most critical as it often ends in leaks of customers personal data.

### Username Enumeration
A helpful exercise to complete when trying to find authentication vulnerabilities is creating a list of valid usernames.

Website error messages are great resources for collating this information to build our list of valid usernames. 

If you try entering the username admin and fill in the other form fields with fake information, you'll see we get the error An account with this username already exists. We can use the existence of this error message to produce a list of valid usernames already signed up on the system by using the ffuf tool below. The ffuf tool uses a list of commonly used usernames to check against for any matches.

`berkankutuk@kali:~$ ffuf -w /usr/share/wordlists/SecLists/Usernames/Names/names.txt -X POST -d "username=FUZZ&email=x&password=x&cpassword=x" -H "Content-Type: application/x-www-form-urlencoded" -u <website_url> -mr "username already exists"`

In the above example, the `-w` argument selects the file's location on the computer that contains the list of usernames that we're going to check exists. 

The `-X` argument specifies the request method, this will be a GET request by default, but it is a POST request in our example. 

The `-d` argument specifies the data that we are going to send. In our example, we have the fields username, email, password and cpassword. We've set the value of the username to FUZZ. In the ffuf tool, the FUZZ keyword signifies where the contents from our wordlist will be inserted in the request. 

The `-H` argument is used for adding additional headers to the request. In this instance, we're setting the Content-Type to the webserver knows we are sending form data. 

The `-u` argument specifies the URL we are making the request to, and finally, the -mr argument is the text on the page we are looking for to validate we've found a valid username.





# Reverse Engineering
Reverse-engineering is the creative process of analyzing software and understanding it without having access to the source code. It is the process by which software is deconstructed in a way that reveals its innermost details such as its structure, function and operation.

## Assembly
Find the in-depth content for the Assembly x86-64 language [here](/More/Assembly/Readme.md) inside this repository.

`TO BE ADDED`
## Disassemblers
A disassembler is a computer program that translates machine language into assembly language—the inverse operation to that of an assembler.  

### gdb
GDB, the GNU Project debugger, allows you to see what is going on `inside' another program while it executes -- or what another program was doing at the moment it crashed.

```bash
berkankutuk@kali:~$ gdb <binary file>` # opens the binary file in gdb

(gdb)> break <function name> # sets a breakpoint at the given function
(gdb)> break *<addr> # sets a breakpoint at the given address
(gdb)> run # runs the program until it reaches the first breakpoint
(gdb)> run < <input file> # runs the program with the given input file
(gdb)> disassemble <function name> # disassembles the given function
(gdb)> x /s <addr> # prints a string from memory address
(gdb)> continue # continues the execution of the program
(gdb)> info registers # prints the values of the registers
(gdb)> info variables # prints the values of the variables
(gdb)> info functions # prints the functions
(gdb)> exploit # runs the exploit
(gdb)> x # inspect memory locations
(gdb)> quit # quits gdb
```

### radare2
Radare2 is an open-source framework that can perform disassembly, debugging, analysis, comparing data and manipulation of binary files. 

```bash
berkankutuk@kali:~$ r2 <binary file>` # opens the binary file in radare2
berkankutuk@kali:~$ r2 -d <binary file>` # opens the binary file in radare2 in debug mode 

# General
[0x00400510]> aaa # Analyze the binary
[0x00400510]> afl # List functions
[0x00400510]> s main # Go to main function
[0x00400510]> pdf # Print disassembled function
[0x00400510]> s/ password # Search for data within the code
[0x00400510]> V # Hex view

# Debug mode
[0x00400510]> dc # Launch the executable
[0x00400510]> dr # Check register state 
```

### Ghidra
Ghidra is a software reverse engineering (SRE) framework created and maintained by the National Security Agency (NSA). It is a free and open-source software reverse engineering tool released under the Apache License 2.0.

```bash
berkankutuk@kali:~$ ghidraRun <binary file>` # opens the binary file in ghidra
```

Ghidra GUI
```bash
Right click -> Patch Instruction -> Values # Patch the instruction with the given values 
File -> Export Program -> Export as ELF # Export the binary as an ELF file

Symbol Tree -> Functions # List functions (ex. Main)
```

## Call Graphs
[Cytoscape](https://github.com/cytoscape/cytoscape) is a tool for network analysis and visualization that can be used to see call graphs.

**Useful functions:**
- Layout -> Grid View = Show a grid view of the nodes.
- Pathlinker = Find paths between nodes. Needs a source and a target node. K = number of paths to find. Is mostly one in CTF situations.

## Decompilers
A decompiler is a computer program that takes an executable file as input, and attempts to create a high level code (like C/C++, Java). 

### Jar files
A jar file is a Java archive file that can contain multiple files and folders. Jar files are mainly used for archiving, compression and decompression. Jar files are similar to zip files, but jar files can have additional attributes that are required for a Java application to run.

To decompile a jar file, [procyon](https://manpages.ubuntu.com/manpages/jammy/man1/procyon.1.html) can be used.

```bash
berkankutuk@kali:~$ sudo apt-get install -y procyon-decompiler
berkankutuk@kali:~$ procyon -jar <jar file> -o <output directory>
```

# Cryptography
## Generate keys
To generate a private key we use the following command (8912 creates the key 8912 bits long):  
`openssl genrsa -aes256 -out private.key 8912`

To generate a public key we use our previously generated private key:  
`openssl rsa -in private.key -pubout -out public.key`

Lets now encrypt a file (plaintext.txt) using our public key:  
`openssl rsautl -encrypt -pubin -inkey public.key -in plaintext.txt -out encrypted.txt`

Now, if we use our private key, we can decrypt the file and get the original message:  
`openssl rsautl -decrypt -inkey private.key -in encrypted.txt -out plaintext.txt`

## Cryptographic Methods
### Cryptii
[Cryptii](https://cryptii.com) has multiple decoding tools like base64, Ceaser Cipher, ROT13, Vigenère Cipher and more.

### Keyboard Shift
[Dcode](https://www.dcode.fr/keyboard-shift-cipher) If you see any thing that has the shape of a sentence but it looks like nonsense letters, and notes some shift left or right, it may be a keyboard shift...

### Bit Shift
Sometimes the letters may be shifted by a stated hint, like a binary bit shift ( x >> 1 ) or ( x << 1 ).

### Reversed Text
Sometimes a "ciphertext" is just as easy as reversed text. Don't forgot to check under this rock! You can reverse a string in Python like so:

"UOYMORFEDIHOTGNIYRTEBTHGIMFTCA.TAHTTERCESASISIHT"[::-1]

### XOR
ANY text could be XOR'd. Techniques for this are Trey's code, and XORing the data against the known flag format. Typically it is given in just hex, but once it is decoded into raw binary data, it gives it keeps it's hex form (as in \xde\xad\xbe\xef etc..) Note that you can do easy XOR locally with Python like so (you need pwntools installed):

`python >>> import pwn; pwn.xor("KEY", "RAW_BINARY_CIPHER")`

### Vigenère Cipher
The Vigenère cipher is a method of encrypting alphabetic text by using a series of interwoven Caesar ciphers, based on the letters of a keyword. It employs a form of polyalphabetic substitution.

The encryption of the original text is done using the Vigenère square or Vigenère table. It is a table of alphabets written out 26 times in different rows, each alphabet shifted cyclically to the left compared to the previous alphabet, corresponding to the 26 possible Caesar ciphers. At different points in the encryption process, the cipher uses a different alphabet from one of the rows. The alphabet used at each point depends on a repeating keyword.

### Caesar Cipher
The Caesar cipher is one of the earliest known and simplest ciphers. It is a type of substitution cipher in which each letter in the plaintext is replaced by a letter some fixed number of positions down the alphabet. For example, with a left shift of 3, D would be replaced by A, E would become B, and so on. The method is named after Julius Caesar, who used it in his private correspondence.

### ROT13
ROT13 is a simple letter substitution cipher that replaces a letter with the letter 13 letters after it in the alphabet. ROT13 is an example of the Caesar cipher which was developed in ancient Rome.

### Substitution Cipher
A substitution cipher is a method of encoding by which units of plaintext are replaced with ciphertext, according to a fixed system; the "units" may be single letters (the most common), pairs of letters, triplets of letters, mixtures of the above, and so forth. The receiver deciphers the text by performing the inverse substitution.

Useful tools for substitution ciphers are [Cryptii](https://cryptii.com) and [Dcode](https://www.dcode.fr/substitution-cipher).
## Encoding
Encoded data can be decoded immediately, without keys. It's NOT a form of encryption, it just a way of representing data.

**A very popular encoding is Base64.**  
The basic idea behind Base64 encoding is to represent binary data using only ASCII characters. To do this, Base64 converts each 3 bytes of binary data into 4 bytes of ASCII text. The 3 bytes of binary data are divided into 4 groups of 6 bits each, which are then represented by a character from a set of 64 characters. The 64 characters used in Base64 are:

`ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/`

The equals sign (=) is also used as a padding character to ensure that the length of the output is a multiple of 4 characters.

For example, let's say we want to encode the binary data "`011000010110001001100011`", which represents the ASCII characters "`abc`". To encode this data in Base64, we first divide it into 3-byte groups:

`01100001 01100010 01100011`

Then we divide each 3-byte group into 4 groups of 6 bits each:

`011000 010110 001001 100011`

Next, we convert each group of 6 bits to its corresponding Base64 character:

`Y W J j`

So the encoded Base64 string for "`abc`" is "`YWJj`".

### Encoding a string in the terminal
```bash
echo -n "Hello World" | base64
```

### Decoding a string in the terminal
```bash
echo -n "SGVsbG8gV29ybGQ=" | base64 -d
```

### Encoding/Decoding files
```bash
base64 /path/to/file > output.txt # Encoding
base64 -d /path/to/file > output.txt # Decoding
```
## Hashing
Hashing is used for 2 main purposes in Cyber Security. To verify integrity of data, or for verifying passwords. 

plaintext ➡️ hash  
hash ⛔ plaintext

Doing a lookup in a sorted list of hashes that are not salted is quite fast, much much faster than trying to crack the hash. But in case we have to crack, then its done by hashing a large number of different inputs (often rockyou.txt, these are the possible passwords), potentially adding the salt if there is one and comparing it to the target hash. 

Tools like Hashcat and John the Ripper are normally used for this.
## Ciphers
`TO BE ADDED`
## Encryption (RSA)
### Symetric encryption
plaintext ➡️ 🔑 ➡️ ciphertext  
plaintext ⬅️ 🔑 ⬅️ ciphertext  
(🔑 shared key)

### Asymetric encryption
plaintext ➡️ 🔑 ➡️ ciphertext  
plaintext ⬅️ 🗝 ⬅️ ciphertext  
(🔑 public key, 🗝 private key

Public key to encrypt, private key to decrypt.

### Cracking ecrypted files
If you are using Kali linux or Parrot OS, you should have a binary add on called `gpg2john`. This binary program allows us to convert the gpg file into a hash string that john the ripper can understand when it comes to brute-forcing the password against a wordlist. 

How to use it (GPG example):
```bash
gpg2john encrypted_file.txt.gpg > hash.txt
```
Then you can use john the ripper to crack the password.

```bash
john --wordlist=/usr/shared/wordlists/rockyou.txt --format=gpg hash.txt
```

The result should reveal the password if you have used a strong wordlist that contains it.

Cheat Sheets
------------

**Nmap and Nessus** (Source: https://cdn.comparitech.com/wp-content/uploads/2019/06/Nmap-Nessus-Cheat-Sheet.jpg)
![Nmap & Nessus](https://cdn.comparitech.com/wp-content/uploads/2019/06/Nmap-Nessus-Cheat-Sheet.jpg)

**Wireshark** (Source: https://cdn.comparitech.com/wp-content/uploads/2019/06/Wireshark-Cheat-Sheet-1.jpg)
![Wireshark](https://cdn.comparitech.com/wp-content/uploads/2019/06/Wireshark-Cheat-Sheet-1.jpg)

**Hacking Tools** (Source https://blog.compass-security.com/wp-content/uploads/2019/10/hacking_tools_cheat_sheet_v1.0-0.png)
![Hacking Tools](https://blog.compass-security.com/wp-content/uploads/2019/10/hacking_tools_cheat_sheet_v1.0-0.png)

**Hacking Tools P.2** (Source https://blog.compass-security.com/wp-content/uploads/2019/10/hacking_tools_cheat_sheet_v1.0-1.png)
![Hacking Tools p.2](https://blog.compass-security.com/wp-content/uploads/2019/10/hacking_tools_cheat_sheet_v1.0-1.png)

Resources: https://github.com/Berkanktk/CyberSecurity
