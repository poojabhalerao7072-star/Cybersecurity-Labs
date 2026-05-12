# Nmap Command Reference

---

# Common Nmap Flags and Options

| Flag | Description |
|------|-------------|
| `-p` | Scans specific ports |
| `-p-` | Scans all 65535 ports |
| `-sV` | Detects service versions |
| `-O` | Detects operating system |
| `-A` | Enables aggressive scan |
| `-F` | Fast scan using fewer ports |
| `-sn` | Ping scan without port scanning |
| `-Pn` | Skips host discovery |
| `-v` | Enables verbose output |
| `-vv` | Enables very verbose output |
| `-T4` | Faster scan timing |
| `--script` | Runs NSE scripts |
| `-oN` | Saves output in normal format |
| `-oX` | Saves output in XML format |
| `-sS` | TCP SYN stealth scan |
| `-sU` | UDP scan |
| `-sT` | TCP connect scan |
| `-A` | OS detection + version detection + scripts + traceroute |

---

## Basic Scan

```bash
nmap scanme.nmap.org
```

Performs a basic TCP scan on the target.

---

## Service Version Detection

```bash
nmap -sV scanme.nmap.org
```

Detects services and versions running on open ports.

---

## Operating System Detection

```bash
sudo nmap -O scanme.nmap.org
```

Attempts to detect the target operating system.

---

## Aggressive Scan

```bash
sudo nmap -A scanme.nmap.org
```

Performs OS detection, version detection, script scanning, and traceroute.

---

## Scan Specific Ports

```bash
nmap -p 80,443 scanme.nmap.org
```

Scans only ports 80 and 443.

---

## Scan All Ports

```bash
nmap -p- scanme.nmap.org
```

Scans all 65535 ports.

---

## Fast Scan

```bash
nmap -F scanme.nmap.org
```

Scans fewer ports for faster results.

---

## Ping Scan

```bash
nmap -sn scanme.nmap.org
```

Checks whether the host is online.

---

# LEARNINGS:

## 1. What is Nmap?

Nmap is an open-source network scanning and enumeration tool used for security auditing and penetration testing.

---

## 2. What is port scanning?

Port scanning is the process of identifying open ports and services running on a target system.

---

## 3. What is the difference between -sV and -O?

`-sV` detects service versions.  
`-O` attempts to detect the operating system.

---

## 4. What is aggressive scan in Nmap?

`-A` enables OS detection, version detection, script scanning, and traceroute.

---

## 5. Why is Nmap important in cybersecurity?

Nmap helps identify open ports, running services, vulnerabilities, and network exposure during reconnaissance.
