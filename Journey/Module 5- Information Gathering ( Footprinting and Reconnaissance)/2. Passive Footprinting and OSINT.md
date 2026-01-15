## Passive Footprinting

Passive Footprinting is the process of **gathering information about a target without directly interacting with its systems**. It relies entirely on **publicly available data sources**, making it stealthy and legally safer when performed within scope.

Passive footprinting is primarily performed using **search engines, online tools, social platforms, public records, and OSINT sources**.

---

## Footprinting through Search Engines

Footprinting through search engines involves using **advanced search techniques** to extract sensitive or valuable information about a target organization.

### Why Attackers Use Search Engines

Attackers use search engines to gather information such as:
- Technology platforms in use
- Employee details
- Login pages and admin portals
- Intranet URLs
- Cloud storage links
- Backup and configuration files

Search engine caches and internet archives may also contain **data that has been removed from the World Wide Web (WWW)** but is still accessible.

---

## Finding Company’s Public and Restricted Websites

Search engines can reveal both **public-facing** and **restricted** web resources.

### Techniques Used

- Search for the company’s **external URL** using search engines like Google or Bing
- Identify **restricted or hidden URLs** that may reveal:
  - Internal portals
  - Department-specific pages
  - Business unit information

### Google Hacking (Google Dorking)

Google Hacking is a technique that uses **advanced search operators** to build complex queries called **Google Dorks**.

These queries help uncover:
- Admin panels
- Login pages
- Backup files
- Sensitive documents

### Additional Tool
- **Netcraft** – Used to identify restricted URLs and web infrastructure details

---

## Determining the Operating System

Operating system details can often be inferred using search engines and public tools.

### Tools Used

- **Netcraft** – Determines OS and web server technologies
- **Shodan** – Search engine for internet-connected devices such as:
  - Servers
  - Routers
  - IoT devices

Shodan allows filtering based on OS, ports, services, and software versions.

---

## Collecting Location Information

Physical and geographical location of a target can be gathered using mapping services.

### Tools for Geolocation

- Google Earth
- Google Maps
- Wikimapia
- National Geographic Maps
- Yahoo Maps
- Bing Maps

This information may reveal:
- Office locations
- Data centers
- Branch offices

---

## Social Networking Sites & People Search Services

Social platforms and people search services provide a significant amount of intelligence.

### Information Collected

- Residential and email addresses
- Contact numbers and date of birth
- Photos and social media profiles
- Blog URLs
- Satellite images of private residences
- Information about upcoming projects
- Operating environment details

---

## Footprinting through Job Sites

Job postings often reveal **internal infrastructure details**.

### What to Look For

- Job requirements
- Employee profiles
- Hardware platforms
- Software and technologies used
- Cloud services and tools

Job sites indirectly disclose **technology stacks and system architecture**.

---

## Monitoring the Target Using Alerts

Alerts are **automated content monitoring services** that notify changes related to a target.

### Examples of Alert Services

- Google Alerts – http://www.google.com/alerts
- Yahoo Alerts – http://alerts.yahoo.com
- Twitter Alerts – https://twitter.com/alerts
- Giga Alert – http://www.gigaalert.com

Alerts help track:
- New mentions
- Data leaks
- Press releases
- Technical disclosures

---

## Information Gathering Using Groups, Forums, and Blogs

Groups, forums, and blogs often contain **unintentionally leaked sensitive information**.

### Information Found

- Public network information
- System configuration details
- Personal and organizational information

Attackers may:
- Join employee discussion groups
- Monitor technical forums
- Read blogs authored by employees

⚠️ **Note:** Creating fake profiles is unethical and illegal outside authorized testing environments.

---

## OSINT (Open Source Intelligence)

OSINT is the practice of collecting intelligence from **publicly available sources**.

### Common OSINT Sources

- Social media platforms (Twitter, Facebook, LinkedIn)
- News articles and newsletters
- Public-facing web servers
- Code repositories (GitHub, GitLab, CodeChef)

---

## Objectives of OSINT

OSINT aims to identify:

- IP addresses, subdomains, ports, and services
- Technologies and application platforms
- Infrastructure details
- Sensitive information such as:
  - API keys
  - AWS S3 buckets
  - Leaked credentials
- Log files and backup files
- Database files
- Client-side code
- JavaScript libraries
- Configuration files

---

## Real-World Use Cases

- Reconnaissance before penetration testing
- Social engineering preparation
- Asset discovery
- Brand and data leak monitoring

---

## Legal & Ethical Considerations

- Passive footprinting is generally legal
- Data misuse violates privacy laws
- Always follow defined scope and authorization
- Respect terms of service of platforms

---

## Best Practices for Passive Footprinting

- Use multiple data sources
- Validate information from different platforms
- Avoid interacting with target systems
- Document all findings
- Correlate OSINT data with DNS, Website, and Network footprinting

---
