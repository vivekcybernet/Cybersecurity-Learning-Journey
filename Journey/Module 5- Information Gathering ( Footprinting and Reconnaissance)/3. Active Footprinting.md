## Active Reconnaissance

Active Reconnaissance is the process of **directly interacting with a target system, network, or application** to gather information. Unlike passive reconnaissance, active techniques **send traffic to the target**, making them detectable and potentially risky if performed without authorization.

Active reconnaissance is typically performed **after passive footprinting** and before scanning and enumeration.

---

## Purpose of Active Reconnaissance

The main objectives of active reconnaissance are to:

- Validate information collected during passive footprinting
- Identify **live hosts** and reachable systems
- Discover **open ports and running services**
- Determine **operating systems and application versions**
- Identify **potential vulnerabilities**
- Map the **network and service architecture**

---

## Key Characteristics of Active Reconnaissance

- Involves **direct interaction** with the target
- Generates **network traffic**
- May trigger **logs, alerts, or IDS/IPS**
- Requires **explicit permission**
- More accurate than passive techniques

---

## Information Gathered During Active Reconnaissance

Active reconnaissance may reveal:

- Live IP addresses and hosts
- Open ports and services
- Service banners and versions
- Operating system details
- Network topology
- Application behavior and responses
- Firewall and filtering rules

---

## Common Active Reconnaissance Techniques

### Host Discovery

Used to determine whether a system is **alive and reachable**.

- ICMP echo requests
- ARP discovery (local network)
- TCP/UDP probes

---

### Port Scanning

Used to identify **open, closed, or filtered ports**.

- TCP connect scans
- SYN (half-open) scans
- UDP scans

Open ports indicate **available services**.

---

### Service Enumeration

Focuses on identifying **services and versions** running on open ports.

- Banner grabbing
- Service fingerprinting
- Application response analysis

---

### Operating System Detection

Determines the target’s operating system by analyzing:

- TCP/IP stack behavior
- Response patterns
- TTL values
- Window sizes

---

### Network Mapping

Used to understand **network layout and paths**.

- Traceroute
- Route analysis
- Gateway identification

---

## Active Reconnaissance Tools

Common tools used for active reconnaissance include:

- **Nmap** – Host discovery, port scanning, service detection
- **Netcat** – Banner grabbing and manual service interaction
- **Traceroute / Tracert** – Path discovery
- **Hping** – Custom packet crafting and probing
- **Masscan** – High-speed port scanning
- **Zmap** – Internet-scale scanning (authorized use only)
- **Telnet / FTP / SSH clients** – Manual service testing

---

## Active Web Reconnaissance

Active reconnaissance also applies to web applications.

### Techniques

- Sending crafted HTTP requests
- Parameter manipulation
- Form interaction
- Directory and file probing

### Tools

- Burp Suite
- OWASP ZAP
- Nikto
- Dirb / Gobuster

---

## Risks of Active Reconnaissance

- Detection by security monitoring systems
- Blocking of source IP address
- Legal consequences if unauthorized
- Service disruption if misconfigured

---

## Legal & Ethical Considerations

- Active reconnaissance **must be authorized**
- Always follow defined scope and rules of engagement
- Unauthorized scanning is illegal in many jurisdictions
- Ethical hacking requires written permission

---

## Active vs Passive Reconnaissance

| Aspect | Passive Reconnaissance | Active Reconnaissance |
|-----|----------------------|---------------------|
| Interaction | No direct interaction | Direct interaction |
| Stealth | High | Low |
| Accuracy | Moderate | High |
| Risk | Low | High |
| Authorization | Often not required | Always required |

---

## Best Practices for Active Reconnaissance

- Always perform passive reconnaissance first
- Clearly define scope and permission
- Start with low-impact techniques
- Monitor tool output carefully
- Document every action and finding
- Avoid unnecessary traffic

---

## Real-World Use Cases

- Penetration testing
- Vulnerability assessments
- Red team operations
- Network security audits

---
