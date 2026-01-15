## Network Footprinting

Network Footprinting is the process of **gathering information about a target organization’s network infrastructure**. It helps identify IP address ranges, hosts, exposed services, and system details, allowing an attacker or security professional to **map the network before active scanning begins**.

Network footprinting focuses on **high-level network intelligence** and is a critical step in the reconnaissance phase.

---

## Locating the Network Range

Identifying the network range is one of the primary objectives of network footprinting.

### Why Network Range Information is Important

- Helps create a **map of the target network**
- Identifies **valid IP address blocks**
- Prevents unnecessary scanning outside the target scope
- Assists in detecting **related networks and subsidiaries**

---

## Identifying IP Address Ranges

IP address ranges can be identified using **WHOIS databases** managed by **Regional Internet Registries (RIRs)**.

### Techniques Used

- **ARIN WHOIS database search**
- WHOIS lookup via other RIRs (APNIC, RIPE, LACNIC, AFRINIC)

### Information Discovered

- Range of IP addresses assigned to the organization
- Subnet mask used
- Organization name and contacts
- Associated autonomous systems (ASNs)

---

## Network Footprinting Information Collected

Network footprinting may reveal the following details:

- **Network address ranges**
- **Hostnames and domain associations**
- **Exposed hosts accessible from the internet**
- **Applications running on exposed hosts**
- **Operating system details and application versions**
- **Patch status of hosts and services**
- **Application architecture and backend server structure**
- **Implementation or configuration details shared publicly**
  - Newsgroups
  - Technical forums
  - Interviews
  - Documentation

---

## Network Footprinting Techniques

### Passive Network Footprinting

- WHOIS lookups
- DNS analysis
- Public network databases
- Search engines and technical forums
- Job postings and documentation

Passive methods do not interact directly with the target network.

---

### Active Network Footprinting

- Network discovery probes
- Banner grabbing
- Limited port checks (authorized only)

⚠️ **Note:** Active techniques require **explicit permission**.

---

## Common Network Footprinting Tools

- **whois**
- **ARIN Database Search**
- **BGPView**
- **Shodan**
- **Censys**
- **Netcraft**
- **Traceroute (authorized use)**
- **Maltego**

---

## Understanding Exposed Hosts

Exposed hosts are systems that:
- Have public IP addresses
- Provide internet-facing services
- Can be directly accessed by external users

Examples:
- Web servers
- Mail servers
- VPN gateways
- API endpoints

---

## Real-World Use Cases

- Defining scanning scope
- Identifying internet-facing assets
- Preparing for vulnerability scanning
- Supporting targeted network attacks
- Infrastructure security assessment

---

## Defensive Perspective (Blue Team)

To reduce network footprinting exposure:
- Minimize public IP exposure
- Use network segmentation
- Apply proper firewall rules
- Keep systems fully patched
- Avoid publishing sensitive infrastructure details

---

## Legal & Ethical Considerations

- Passive network footprinting is generally legal
- Active probing without authorization may be illegal
- Always respect defined testing boundaries

---

## Best Practices for Network Footprinting

- Start with WHOIS and RIR data
- Identify IP ranges and ASNs
- Map exposed hosts carefully
- Correlate findings with DNS and website footprinting
- Maintain detailed documentation

---
