# CompTIA Tech+ (FC0-U71) — Exam Preparation Guide

> **Goal:** Pass the FC0-U71 exam with confidence.
> **Approach:** Systematic domain mastery + active recall + scenario-based practice.
> **Overview:** [CompTIA_Tech+.md](CompTIA_Tech+.md)

---

## 📌 Table of Contents

1. [Exam Snapshot](#1-exam-snapshot)
2. [Study Timeline & Schedule](#2-study-timeline--schedule)
3. [Domain 1 — IT Concepts & Terminology (26%)](#3-domain-1--it-concepts--terminology-26)
4. [Domain 2 — Infrastructure (18%)](#4-domain-2--infrastructure-18)
5. [Domain 3 — Applications & Software (14%)](#5-domain-3--applications--software-14)
6. [Domain 4 — Software Development Concepts (10%)](#6-domain-4--software-development-concepts-10)
7. [Domain 5 — Database Fundamentals (13%)](#7-domain-5--database-fundamentals-13)
8. [Domain 6 — Security (19%)](#8-domain-6--security-19)
9. [Key Terms Master Glossary](#9-key-terms-master-glossary)
10. [Mnemonics & Memory Aids](#10-mnemonics--memory-aids)
11. [Practice Question Strategies](#11-practice-question-strategies)
12. [Exam Day Checklist](#12-exam-day-checklist)
13. [Resources & Tools](#13-resources--tools)
14. [Progress Tracker](#14-progress-tracker)

---

## 1. Exam Snapshot

| Property | Value |
|----------|-------|
| Exam Code | FC0-U71 |
| Questions | Max 70–75 (multiple-choice) |
| Time | 60 minutes |
| Passing Score | **650 / 900** |
| Cost | ~$130–$150 USD |
| Expires | **Never** (Cert for Life) |
| Proctored By | Pearson VUE (in-person or online) |

### Domain Weight Summary

```
Domain 1: IT Concepts & Terminology   ██████████ 26%  (~19 questions)
Domain 6: Security                    ███████    19%  (~14 questions)
Domain 2: Infrastructure              ███████    18%  (~13 questions)
Domain 3: Applications & Software     █████      14%  (~10 questions)
Domain 5: Database Fundamentals       █████      13%  (~10 questions)
Domain 4: Software Development        ████       10%  (~7 questions)
```

> **Strategy:** Domains 1 and 6 together make up 45% of the exam. Master these first.

---

## 2. Study Timeline & Schedule

### Option A — 4-Week Intensive Plan (Full-time Student)

| Week | Focus | Daily Commitment |
|------|-------|-----------------|
| Week 1 | Domain 1 (IT Concepts) + Domain 2 (Infrastructure) | 1.5 hrs/day |
| Week 2 | Domain 3 (Apps/Software) + Domain 4 (Dev Concepts) + Domain 5 (Databases) | 1.5 hrs/day |
| Week 3 | Domain 6 (Security) + Full review of all domains | 1.5 hrs/day |
| Week 4 | Practice tests + weak-area review + final prep | 1.5 hrs/day |

### Option B — 6-Week Relaxed Plan (Busy Schedule)

| Week | Focus | Daily Commitment |
|------|-------|-----------------|
| Week 1 | Domain 1 — IT Concepts & Terminology | 45 min/day |
| Week 2 | Domain 2 — Infrastructure | 45 min/day |
| Week 3 | Domain 3 — Applications & Software | 45 min/day |
| Week 4 | Domain 4 + Domain 5 | 45 min/day |
| Week 5 | Domain 6 — Security | 45 min/day |
| Week 6 | Full review + 3 practice tests | 1 hr/day |

### Daily Study Template

```
[ ] Review yesterday's notes (10 min)
[ ] Study new content — read/watch (30–40 min)
[ ] Make flashcards for new terms (10 min)
[ ] Do 10–15 practice questions (15 min)
[ ] Review wrong answers and understand WHY (10 min)
[ ] Write a 3-sentence summary of today's topic (5 min)
```

---

## 3. Domain 1 — IT Concepts & Terminology (26%)

> Highest-weighted domain on the exam. It forms the foundational vocabulary and principles for all computing. Master this and every subsequent domain becomes significantly clearer.

### 3.1 Notational Systems

Computers operate natively on binary states (on/off, high/low voltage). You must recognize four distinct numbering systems:

| System | Base | Digits / Symbols Used | Primary Use in IT |
|--------|------|-----------------------|-------------------|
| **Binary** | Base 2 | `0, 1` | Fundamental machine code, CPU logic gates, data transmission |
| **Octal** | Base 8 | `0–7` | Linux/Unix file permissions (e.g., `chmod 755`), legacy computing |
| **Decimal** | Base 10 | `0–9` | Human everyday counting, standard user interfaces |
| **Hexadecimal** | Base 16 | `0–9, A–F` (A=10, B=11, C=12, D=13, E=14, F=15) | Memory addresses, MAC addresses (`00:1A:2B`), HTML/CSS color codes (`#FFFFFF`), IPv6 addresses |

**Key Mathematical Relationships & Concepts:**
- **Bit:** 1 binary digit (`0` or `1`).
- **Nibble:** 4 bits = 1 Hexadecimal digit (e.g., `1010` in binary = `A` in hex = `10` in decimal).
- **Byte:** 8 bits = 2 Hexadecimal digits (e.g., `11111111` in binary = `FF` in hex = `255` in decimal).
- **Binary Place Values (Powers of 2):** `128, 64, 32, 16, 8, 4, 2, 1`
  - Example: `00001010` = 8 + 2 = **10** (Decimal) = **A** (Hex).
  - Example: `11111111` = 128 + 64 + 32 + 16 + 8 + 4 + 2 + 1 = **255** (Decimal) = **FF** (Hex).

---

### 3.2 Data Representation & Character Encoding

How human readable characters and symbols are encoded into binary bytes:

| Standard | Character Width | Number of Characters | Description |
|----------|-----------------|----------------------|-------------|
| **ASCII** | 7-bit (or 8-bit Extended) | 128 (256 in extended) | American Standard Code for Information Interchange. Encodes English alphabet (A-Z, a-z), numbers (0-9), punctuation, and control characters (like Enter, Backspace). |
| **Unicode** | Variable (8 to 32 bits, e.g., UTF-8, UTF-16) | Over 149,000+ characters | Modern global standard. Supports virtually all spoken languages, ancient scripts, mathematical symbols, and modern emojis (😀). |
| **UTF-8** | 1 to 4 bytes per character | Variable width | The dominant encoding on the World Wide Web. Backward-compatible with standard ASCII. |

> **Exam Tip:** ASCII is limited to basic English and standard symbols. If a question mentions international characters, multilingual support, or emojis, the answer is **Unicode / UTF-8**.

---

### 3.3 The IPOS Computing Cycle

Every computer system follows the **IPOS** operational cycle:

```
[ INPUT ] ──▶ [ PROCESSING ] ──▶ [ OUTPUT ]
                     │   ▲
                     ▼   │
                 [ STORAGE ]
```

1. **Input:** Entering raw data or commands into the system.
   - *Devices:* Keyboard, mouse, touchscreen, barcode scanner, microphone, webcam, biometrics, sensors.
2. **Processing:** Manipulating, calculating, and executing instructions on the raw input data.
   - *Components:* CPU (Central Processing Unit), GPU (Graphics Processing Unit), ALU (Arithmetic Logic Unit), registers.
3. **Output:** Presenting processed results in a human-understandable or machine-actionable format.
   - *Devices:* Monitors/displays, printers, speakers, headphones, haptic feedback actuators, projectors.
4. **Storage:** Retaining data, applications, and operating systems permanently or temporarily.
   - *Temporary / Volatile:* RAM, CPU Cache.
   - *Permanent / Non-Volatile:* SSD, HDD, NVMe drives, Flash memory (USB drives), Optical media (CD/DVD/Blu-ray), Tape drives, Cloud storage.
5. **Hybrid / I/O Devices (Both Input and Output):** Touchscreen monitors, multi-function printers (scanner + printer), VR headsets with motion tracking.

---

### 3.4 Data vs. Information vs. Knowledge (The DIKW Framework)

Understanding how raw signals transform into actionable insight:

| Level | Definition | Real-World Example |
|-------|------------|--------------------|
| **Data** | Raw, unorganized, and uncontextualized facts, numbers, or symbols. Has no intrinsic meaning on its own. | `103.8` |
| **Information** | Data that has been processed, structured, labeled, or contextualized to give it meaning. | `Patient Body Temperature: 103.8°F (Elevated High Fever)` |
| **Knowledge** | Information that is understood, combined with experience, and applied to make decisions or solve problems. | `A sustained temperature of 103.8°F in an adult indicates a severe infection requiring clinical evaluation and cooling therapy.` |
| **Wisdom** | Applying knowledge, ethics, and long-term perspective to make sound judgments. | `Implementing preventative hygiene protocols and sanitation to prevent future outbreaks across the ward.` |

> **Exam Tip:** If a question asks about "raw, unprocessed numbers or characters without context", choose **Data**. If it asks about "processed data that provides meaning or context", choose **Information**.

---

### 3.5 Units of Measure & Performance Metrics

#### Storage Capacity Units (Bytes)
Storage is measured in **Bytes** (capital **B**). 1 Byte = 8 bits.

| Unit | Symbol | Base 10 (Decimal) | Base 2 (Binary / IEC) | Practical Reference |
|------|--------|-------------------|-----------------------|---------------------|
| **Bit** | b | 1 or 0 | 1 or 0 | Single binary state |
| **Byte** | B | 8 bits | 8 bits | Single ASCII text character |
| **Kilobyte** | KB | 1,000 Bytes | 1,024 Bytes ($2^{10}$) | Small text document / email |
| **Megabyte** | MB | 1,000,000 Bytes | 1,024 KB ($2^{20}$) | High-res photo / 3-minute MP3 audio file |
| **Gigabyte** | GB | 1,000,000,000 Bytes | 1,024 MB ($2^{30}$) | Full HD movie / smartphone RAM |
| **Terabyte** | TB | 1 Trillion Bytes | 1,024 GB ($2^{40}$) | Modern laptop / desktop internal SSD/HDD |
| **Petabyte** | PB | 1 Quadrillion Bytes | 1,024 TB ($2^{50}$) | Enterprise data center / cloud storage pool |

#### Data Transfer Rate / Throughput (Bits per second)
Network transmission and bus bandwidth are measured in **bits per second** (lowercase **b**).

- **bps:** Bits per second
- **Kbps:** Kilobits per second ($10^3$ bps)
- **Mbps:** Megabits per second ($10^6$ bps) — typical home broadband speeds (e.g., 300 Mbps)
- **Gbps:** Gigabits per second ($10^9$ bps) — high-speed fiber internet and enterprise backbones (e.g., 1 Gbps, 10 Gbps)
- **Tbps:** Terabits per second ($10^{12}$ bps) — global internet trunk lines

> **Conversion Formula (Bits to Bytes):**
> $$\text{Transfer Speed in MB/s} = \frac{\text{Connection Speed in Mbps}}{8}$$
> *Example:* A **100 Mbps** connection downloads at a theoretical maximum speed of **12.5 MB/s** ($100 \div 8$).

#### Processing Speed & Frequency
- **Hertz (Hz):** One CPU clock cycle per second.
- **Megahertz (MHz):** Millions of cycles per second (older CPUs, RAM frequencies).
- **Gigahertz (GHz):** Billions of cycles per second (modern CPUs, typically 2.5 GHz – 5.5 GHz).
- **Cores:** Multiple physical processing engines on a single CPU chip (Dual-core, Quad-core, Octa-core) allowing parallel task execution.

---

### 3.6 Intellectual Property, Software Licensing & Digital Ethics

#### Intellectual Property (IP) Protections

| Protection Type | What It Protects | Duration / Details | Example |
|-----------------|------------------|--------------------|---------|
| **Copyright** | Original authorial and creative works (source code, books, music, videos, software). | Life of author + 70 years (automatic upon creation). | The source code of a software application or a video game script. |
| **Patent** | Inventions, unique physical devices, and novel technical processes. | Typically 20 years from filing (must be registered). | A new hardware sensor design or a patented cryptographic chip architecture. |
| **Trademark** | Identifiable brand names, logos, slogans, product names, and distinct marks. | Renewable indefinitely as long as in commercial use (`™`, `®`). | The Apple logo, the name "CompTIA Tech+", "Windows". |
| **Trade Secret** | Confidential, closely guarded business information giving a competitive edge. | Protected indefinitely as long as kept secret; enforced via NDAs. | Google's search ranking algorithm, proprietary trading algorithms. |

#### Software Licensing Models

| License Model | Source Code Access | Terms & Cost | Examples |
|---------------|--------------------|--------------|----------|
| **Proprietary / Commercial** | Closed (source code private) | Must purchase a license or subscription; cannot inspect or modify source code. | Microsoft Windows, Adobe Creative Cloud, AutoCAD |
| **EULA** (End User License Agreement) | Closed | Legal agreement between software publisher and user specifying permitted uses and restrictions. | Standard terms agreed to during software installation |
| **Open Source (FOSS)** | Open (publicly accessible) | Free to inspect, modify, and redistribute under licenses like GPL, MIT, Apache. | Linux (Ubuntu), Apache HTTP Server, Python, LibreOffice |
| **Freeware** | Closed | Free to use at no financial cost, but source code remains closed/proprietary. | Adobe Acrobat Reader, Skype, 7-Zip |
| **Shareware / Trialware** | Closed | Free trial period or feature-limited; payment required to unlock full version. | WinRAR, trial versions of antivirus software |

#### Enterprise Software Licensing Types:
- **Per-Seat / Named User License:** Assigned to one specific individual user or machine.
- **Concurrent License:** Allows a fixed maximum number of simultaneous users to access the software at the same time across a network.
- **Site License:** Permits unlimited installations and usage within a specific physical location, building, or organization.
- **Subscription / SaaS:** Ongoing recurring fee (monthly/annual) granting access to software and updates.

#### Digital Ethics & Security Policies
- **PII (Personally Identifiable Information):** Any data that can identify an individual (Social Security Number, Full Name, Date of Birth, Biometric data). Must be protected by law (GDPR, HIPAA, CCPA).
- **AUP (Acceptable Use Policy):** Organizational policy outlining what employees/students can and cannot do on company computers, networks, and internet connections.
- **Environmental & Hardware Safety:**
  - **ESD (Electrostatic Discharge):** Prevent damage to sensitive computer chips by wearing an ESD wrist strap and working on anti-static mats.
  - **Surge Protectors:** Defends hardware from voltage spikes.
  - **UPS (Uninterruptible Power Supply):** Battery backup providing temporary power during blackouts to allow clean system shutdown.

---

### 3.7 Troubleshooting Methodology Deep-Dive (CompTIA 6-Step)

The official CompTIA 6-step troubleshooting model is heavily tested through practical scenario questions:

```
┌─────────────────────────────────────────────────────────────┐
│ 1. IDENTIFY THE PROBLEM                                     │
│    • Gather information from the user                       │
│    • Ask OPEN-ENDED questions first (explore symptoms)      │
│    • Ask CLOSED-ENDED questions later (confirm facts)       │
│    • Inquire about recent changes (updates, new cables)     │
│    • Replicate the problem if possible; view error logs     │
│    • Determine if anything has changed                      │
└──────────────────────────────┬──────────────────────────────┘
                               ▼
┌─────────────────────────────────────────────────────────────┐
│ 2. ESTABLISH A THEORY OF PROBABLE CAUSE                     │
│    • Question the obvious (power switch, loose cable)       │
│    • Consider simple, common explanations first             │
│    • Consult documentation, knowledge bases, or internet    │
└──────────────────────────────┬──────────────────────────────┘
                               ▼
┌─────────────────────────────────────────────────────────────┐
│ 3. TEST THE THEORY TO DETERMINE CAUSE                       │
│    • Confirm your theory through targeted testing           │
│    • IF THEORY IS CONFIRMED ──▶ Proceed to Step 4           │
│    • IF THEORY FAILS ──────────▶ Form a NEW theory          │
│    • IF UNRESOLVED ────────────▶ ESCALATE to senior tech    │
└──────────────────────────────┬──────────────────────────────┘
                               ▼
┌─────────────────────────────────────────────────────────────┐
│ 4. ESTABLISH A PLAN OF ACTION & IMPLEMENT SOLUTION          │
│    • Develop step-by-step resolution plan                   │
│    • Identify and mitigate potential side effects / risks   │
│    • Implement the solution or test in a staging area       │
└──────────────────────────────┬──────────────────────────────┘
                               ▼
┌─────────────────────────────────────────────────────────────┐
│ 5. VERIFY FULL SYSTEM FUNCTIONALITY                         │
│    • Have the user test the system to ensure it works       │
│    • Implement preventive measures to stop recurrence       │
│    • Check for unintended secondary issues                  │
└──────────────────────────────┬──────────────────────────────┘
                               ▼
┌─────────────────────────────────────────────────────────────┐
│ 6. DOCUMENT FINDINGS, ACTIONS, AND OUTCOMES                 │
│    • Record the initial symptoms, cause, and solution       │
│    • Update ticketing system and corporate knowledge base   │
│    • Helps future technicians resolve identical issues      │
└─────────────────────────────────────────────────────────────┘
```

> **Troubleshooting Questioning Technique Tip:**
> - **Open-ended question:** *"What were you doing when the screen went black?"* (Lets the user explain context).
> - **Closed-ended question:** *"Did you receive an error code 404?"* (Yes/No answer to verify specific detail).
> - **Always ask:** *"Has anything changed recently (updates, relocations, new software)?"*

---

### 3.8 Comprehensive IT Acronyms to Master

| Acronym | Full Form | What It Does / Category |
|---------|-----------|-------------------------|
| **CPU** | Central Processing Unit | Main processor executing instructions |
| **GPU** | Graphics Processing Unit | Specialized processor for rendering parallel visual calculations |
| **RAM** | Random Access Memory | Fast, volatile system memory for running applications |
| **ROM** | Read-Only Memory | Non-volatile memory storing startup firmware |
| **BIOS** | Basic Input/Output System | Legacy PC startup firmware initializing hardware |
| **UEFI** | Unified Extensible Firmware Interface | Modern, secure replacement for legacy BIOS |
| **SSD** | Solid State Drive | High-speed, non-volatile flash storage with no moving parts |
| **HDD** | Hard Disk Drive | Magnetic spinning platter storage drive |
| **NIC** | Network Interface Card | Hardware controller providing network connectivity |
| **MAC** | Media Access Control | Unique physical 48-bit hardware address burned into a NIC |
| **IP** | Internet Protocol | Logical addressing system for routing data across networks |
| **DNS** | Domain Name System | Translates human-friendly domain names to IP addresses |
| **DHCP** | Dynamic Host Configuration Protocol | Automatically assigns IP addresses and subnet masks |
| **ISP** | Internet Service Provider | Organization providing telecommunication/internet access |
| **GUI** | Graphical User Interface | Visual desktop/app interface (icons, windows, menus) |
| **CLI** | Command Line Interface | Text-based prompt for direct system administration |
| **OS** | Operating System | System software managing hardware and executing applications |
| **UPS** | Uninterruptible Power Supply | Emergency battery backup system during power outages |
| **ESD** | Electrostatic Discharge | Static electricity buildup capable of frying microchips |
| **PII** | Personally Identifiable Information | Sensitive private user data subject to compliance laws |
| **AUP** | Acceptable Use Policy | Rules for appropriate use of organizational IT assets |
| **EULA** | End User License Agreement | Software legal usage contract |
| **ASCII** | American Standard Code for Information Interchange | 7/8-bit character encoding standard |
| **UTF** | Unicode Transformation Format | Universal multilingual character encoding format |

---

## 4. Domain 2 — Infrastructure (18%)

> Hardware, networking, cloud, and virtualization. Focus on *purpose* over deep technical detail.

### 4.1 Internal Computing Components

| Component | Purpose |
|-----------|---------|
| **CPU** | Executes program instructions (measured in GHz) |
| **RAM** | Holds active data for fast access; volatile (clears on shutdown) |
| **Motherboard** | Main circuit board connecting all components |
| **HDD / SSD** | Long-term, non-volatile storage |
| **PSU (Power Supply)** | Converts AC power to DC power for internal components |
| **GPU** | Handles graphics rendering; essential for gaming/video editing |
| **NIC** | Connects device to a network (wired or wireless) |
| **Optical Drive** | Reads/writes CDs, DVDs, Blu-rays |

### 4.2 Networking Fundamentals

**Key Network Devices:**

| Device | Function |
|--------|----------|
| **Router** | Connects different networks (e.g., home network to internet) |
| **Switch** | Connects devices *within* the same network (LAN) |
| **Modem** | Converts ISP signal to a usable format |
| **Access Point (AP)** | Extends wireless connectivity |
| **Firewall** | Monitors/controls incoming and outgoing traffic |

**Network Types:**

| Type | Full Name | Scope |
|------|-----------|-------|
| LAN | Local Area Network | Building/home |
| WAN | Wide Area Network | City/country/internet |
| WLAN | Wireless LAN | Wi-Fi based LAN |
| MAN | Metropolitan Area Network | City-wide |
| PAN | Personal Area Network | Bluetooth, very short range |

**IP Addressing:**
- Every device on a network has a unique **IP address**
- **IPv4:** 32-bit address (e.g., `192.168.1.1`) — running out of addresses
- **IPv6:** 128-bit address — newer, larger address space
- **Private IP:** Used inside a LAN (e.g., `192.168.x.x`)
- **Public IP:** Assigned by ISP; used to reach the internet
- **DNS** translates a domain name (e.g., `google.com`) to an IP address
- **DHCP** automatically assigns IP addresses to devices on a network

### 4.3 Virtualization

| Term | Definition |
|------|------------|
| **Virtual Machine (VM)** | A software-based computer running inside another computer |
| **Hypervisor** | Software that manages and runs VMs |
| **Type 1 Hypervisor** | Runs directly on hardware (bare-metal): VMware ESXi, Hyper-V |
| **Type 2 Hypervisor** | Runs on top of an OS: VirtualBox, VMware Workstation |
| **Snapshot** | A saved state of a VM at a point in time (easy rollback) |

**Why virtualize?**
- Better hardware utilization (run multiple OSes on one machine)
- Isolation — one VM crashing doesn't affect others
- Easy backup and restoration via snapshots

### 4.4 Cloud Computing

**Service Models:**

| Model | What the Provider Manages | Example |
|-------|--------------------------|---------|
| **IaaS** (Infrastructure as a Service) | Servers, storage, networking | AWS EC2, Azure VMs |
| **PaaS** (Platform as a Service) | OS + runtime environment | Google App Engine |
| **SaaS** (Software as a Service) | Full app delivery | Gmail, Office 365, Salesforce |

**Deployment Models:**

| Model | Description |
|-------|-------------|
| **Public Cloud** | Shared infrastructure; managed by a provider (AWS, Azure, GCP) |
| **Private Cloud** | Dedicated to one organization; more control/security |
| **Hybrid Cloud** | Mix of public and private; connects on-prem to cloud |
| **Community Cloud** | Shared by a specific group (e.g., government agencies) |

**Key Cloud Characteristics:**
- **On-demand self-service** — provision resources without human interaction
- **Broad network access** — available from anywhere with internet
- **Elasticity** — scale resources up or down dynamically
- **Measured service** — pay only for what you use
- **Multitenancy** — multiple customers share the same infrastructure

### 4.5 Networking Protocols & Communication

> This is the area your colleague was referring to — the FC0-U71 exam tests these specifically. Know the **purpose**, **protocol name**, and **port number** for each.

#### TCP vs. UDP — The Two Transport Protocols

| Feature | TCP (Transmission Control Protocol) | UDP (User Datagram Protocol) |
|---------|--------------------------------------|------------------------------|
| **Connection** | Connection-oriented (establishes a link first) | Connectionless (sends without setup) |
| **Reliability** | Guaranteed delivery; data arrives in order | No guarantee; packets may be lost or reordered |
| **Speed** | Slower due to error-checking overhead | Faster — no handshake or acknowledgment |
| **Error Checking** | Yes — retransmits lost packets | No — lost data is just dropped |
| **Best For** | Web browsing, email, file transfers, databases | Live streaming, video calls, online gaming, DNS |
| **Example Protocols** | HTTP, HTTPS, FTP, SMTP, SSH | DNS (also uses UDP), VoIP, live video |

> **Exam Tip:** TCP = reliable but slower. UDP = fast but no guarantees. A question showing "streaming video" or "online gaming" almost always points to UDP.

#### Common Application-Layer Protocols & Port Numbers

The exam expects you to match protocols to their function AND port number.

| Protocol | Full Name | Port | Function |
|----------|-----------|------|----------|
| **HTTP** | Hypertext Transfer Protocol | **80** | Loads standard (unencrypted) web pages |
| **HTTPS** | HTTP Secure | **443** | Loads encrypted web pages (uses TLS/SSL) |
| **FTP** | File Transfer Protocol | **20/21** | Transfers files between client and server (port 21 = control, 20 = data) |
| **SFTP** | Secure File Transfer Protocol | **22** | Encrypted file transfer (runs over SSH) |
| **SSH** | Secure Shell | **22** | Encrypted remote command-line access to servers |
| **Telnet** | — | **23** | Unencrypted remote access — INSECURE; replaced by SSH |
| **SMTP** | Simple Mail Transfer Protocol | **25** | Sends outgoing email from client to mail server |
| **POP3** | Post Office Protocol v3 | **110** | Downloads email to local device; removes from server |
| **IMAP** | Internet Message Access Protocol | **143** | Reads email while keeping it on the server (sync across devices) |
| **DNS** | Domain Name System | **53** | Translates domain names to IP addresses |
| **DHCP** | Dynamic Host Configuration Protocol | **67/68** | Auto-assigns IP addresses to devices |
| **RDP** | Remote Desktop Protocol | **3389** | Graphical remote desktop access (Windows) |
| **SNMP** | Simple Network Management Protocol | **161** | Monitors and manages network devices remotely |

> **Exam Tip — Email Protocols:**
> - **SMTP** = *Sending* mail (outgoing)
> - **POP3** = *Downloading* mail (removes from server)
> - **IMAP** = *Syncing* mail (stays on server — works on multiple devices)

#### MAC Address vs. IP Address

| Feature | MAC Address | IP Address |
|---------|-------------|------------|
| **Stands For** | Media Access Control | Internet Protocol |
| **Purpose** | Identifies a device on a *local* network segment | Identifies a device on a *network* (local or internet) |
| **Assigned By** | Burned into the NIC by the manufacturer | Assigned by DHCP or configured manually |
| **Changes?** | Typically permanent (hardware-level) | Can change (e.g., DHCP reassignment) |
| **Format** | 12 hex digits: `00:1A:2B:3C:4D:5E` | IPv4: `192.168.1.10` / IPv6: `2001:db8::1` |
| **Scope** | Local network only — not routed across internet | Routed globally across the internet |

#### Subnet Mask (Conceptual Understanding Only)

For Tech+, you do NOT need to perform binary subnetting math. You only need to understand the concept:

- A **subnet mask** separates an IP address into two parts:
  - **Network portion** — identifies which network the device belongs to
  - **Host portion** — identifies the specific device within that network
- **Common subnet masks:**
  - `255.255.255.0` → `192.168.1.x` — the first three octets = network; last octet = devices (up to 254 hosts)
  - `255.255.0.0` → the first two octets = network; last two = devices
- **Default Gateway:** The router IP address that devices use to send traffic *outside* their local network

> **Exam Tip:** `192.168.x.x` and `10.x.x.x` are **private IP ranges** (not routable on the internet). You'll see these in home/office LAN scenarios.

#### Wi-Fi / Wireless Standards (IEEE 802.11)

| Standard | Common Name | Max Speed | Frequency | Notes |
|----------|-------------|-----------|-----------|-------|
| 802.11a | Wi-Fi 1 | 54 Mbps | 5 GHz | Early standard; short range |
| 802.11b | Wi-Fi 2 | 11 Mbps | 2.4 GHz | Older; long range; easily interfered |
| 802.11g | Wi-Fi 3 | 54 Mbps | 2.4 GHz | Combined range of b + speed of a |
| 802.11n | **Wi-Fi 4** | 600 Mbps | 2.4 & 5 GHz | Dual-band; introduced MIMO antennas |
| 802.11ac | **Wi-Fi 5** | ~3.5 Gbps | 5 GHz only | Very fast; common in modern routers |
| 802.11ax | **Wi-Fi 6** | ~9.6 Gbps | 2.4, 5, & 6 GHz | Latest; efficient in crowded areas |

**Frequency Band Trade-offs:**

| Band | Range | Speed | Interference |
|------|-------|-------|--------------|
| **2.4 GHz** | Longer | Slower | Higher (microwaves, baby monitors, neighbors) |
| **5 GHz** | Shorter | Faster | Lower (less congestion) |
| **6 GHz** | Shortest | Fastest | Least (newest, less crowded) |

> **Exam Tip:** If a question asks about *interference* → 2.4 GHz is the culprit. If it asks about *range* → 2.4 GHz wins. If it asks about *throughput/speed* → 5 GHz or 6 GHz wins.

#### Additional Networking Terms for the Exam

| Term | Definition |
|------|------------|
| **Bandwidth** | Maximum data transfer rate of a connection (e.g., 1 Gbps) |
| **Latency** | The delay in data transmission — measured in milliseconds (ms); lower = better |
| **Throughput** | Actual data transfer rate achieved in practice (usually less than bandwidth) |
| **Packet** | A small unit of data transmitted across a network; large files are broken into packets |
| **Port** | A logical number (0–65535) that identifies a specific application or service on a device |
| **NAT** | Network Address Translation — router converts private IPs to one public IP for internet traffic |
| **SSID** | Service Set Identifier — the name of a Wi-Fi network (e.g., "HomeNetwork_5G") |
| **Ping** | A command-line tool that tests connectivity to another device/server; measures round-trip latency |
| **Traceroute** | Maps every hop (router) between your device and a destination; identifies where delays occur |

---

## 5. Domain 3 — Applications & Software (14%)

> Covers operating system mechanics, file systems, software delivery and management, browser architecture, and modern Artificial Intelligence (AI) implementations.

### 5.1 Operating System Architecture & Core Functions

An **Operating System (OS)** acts as the intermediary between hardware resources and user applications, providing hardware abstraction, multitasking, and access control.

```
┌─────────────────────────────────────────────────────────────┐
│                     USER APPLICATIONS                       │
│        (Word Processors, Web Browsers, Games, IDEs)         │
└──────────────────────────────┬──────────────────────────────┘
                               ▼
┌─────────────────────────────────────────────────────────────┐
│                      OPERATING SYSTEM                       │
│  ┌────────────────────────┐    ┌─────────────────────────┐  │
│  │   USER SPACE / SHELL   │    │      SYSTEM KERNEL      │  │
│  │  (GUI, CLI, Terminal)  │◀──▶│ (CPU, RAM, Device Mgmt) │  │
│  └────────────────────────┘    └─────────────────────────┘  │
└──────────────────────────────┬──────────────────────────────┘
                               ▼
┌─────────────────────────────────────────────────────────────┐
│                      PHYSICAL HARDWARE                      │
│            (CPU, RAM, GPU, SSD/HDD, NIC, Ports)             │
└─────────────────────────────────────────────────────────────┘
```

#### Kernel vs. Shell
- **Kernel:** The privileged core program loaded at boot that directly controls CPU scheduling, memory allocation (paging/virtual memory), file I/O, and hardware communication via device drivers.
- **Shell / User Interface:** The outer layer allowing users and programs to interact with the OS:
  - **GUI (Graphical User Interface):** Visual windows, icons, menus, pointer navigation (Windows Explorer, macOS Finder).
  - **CLI (Command Line Interface):** Text-based shell for scripting, system automation, and remote administration (Windows PowerShell, Command Prompt `cmd.exe`, Linux/macOS Bash / Zsh).

#### 32-bit (x86) vs. 64-bit (x64) Architectures

| Feature | 32-bit Architecture (x86) | 64-bit Architecture (x64) |
|---------|----------------------------|----------------------------|
| **Memory Address Width** | 32 bits ($2^{32}$ addresses) | 64 bits ($2^{64}$ addresses) |
| **Maximum Usable RAM** | **4 GB maximum** | Theoretical **16 Exabytes** (multi-TB in practice) |
| **Application Compatibility** | Can only run 32-bit applications | Can run **both 64-bit and 32-bit** applications (e.g., `Program Files (x86)` on Windows) |
| **Modern Relevance** | Legacy systems only | Standard for all modern desktop, laptop, and server OSes |

> **Exam Tip:** A 32-bit operating system cannot utilize more than 4 GB of RAM, even if 16 GB of physical RAM is installed on the motherboard.

#### Process & Service Management
- **Process / Task:** An actively running instance of a program consuming CPU cycles and RAM. Managed via:
  - *Windows:* **Task Manager** (`Ctrl + Shift + Esc`) / Resource Monitor.
  - *macOS:* **Activity Monitor**.
  - *Linux:* `top`, `htop`, `ps`, `kill` commands.
- **Service (Windows) / Daemon (Linux):** A background process that runs continuously without user interface interaction (e.g., Print Spooler, Windows Update, Apache `httpd`, SSH daemon `sshd`).
- **Device Drivers:** Specialized software modules that translate generic OS input/output commands into device-specific hardware instructions (e.g., GPU display drivers, printer drivers).

---

### 5.2 File Systems & File Management

A **file system** dictates how data is organized, named, indexed, and retrieved on physical storage media.

#### File System Comparison

| File System | Primary OS | Max File Size | Max Volume Size | Key Features |
|-------------|------------|---------------|-----------------|--------------|
| **NTFS** | Windows | 16 TB – 8 PB | 8 PB | **Permissions (ACLs), Compression, BitLocker encryption, and Journaling** (crash recovery). |
| **FAT32** | Universal (Win, Mac, Linux, Consoles) | **4 GB** (Strict Limit) | 2 TB (32 GB Windows format limit) | Universal compatibility; legacy format for USB thumb drives; **no native permissions or journaling**. |
| **exFAT** | Cross-Platform (Win & Mac) | 16 Exabytes (Virtually unlimited) | 128 Petabytes | Designed for modern high-capacity flash drives, SD cards, and external hard drives; removes FAT32's 4 GB limit. |
| **ext4** | Linux | 16 TB | 1 Exabyte | Standard Linux filesystem; high performance, robust **journaling**, and permission management. |
| **APFS** | macOS / iOS | 8 Exabytes | 8 Exabytes | Modern Apple filesystem; SSD/flash-optimized, fast cloning, space sharing, and native file encryption. |

> **Exam Tip — File System Journaling:**
> Journaling (in NTFS, ext4, APFS) writes pending file modifications to a circular log before applying them to disk. If power fails mid-write, the OS reads the journal to recover cleanly without file corruption.

#### File Attributes & Properties
- **Read-Only (R):** File can be opened and viewed, but cannot be modified, overwritten, or deleted.
- **Hidden (H):** File is concealed from standard directory views (used to prevent accidental user deletion of config files).
- **System (S):** Critical operating system file required for system boot and stability.
- **Archive (A):** Flag indicating the file has been modified since the last backup (used by incremental/differential backup software).

#### Common File Extensions & Executable Types

| Category | File Extensions | Description |
|----------|-----------------|-------------|
| **Executables & Installers** | `.exe`, `.msi` (Windows), `.app`, `.dmg` (macOS), `.deb`, `.rpm` (Linux), `.apk` (Android) | Compiled binary programs that execute code directly. |
| **Scripting / Automation** | `.bat` (Batch), `.ps1` (PowerShell), `.sh` (Bash), `.py` (Python), `.js` (JavaScript) | Plaintext commands executed line-by-line by an interpreter/shell. |
| **Compressed Archives** | `.zip`, `.tar`, `.gz`, `.7z`, `.rar`, `.iso` (Optical image) | Bundled and compressed files saving bandwidth and storage. |
| **Documents & Data** | `.docx`, `.xlsx`, `.pptx`, `.pdf`, `.txt`, `.csv`, `.json`, `.xml` | Formatted productivity and structured data interchange files. |

---

### 5.3 Software Categories, Delivery & Management

#### Software Categories & Roles
- **System Software:** Operating systems, firmware (BIOS/UEFI), device drivers.
- **Application Software:** User-facing programs:
  - *Productivity:* Word processing (Docs/Word), Spreadsheets (Excel/Sheets), Presentations (PowerPoint/Slides).
  - *Collaboration:* Real-time messaging (Slack, Teams), Video conferencing (Zoom, Meet), Email clients (Outlook).
  - *Enterprise Business Software:*
    - **CRM (Customer Relationship Management):** Tracks sales leads, customer contacts, and support tickets (Salesforce, HubSpot).
    - **ERP (Enterprise Resource Planning):** Centralized system managing accounting, supply chain, manufacturing, inventory, and payroll (SAP, Oracle).
    - **Accounting:** Invoicing, balance sheets, payroll processing (QuickBooks).
    - **Project Management:** Sprint boards, Gantt charts, task dependencies (Jira, Asana, Trello).

#### Software Delivery Models
- **Locally Installed (Desktop Apps):** Runs directly on local hardware; operates offline; requires local disk space and manual installation.
- **Cloud / Web-based Applications (SaaS):** Runs in a web browser; zero client install; automatic updates; requires internet connectivity (e.g., Google Workspace, Microsoft 365 Web).
- **Mobile Applications:** Compiled for mobile chipsets (ARM); downloaded through curated app stores (Google Play, Apple App Store); run in sandboxed environments for security.
- **Portable Applications:** Can run directly from a USB flash drive without running an installer or modifying system registry entries.

#### Software Maintenance & Lifecycles
- **Hotfix / Patch:** A small emergency update addressing a specific software bug or critical security vulnerability.
- **Feature Update:** Adds new tools or user interface enhancements.
- **Rollup / Service Pack:** A cumulative collection of hotfixes, security patches, and updates bundled into a single installer.
- **End-of-Life (EOL) / End-of-Support:** The milestone where a vendor ceases security updates, patches, and technical support. Continuing to run EOL software represents a severe organizational vulnerability.
- **Backward Compatibility:** The ability of newer software or OS versions to open, process, or execute files created in older versions.

---

### 5.4 Web Browser Architecture, Configuration & Privacy

Web browsers are the primary gateway for web-based applications and internet access.

```
┌─────────────────────────────────────────────────────────────┐
│                    WEB BROWSER INTERFACE                    │
│   (Address Bar, Tabs, Bookmarks, Navigation, Pop-up Block)   │
└──────────────────────────────┬──────────────────────────────┘
                               ▼
┌─────────────────────────────────────────────────────────────┐
│                    LOCAL BROWSER ENGINE                     │
│  ┌────────────────────────┐    ┌─────────────────────────┐  │
│  │     BROWSER CACHE      │    │     BROWSER COOKIES     │  │
│  │ (Images, CSS, JS Files)│    │(Logins, Sessions, State)│  │
│  └────────────────────────┘    └─────────────────────────┘  │
│  ┌───────────────────────────────────────────────────────┐  │
│  │    EXTENSIONS & ADD-ONS (Ad Blockers, PW Managers)    │  │
│  └───────────────────────────────────────────────────────┘  │
└──────────────────────────────┬──────────────────────────────┘
                               ▼
┌─────────────────────────────────────────────────────────────┐
│                     SECURITY VALIDATION                     │
│  (TLS/SSL Certificate Verification ──▶ Padlock Icon / HTTPS)│
└─────────────────────────────────────────────────────────────┘
```

#### Browser Features & Performance Optimization
- **Address Bar (URL Bar):** Displays current webpage location (`https://...`) and integrates default search engine queries.
- **Browser Cache:** Locally stores static web assets (high-res images, stylesheets, JavaScript libraries). Subsequent visits load these assets from the local hard drive instead of re-downloading over the internet.
  - *Troubleshooting Tip:* If a web app displays stale data or layout glitches after an update, **clearing the browser cache** resolves the issue.
- **Browser Cookies:** Small text files saved by websites:
  - *First-party Cookies:* Remember user login sessions, shopping cart items, and language preferences.
  - *Third-party Cookies:* Placed by external advertising/tracking domains to monitor browsing habits across multiple websites.

#### Browser Security, Privacy & Extensions
- **Private / Incognito Browsing:**
  - *What it does:* Prevents local browsing history, temporary cache files, autofill data, and cookies from being saved on that specific computer.
  - *What it DOES NOT do:* Does **not** hide your traffic from your ISP, corporate firewall, network administrator, or visited web servers.
- **Digital Certificates & HTTPS:**
  - Web browsers validate that a website's SSL/TLS certificate was signed by a trusted **Certificate Authority (CA)**.
  - *Certificate Errors:* If a certificate is expired, domain names don't match, or the CA is untrusted, the browser displays a full-page red security warning.
- **Extensions / Add-ons:** Mini-programs extending functionality (ad blockers, password managers, grammar checkers).
  - *Risk:* Malicious or abandoned extensions can log keystrokes, track browsing, or inject adware.
- **Pop-up Blockers:** Suppresses unsolicited secondary browser windows. Can be configured with site-specific whitelists for legitimate enterprise portals.

---

### 5.5 Artificial Intelligence (AI) — Comprehensive Tech+ Guide

The FC0-U71 exam introduces explicit testing on modern Artificial Intelligence paradigms and practical business applications.

#### AI Classification Hierarchy

```
┌─────────────────────────────────────────────────────────────┐
│             ARTIFICIAL INTELLIGENCE (AI)                    │
│    Machines simulating human cognition & problem solving    │
│  ┌───────────────────────────────────────────────────────┐  │
│  │               MACHINE LEARNING (ML)                   │  │
│  │     Systems learning patterns from training data      │  │
│  │  ┌─────────────────────────────────────────────────┐  │  │
│  │  │                 DEEP LEARNING                   │  │  │
│  │  │ Multi-layer neural networks (Vision, Speech, NLP│  │  │
│  │  └─────────────────────────────────────────────────┘  │  │
│  └───────────────────────────────────────────────────────┘  │
└─────────────────────────────────────────────────────────────┘
```

#### Generative AI vs. Predictive AI

| Feature | Generative AI | Predictive / Analytical AI |
|---------|---------------|----------------------------|
| **Core Function** | Creates **brand new, original content** (text, synthetic code, images, audio, video). | Analyzes existing datasets to **classify objects or forecast future trends**. |
| **Underlying Tech** | Large Language Models (LLMs), Diffusion models, Transformers. | Regression models, decision trees, neural classifiers. |
| **Examples** | ChatGPT, Claude, Google Gemini, DALL-E, GitHub Copilot. | Credit card fraud detection, weather forecasting, spam email filters, recommendation engines. |

#### Large Language Models (LLMs) & Prompt Engineering
- **Large Language Model (LLM):** A deep learning model trained on petabytes of text data to predict the most probable sequence of words, enabling natural conversational dialogue, text summarization, code generation, and translation.
- **Prompt:** The text, code, or context provided by a user to guide the AI's response.
- **Prompt Engineering Principles:**
  - *Role Conditioning:* Assigning a persona (*"Act as a CompTIA-certified security specialist"*).
  - *Context & Constraints:* Setting boundaries (*"Explain in 3 bullet points without technical jargon"*).
  - *Few-Shot Prompting:* Providing 1–2 desired input/output examples inside the prompt.

#### Practical Business & IT Use Cases
- **Customer Support Chatbots:** 24/7 automated level-1 helpdesk triage and answering common user queries.
- **Code Assistance & Debugging:** Generating boilerplate code, writing unit tests, and detecting syntax vulnerabilities.
- **Document Summarization:** Condensing lengthy legal contracts, technical manuals, or log files.
- **Virtual Assistants:** Voice-driven command interpretation (Siri, Alexa, Google Assistant).

#### AI Risks, Limitations & Security Considerations
- **AI Hallucinations:** When an AI generates plausible-sounding but completely fabricated, factually incorrect citations, code libraries, or statements with high confidence.
- **Data Privacy & IP Leakage (Crucial Exam Concept):**
  - Pasting proprietary source code, confidential financial spreadsheets, or customer PII into public AI models risks exposing trade secrets or having that data ingested into future model training sets.
  - *Mitigation:* Enterprise-grade AI contracts with zero-retention policies and private local model deployments.
- **Copyright & Ethical Bias:** AI models can inherit human prejudices present in their training datasets or reproduce copyrighted artistic works.

---

## 6. Domain 4 — Software Development Concepts (10%)

> Focuses on how software logic is designed, structured, and executed. You do not need to write production code — you need to understand core programming paradigms, data structures, visual logic (flowcharts), and software lifecycles.

### 6.1 Programming Language Categories & Paradigms

```
┌─────────────────────────────────────────────────────────────┐
│                 HIGH-LEVEL PROGRAMMING CODE                 │
│         (Python, JavaScript, C++, C#, Java, Rust)           │
└──────────────────────────────┬──────────────────────────────┘
                               │
               ┌───────────────┴───────────────┐
               ▼                               ▼
┌─────────────────────────────┐ ┌─────────────────────────────┐
│      COMPILER (Ahead)       │ │     INTERPRETER (Live)      │
│ Converts entire source code │ │ Executes code line-by-line  │
│ into native binary machine  │ │ at runtime in memory.       │
│ code file (.exe) prior to   │ │ (Python, Ruby, JavaScript,  │
│ execution. (C, C++, Go)     │ │ PowerShell, Bash)           │
└──────────────┬──────────────┘ └──────────────┬──────────────┘
               ▼                               ▼
┌─────────────────────────────────────────────────────────────┐
│                    NATIVE MACHINE CODE                      │
│            Binary instructions (0s and 1s) for CPU          │
└─────────────────────────────────────────────────────────────┘
```

#### Language Categories Comparison

| Category | How It Works | Key Advantages | Disadvantages | Examples |
|----------|--------------|----------------|---------------|----------|
| **Compiled** | A compiler translates the entire source code file into a native binary executable file (`0`s and `1`s) *before* it runs. | Fastest runtime performance; direct hardware/memory access; syntax errors caught before release. | Platform-specific output (must recompile for Windows/Mac/Linux); longer build cycles. | C, C++, Rust, Go |
| **Interpreted** | An interpreter reads and executes source code line-by-line in real time at runtime. | High portability; rapid prototyping and testing without waiting for compilation. | Slower execution speed; syntax bugs may only trigger when a specific line of code runs. | Python, Ruby, JavaScript, PHP |
| **Hybrid / Bytecode** | Code is compiled into intermediate bytecode, which executes inside a Virtual Machine (JVM / .NET CLR). | "Write once, run anywhere"; strong memory management. | Slight VM runtime overhead compared to pure compiled C. | Java, C# (.NET) |
| **Scripting** | Lightweight interpreted language designed to automate tasks, manipulate files, or control other applications. | Rapid automation; easy to learn and write. | Not suited for heavy computation or standalone enterprise software. | PowerShell, Bash, Python, JavaScript |
| **Assembly** | Lowest-level human-readable language; uses 1-to-1 mnemonics (`MOV`, `ADD`, `JMP`) directly mapping to CPU micro-instructions. | Maximum possible speed and microsecond hardware control. | Extremely complex to write; strictly tied to one specific CPU architecture (x86 vs ARM). | x86 Assembly, ARM Assembly |
| **Markup** | Formats, structures, and presents data using tags; **contains no programmatic logic** (no variables, arithmetic, or loops). | Universal standard for document layouts and data interchange. | Cannot perform calculations or execute conditional algorithms. | HTML, XML, Markdown, JSON |
| **Query** | Declarative language designed specifically to interact with, search, and manipulate database tables. | Optimized for relational data operations. | Specialized for databases; not a general-purpose programming language. | SQL (Structured Query Language) |

---

### 6.2 Data Types, Identifiers & Data Structures

#### Identifiers: Variables vs. Constants
- **Identifier:** A programmer-assigned name given to an entity (variable, constant, function, class).
- **Variable:** A named memory container whose stored value **can change** dynamically during program execution (e.g., `userScore = 100`, `userScore = userScore + 50`).
- **Constant:** A named value that is permanently locked at declaration and **cannot be modified** at runtime (e.g., `const PI = 3.14159`, `const MAX_RETRY_COUNT = 3`).

#### Fundamental Data Types

| Data Type | Description | Memory / Value Range | Example Values |
|-----------|-------------|----------------------|----------------|
| **Char** | A single character, letter, digit, or symbol in single quotes | 1 byte (ASCII) / 2 bytes | `'A'`, `'z'`, `'9'`, `'#'` |
| **String** | An ordered sequence of text characters in quotes | Variable width | `"Hello World"`, `"FC0-U71"` |
| **Integer (int)** | Whole positive or negative numbers (no decimals) | 32-bit / 64-bit | `42`, `-10`, `0`, `2048` |
| **Float / Double** | Numbers with fractional decimal points. Double provides double the precision (64-bit vs 32-bit float). | 32-bit (Float) / 64-bit (Double) | `3.14159`, `-0.005`, `99.99` |
| **Boolean (bool)** | Logical binary state with exactly two possible values | 1 bit (0 or 1) | `True`, `False` |

#### Composite Data Structures
- **Array / List:** An ordered, zero-indexed collection of items of the same data type:
  ```
  fruits = ["Apple", "Banana", "Cherry"]
  fruits[0]  ──▶  "Apple"
  fruits[1]  ──▶  "Banana"
  ```
- **Dictionary / Map / Key-Value Pair:** A collection of unique keys linked to associated values:
  ```
  userProfile = {
      "username": "jreniel",
      "role": "Administrator",
      "active": True
  }
  ```

---

### 6.3 Control Structures & Program Flow Control

Every computer algorithm is constructed using three basic control structures: **Sequence**, **Selection (Branching)**, and **Iteration (Looping)**.

#### 1. Branching & Conditionals (Decision Making)
Directs code execution along different paths based on whether a condition evaluates to `True` or `False`.

```
// Standard IF / ELSE statement
IF userAge >= 18 THEN
    display "Access Granted to System"
ELSE
    display "Access Denied: Must be 18+"
ENDIF

// SWITCH / CASE statement (clean multi-branch selection)
SWITCH (dayOfWeek):
    CASE 1: print "Monday"; break
    CASE 2: print "Tuesday"; break
    DEFAULT: print "Other Day"; break
```

#### 2. Looping & Iteration (Repetition)
Repeats a block of code multiple times based on a counter or condition.

| Loop Type | When Checked | Guaranteed Executions | Common Use Case |
|-----------|--------------|-----------------------|-----------------|
| **FOR Loop** | Start of iteration | 0 or more times | When the exact number of iterations is known in advance (e.g., iterate 10 times). |
| **WHILE Loop** | **Before** each iteration | 0 or more times | Repeats while a condition is True. If condition is False initially, loop body never runs. |
| **DO-WHILE Loop** | **After** each iteration | **At least 1 time** | Executes the code block first, then evaluates the condition to decide if it should repeat. |

```
// FOR Loop Example (known count)
FOR count = 1 TO 5
    print "Packet transmitted: " + count
ENDFOR

// WHILE Loop Example (pre-condition check)
WHILE batteryPercent > 10
    runDiagnostics()
    batteryPercent = batteryPercent - 1
ENDWHILE

// DO-WHILE Loop Example (post-condition check — runs at least once)
DO
    userPassword = promptUser("Enter Admin Password: ")
WHILE validate(userPassword) == False
```

> **Exam Warning — Infinite Loops:** If a loop lacks a condition that eventually evaluates to `False` (e.g., `WHILE True` without a `break`), the program hangs or crashes.

#### 3. Functions, Parameters & Return Values
A **Function** (or Method/Subroutine) is a named, reusable block of code designed to perform a single specific task.
- **Parameters / Arguments:** Variables passed into the function as input.
- **Return Value:** The output data sent back to the calling line of code upon completion.

```
FUNCTION calculateTax(subtotal, taxRate):
    taxAmount = subtotal * taxRate
    RETURN taxAmount
ENDFUNCTION

// Calling the function:
finalTax = calculateTax(100, 0.08)  // finalTax receives 8.00
```

---

### 6.4 Visual & Organizational Logic Tools

Before writing code, software engineers use visual and text-based modeling tools to design algorithms.

#### Standard Flowchart Symbols (Crucial Exam Concept)

```
┌─────────────────────────────────────────────────────────────┐
│                 FLOWCHART SYMBOLS GUIDE                     │
│                                                             │
│       ( START / END )        ──▶  OVAL / PILL               │
│                                   (Terminator: Start or End)│
│              │                                              │
│              ▼                                              │
│       ┌─────────────┐        ──▶  RECTANGLE                 │
│       │   PROCESS   │             (Calculation, Action,     │
│       └─────────────┘              Variable Assignment)     │
│              │                                              │
│              ▼                                              │
│       /  INPUT/OUT  /        ──▶  PARALLELOGRAM             │
│      /   DATA FLOW /              (User input or screen     │
│     /─────────────/                display)                 │
│              │                                              │
│              ▼                                              │
│            /\                                               │
│           /  \               ──▶  DIAMOND                   │
│          <DEC >                   (Decision / Branching:    │
│           \  /                     True/False test)         │
│            \/                                               │
└─────────────────────────────────────────────────────────────┘
```

| Flowchart Symbol | Name | Function in Diagram |
|------------------|------|---------------------|
| **Oval / Rounded Pill** | **Terminator** | Indicates the official **Start** or **End** of the algorithm. |
| **Rectangle** | **Process** | Represents a computational task, action, arithmetic calculation, or variable assignment (e.g., `x = y + 2`). |
| **Diamond** | **Decision** | Represents a conditional branch test (e.g., `Is balance > 0?`). Has multiple exit arrows (`Yes`/`No` or `True`/`False`). |
| **Parallelogram** | **Input / Output (I/O)** | Represents entering data into the system (e.g., `Read temperature`) or outputting data (e.g., `Display alert message`). |
| **Arrow** | **Flow Line** | Connects symbols to indicate the chronological direction of execution flow. |

#### Pseudocode
**Pseudocode** is an informal, human-readable outline of program logic that uses programming conventions (like `IF`, `WHILE`, `PRINT`) without requiring valid syntax of any specific programming language.

```
START
    PROMPT user for "hourlyRate"
    PROMPT user for "hoursWorked"
    IF hoursWorked > 40 THEN
        overtime = hoursWorked - 40
        grossPay = (40 * hourlyRate) + (overtime * hourlyRate * 1.5)
    ELSE
        grossPay = hoursWorked * hourlyRate
    ENDIF
    DISPLAY "Gross Pay is: " + grossPay
END
```

---

### 6.5 Boolean Logic & Truth Tables

Computers use **Boolean Logic** gates to make decisions at both hardware (transistors) and software levels.

| Input A | Input B | **AND** (`A && B`) | **OR** (`A \|\| B`) | **XOR** (`A ^ B`) | **NOT A** (`!A`) |
|:-------:|:-------:|:------------------:|:-------------------:|:-----------------:|:----------------:|
| `False` | `False` | `False` | `False` | `False` | `True` |
| `False` | `True` | `False` | `True` | `True` | `True` |
| `True` | `False` | `False` | `True` | `True` | `False` |
| `True` | `True` | **`True`** | **`True`** | **`False`** | `False` |

- **AND:** Returns `True` **only if BOTH** inputs are `True`.
- **OR:** Returns `True` if **AT LEAST ONE** input is `True`.
- **XOR (Exclusive OR):** Returns `True` if **EXACTLY ONE** input is `True`, but `False` if both are `True` or both are `False`.
- **NOT:** Inverts the boolean input value (`NOT True = False`).

---

### 6.6 Object-Oriented Programming (OOP) Concepts

**Object-Oriented Programming (OOP)** is a design paradigm where software is organized around self-contained entities called **Objects**, which combine data and functionality.

```
┌─────────────────────────────────────────────────────────────┐
│                 CLASS BLUEPRINT: "Server"                   │
│  ┌───────────────────────────────────────────────────────┐  │
│  │ ATTRIBUTES (Properties / Data):                       │  │
│  │ • ipAddress                                           │  │
│  │ • hostname                                            │  │
│  │ • isOnline                                            │  │
│  └───────────────────────────────────────────────────────┘  │
│  ┌───────────────────────────────────────────────────────┐  │
│  │ METHODS (Behaviors / Functions):                      │  │
│  │ • reboot()                                            │  │
│  │ • sendPing()                                          │  │
│  └───────────────────────────────────────────────────────┘  │
└──────────────────────────────┬──────────────────────────────┘
                               ▼
┌─────────────────────────────────────────────────────────────┐
│               CONCRETE OBJECT INSTANCE: "webServer01"        │
│ • ipAddress = "192.168.1.50"                                │
│ • hostname  = "web-prod-01"                                 │
│ • isOnline  = True                                          │
│ ──▶ webServer01.reboot()                                    │
└─────────────────────────────────────────────────────────────┘
```

- **Class:** A template or blueprint defining the attributes and methods that instances will possess.
- **Object / Instance:** A concrete, distinct realization of a class created in memory at runtime.
- **Attributes / Properties / Fields:** Data values describing the object state.
- **Methods:** Callable functions representing behaviors the object can execute.
- **Core OOP Principles:**
  - **Encapsulation:** Bundling data and methods into a single unit and restricting direct external access to internal data fields.
  - **Inheritance:** Enabling a new "child" class to automatically inherit properties and methods from an existing "parent" class (e.g., class `DatabaseServer` inherits all features of class `Server`).

---

### 6.7 Software Development Life Cycle (SDLC) & Version Control

#### SDLC Phases
The systematic process for planning, developing, testing, and maintaining software:

1. **Planning & Feasibility:** Defining project scope, budget, and feasibility.
2. **Requirements Analysis:** Gathering end-user feature requests and technical specifications.
3. **Design & Architecture:** Creating database schemas, UI wireframes, flowcharts, and system architecture.
4. **Development / Coding:** Writing software source code in an IDE.
5. **Testing & QA:** Performing unit testing, integration testing, bug tracking, and security scans.
6. **Deployment & Release:** Releasing software to production servers or app stores.
7. **Maintenance & Patching:** Issuing ongoing bug fixes, security patches, and performance optimizations.

#### SDLC Methodologies: Waterfall vs. Agile vs. DevOps
- **Waterfall:** Linear, sequential model where each phase must be fully signed off before the next begins. Rigid and slow to adapt to changing requirements.
- **Agile / Scrum:** Iterative, flexible framework delivering working software increments in short 1- to 4-week **sprints** with frequent customer feedback.
- **DevOps:** Culture and tooling combining Development (Dev) and IT Operations (Ops) using **CI/CD (Continuous Integration / Continuous Delivery)** pipelines for automated testing and deployment.

#### Version Control Systems (Git)
- **Repository (Repo):** Centralized directory containing all project code, branches, and full historical change records.
- **Commit:** A saved snapshot of file modifications recorded with an author timestamp and descriptive message.
- **Branch:** An independent workspace fork allowing a developer to build a new feature without breaking the primary production codebase (`main`/`master`).
- **Merge / Pull Request:** A formal review process to inspect and combine branch changes back into the main branch.

---

## 7. Domain 5 — Database Fundamentals (13%)

> Focuses on how data is structured, categorized, queried, analyzed, and protected. Covers relational structures, SQL CRUD operations, non-relational alternatives, and disaster recovery backup strategies.

### 7.1 The Value of Data, Big Data & Analytics

Data is a core organizational asset. Understanding how raw data is collected, cleansed, analyzed, and secured drives modern business decisions.

```
┌─────────────────────────────────────────────────────────────┐
│                 DATA ASSET PIPELINE (ETL)                   │
│                                                             │
│   [ OPERATIONAL DATA ]       [ ETL ENGINE ]     [ ANALYTICS & BI ]
│  • Transaction DBs     ──▶  • Extract      ──▶  • Data Warehouse   │
│  • IoT Sensor Logs          • Transform         • BI Dashboards    │
│  • Web Event Streams        • Load              • ML Analytics     │
└─────────────────────────────────────────────────────────────┘
```

#### Key Concepts & Terminology
- **Data as an Asset:** Proprietary business information, customer records, and transaction logs that provide competitive advantages and financial value.
- **Critical vs. Non-Critical Data:**
  - *Critical Data:* Essential for immediate business operations or strictly regulated by law (e.g., credit card records under PCI-DSS, patient health records under HIPAA, customer PII). Requires fault-tolerant storage and continuous backups.
  - *Non-Critical Data:* Temporary log files, marketing mockups, or non-essential cache files.
- **Big Data (The 3 Vs):**
  - **Volume:** Massive scale of data generated (Terabytes, Petabytes, Exabytes).
  - **Velocity:** Extreme speed at which new data arrives and must be ingested in real time (e.g., financial market trade feeds, live telemetry).
  - **Variety:** Diverse data types arriving in structured tables, semi-structured JSON, and unstructured audio/video.
- **Data Warehouse vs. Data Lake:**
  - **Data Warehouse:** A centralized database repository of cleaned, structured, and normalized historical data specifically optimized for **Business Intelligence (BI)** reporting, executive dashboards, and analytical queries (OLAP).
  - **Data Lake:** A massive storage repository holding raw, unfiltered data in its native format (structured, semi-structured, and unstructured) until a specific analytical need arises.
- **The ETL Process:**
  1. **Extract:** Retrieve raw data from disparate operational sources (databases, log files, APIs).
  2. **Transform:** Cleanse, deduplicate, validate, normalize, and format the data to ensure consistency.
  3. **Load:** Insert the transformed, structured data into the target data warehouse.

---

### 7.2 Database Architecture, Structures & Relational Integrity

A **Database Management System (DBMS)** is specialized software that provides centralized data storage, multi-user concurrent access, security controls, and fast indexed searching.

```
┌─────────────────────────────────────────────────────────────┐
│             RELATIONAL DATABASE ARCHITECTURE                │
│                                                             │
│  ┌─────────────────────────┐       ┌──────────────────────┐ │
│  │   CUSTOMERS (Parent)    │       │   ORDERS (Child)     │ │
│  ├─────────────────────────┤       ├──────────────────────┤ │
│  │ [PK] CustomerID  (101)  │◀──┐   │ [PK] OrderID   (5001)│ │
│  │      FirstName   (Alice)│   └───┼─[FK] CustomerID(101) │ │
│  │      Email       (a@...)│       │      OrderTotal($99) │ │
│  └─────────────────────────┘       └──────────────────────┘ │
└─────────────────────────────────────────────────────────────┘
```

#### Structural Hierarchy in Relational Databases (RDBMS)
- **Database:** The overall container holding related tables, views, stored procedures, and security roles.
- **Schema:** The structural architectural blueprint defining tables, column definitions, data types, constraints, and relationships.
- **Table / Entity / Relation:** A two-dimensional grid of rows and columns storing records for a specific subject (e.g., `Employees`, `Products`).
- **Record / Row / Tuple:** A single, complete horizontal entry representing an instance of an entity (e.g., Employee ID #1042).
- **Field / Column / Attribute:** A vertical category holding a specific property of the entity, enforced with a strict data type (e.g., `HireDate DATE`, `Salary INT`).

#### Keys & Referential Integrity
- **Primary Key (PK):** A column (or combination of columns) that **uniquely identifies every individual row** in a table.
  - *Golden Rules:* Must be unique for every record; **can NEVER be NULL**; every well-designed table must have one.
- **Foreign Key (FK):** A column in a "child" table that references the Primary Key of a "parent" table, creating a relational link between them.
- **Referential Integrity:** A database constraint ensuring that a Foreign Key value must always correspond to an existing, valid Primary Key record in the parent table.
  - *Prevents:* "Orphaned" child records (e.g., prevents creating an Order for a Customer ID that does not exist).

#### Relationship Multiplicities
- **One-to-One (1:1):** Each record in Table A relates to exactly one record in Table B (e.g., `Employee` to `CompanyVehicle`).
- **One-to-Many (1:N):** One record in Table A relates to multiple records in Table B (e.g., One `Customer` places multiple `Orders`). This is the most common relational pattern.
- **Many-to-Many (N:M):** Multiple records in Table A relate to multiple records in Table B (e.g., `Students` enrolled in multiple `Courses`). Requires an intermediate **junction / linking table** containing foreign keys from both parent tables.

---

### 7.3 Data Categories & Database Paradigms

```
┌─────────────────────────────────────────────────────────────┐
│                    DATA STRUCTURE SPECTRUM                  │
│                                                             │
│  STRUCTURED             SEMI-STRUCTURED        UNSTRUCTURED │
│  • Relational Tables    • JSON Files           • MP4 Videos │
│  • SQL Databases        • XML Documents        • Audio WAVs │
│  • Strict Schema        • Key-Value Tags       • Scanned PDF│
└─────────────────────────────────────────────────────────────┘
```

#### Data Classification Comparison

| Category | Definition | Structure | Storage & Query Tools | Examples |
|----------|------------|-----------|-----------------------|----------|
| **Structured Data** | Highly organized data following a strict, predefined tabular schema. | Rows and columns with explicit data types. | Relational DBMS (RDBMS), SQL queries. | SQL databases (PostgreSQL, MySQL), Excel spreadsheets. |
| **Semi-Structured Data** | Does not conform to rigid table schemas, but contains organizational markers, tags, or key-value hierarchies. | Self-describing data trees and key-value pairs. | Document databases, NoSQL, text parsers. | JSON, XML, YAML, CSV files. |
| **Unstructured Data** | Data lacking any predefined conceptual schema or formatting model (~80% of corporate data). | Raw binary, media streams, free-form text. | Object storage, Data Lakes, blob storage. | Video recordings, audio files, photos, PDF manuals, email bodies. |

#### Relational (SQL) vs. Non-Relational (NoSQL) Databases

| Feature | Relational (SQL / RDBMS) | Non-Relational (NoSQL) |
|---------|--------------------------|------------------------|
| **Data Model** | Tabular (Rows & Columns) with fixed schemas | Flexible schemas (Documents, Key-Value, Graphs) |
| **Query Language** | SQL (Structured Query Language) | Proprietary APIs, JSON-based query syntax |
| **Scalability** | Vertical (Scale Up: bigger CPU/RAM on one server) | Horizontal (Scale Out: distribute across clusters of commodity servers) |
| **ACID Compliance** | Strict ACID transactional integrity | Optimized for high velocity, eventual consistency |
| **Leading Engines** | PostgreSQL, MySQL, Microsoft SQL Server, Oracle, SQLite | MongoDB (Document), Redis (Key-Value), Cassandra (Columnar), Neo4j (Graph) |
| **Flat File Alternative** | .csv / .xlsx files (Single sheet, no relationships, no concurrency, lacks security) | — |

---

### 7.4 Structured Query Language (SQL) & CRUD Operations

SQL is the universal declarative language used to manage, define, and query relational databases.

#### The CRUD Framework

| CRUD Operation | SQL Category | Primary SQL Command | Purpose & Example |
|----------------|--------------|---------------------|-------------------|
| **C**reate | DML / DDL | `INSERT INTO` / `CREATE` | Adds new data records / creates new database tables. |
| **R**ead | DML | `SELECT` | Queries and retrieves records matching search criteria. |
| **U**pdate | DML | `UPDATE` | Modifies existing data values in one or more records. |
| **D**elete | DML / DDL | `DELETE` / `DROP` | Removes data records (`DELETE`) or removes entire tables (`DROP`). |

#### Core SQL Commands in Action

```sql
-- 1. DATA DEFINITION LANGUAGE (DDL) — Schema Creation
CREATE TABLE Customers (
    CustomerID INT PRIMARY KEY,
    FullName VARCHAR(100) NOT NULL,
    Email VARCHAR(100) UNIQUE,
    City VARCHAR(50)
);

-- 2. CREATE (INSERT) — Adding records
INSERT INTO Customers (CustomerID, FullName, Email, City)
VALUES (101, 'John Reniel', 'john@example.com', 'Manila');

-- 3. READ (SELECT) — Querying with conditions & sorting
SELECT FullName, Email 
FROM Customers 
WHERE City = 'Manila' 
ORDER BY FullName ASC;

-- 4. UPDATE — Modifying data (CRITICAL: Always use WHERE clause!)
UPDATE Customers 
SET City = 'Cebu' 
WHERE CustomerID = 101;

-- 5. DELETE — Removing data (CRITICAL: Always use WHERE clause!)
DELETE FROM Customers 
WHERE CustomerID = 101;

-- 6. RELATIONAL QUERY (INNER JOIN) — Merging related tables
SELECT Orders.OrderID, Customers.FullName, Orders.TotalAmount
FROM Orders
INNER JOIN Customers ON Orders.CustomerID = Customers.CustomerID
WHERE Orders.TotalAmount > 100;

-- 7. REMOVING AN ENTIRE TABLE (DDL)
DROP TABLE OldCustomerArchive;
```

> **Exam Warning — The Missing WHERE Clause:**
> Executing `UPDATE Customers SET City = 'Cebu';` without a `WHERE` clause will overwrite the city of **EVERY customer in the entire database**. Executing `DELETE FROM Customers;` without a `WHERE` clause deletes **all records in the table**.

---

### 7.5 Data Protection, Backups & Disaster Recovery

Data loss can result from hardware failures, ransomware, accidental deletion, or natural disasters. Organizations implement structured backup policies to ensure business continuity.

```
┌─────────────────────────────────────────────────────────────┐
│                     THE 3-2-1 BACKUP RULE                   │
│                                                             │
│       ┌─────────────┐       ┌─────────────┐                 │
│       │  3 COPIES   │       │  2 STORAGE  │   ┌───────────┐ │
│       │   OF DATA   │  ──▶  │ MEDIA TYPES │──▶│ 1 OFF-SITE│ │
│       │(1 Prod + 2) │       │(Disk + NAS) │   │ (Cloud/DC)│ │
│       └─────────────┘       └─────────────┘   └───────────┘ │
└─────────────────────────────────────────────────────────────┘
```

#### Backup Methods Comparison

| Backup Method | What It Backs Up | Storage Required | Backup Speed | Restoration Speed & Process |
|---------------|------------------|------------------|--------------|-----------------------------|
| **Full Backup** | Complete copy of **all data** on the system. | Highest storage consumption | Slowest backup time | **Fastest single-step restoration** (only needs the 1 full backup set). |
| **Incremental Backup** | Backs up only data that has **changed since the LAST backup of any type** (Full or Incremental). | Lowest storage consumption | Fastest backup time | **Slowest / complex restoration** (requires the initial Full backup + *every* subsequent Incremental backup in exact sequence). |
| **Differential Backup** | Backs up all data that has **changed since the LAST FULL backup**. | Moderate storage consumption | Moderate backup time | **Fast 2-step restoration** (requires the initial Full backup + *only the single latest* Differential backup). |
| **Snapshot / Image** | Byte-level point-in-time image of an entire virtual machine or storage volume. | Variable (uses delta pointers) | Fast capture | Rapid rollback to a specific point in time. |

#### The 3-2-1 Backup Rule (CompTIA Best Practice)
- **3** Total copies of important data (1 active production copy + 2 backup copies).
- **2** Different storage media types (e.g., internal RAID array + external tape/NAS).
- **1** Copy stored **off-site** (cloud storage or remote geographic facility) to survive physical site disasters (fire, flood, theft).

#### Business Continuity Metrics (RPO vs. RTO)
- **RPO (Recovery Point Objective):** The maximum tolerable volume of **data loss** measured in time.
  - *Question Answered:* *"How far back in time can our restored data be?"*
  - *Example:* If backups run once every 24 hours at midnight and a crash occurs at 11:00 PM, up to 23 hours of data is lost. If an organization has an RPO of 1 hour, backups/replication must occur hourly.
- **RTO (Recovery Time Objective):** The maximum tolerable duration of **system downtime** before business operations must be restored.
  - *Question Answered:* *"How long can the system be offline while technicians restore it?"*
  - *Example:* An RTO of 30 minutes mandates automated failover mechanisms.

---

## 8. Domain 6 — Security (19%)

> Second-highest weighted domain. Focuses on information security principles, threat mitigation, authentication factors, cryptography, device hardening, and wireless network defense. Expect scenario-based questions where you must identify the appropriate control or attack vector.

### 8.1 Core Security Principles, Frameworks & Compliance

```
┌─────────────────────────────────────────────────────────────┐
│                    THE CIA TRIAD OF INFOSEC                 │
│                                                             │
│                    CONFIDENTIALITY                          │
│                   /               \                         │
│       (Encryption, ACLs,     (Hashing, Digital Signatures,  │
│        Least Privilege)       Integrity Checks)             │
│                 /                   \                       │
│      AVAILABILITY ───────────────── INTEGRITY               │
│  (RAID, Backups, UPS, Redundancy, DDoS Defense)             │
└─────────────────────────────────────────────────────────────┘
```

#### The CIA Triad
- **Confidentiality:** Ensuring that sensitive data is accessible **only to authorized individuals, entities, or processes**.
  - *Controls:* Cryptographic encryption (AES/BitLocker), Access Control Lists (ACLs), Multi-Factor Authentication (MFA), Principle of Least Privilege.
- **Integrity:** Ensuring that data remains **accurate, consistent, and unaltered** by unauthorized modification, tampering, or malicious corruption.
  - *Controls:* Cryptographic hashing (SHA-256, MD5 checksums), Digital Signatures, write-protection, database constraints.
- **Availability:** Ensuring that systems, networks, and applications are **fully operational and accessible to authorized users when needed**.
  - *Controls:* Hardware redundancy (RAID), redundant power supplies, Uninterruptible Power Supplies (UPS), fault-tolerant clustering, automated backups, DDoS mitigation.

#### The AAA Security Framework
- **Authentication:** Verifying the declared identity of a user or system (*"Who are you and prove it?"* — Passwords, biometrics, hardware tokens).
- **Authorization:** Determining the specific permissions, rights, and resource access granted to an authenticated user (*"What are you allowed to do?"* — Read, Write, Execute, Admin rights).
- **Accounting (Auditing):** Tracking, measuring, and recording user sessions, resource access, and system activities in persistent audit logs (*"What did you do, when did you do it, and what was the outcome?"*).

#### Additional Key Concepts
- **Non-Repudiation:** A security assurance that a sender or actor cannot deny having performed an action, executed a transaction, or transmitted a message (enacted via **Digital Signatures** and Public Key Infrastructure).
- **Principle of Least Privilege:** Security standard dictating that users and software processes must only be granted the minimum permissions necessary to accomplish their assigned job duties — nothing more.
- **Personally Identifiable Information (PII) & Compliance:**
  - *PII:* Any data that can distinguish or trace an individual's identity (e.g., Social Security Number, biometric data, driver's license, credit card numbers).
  - *GDPR (General Data Protection Regulation):* Strict EU privacy law mandating user consent, data protection by design, and the "Right to be Forgotten."
  - *HIPAA (Health Insurance Portability and Accountability Act):* US standard regulating patient Protected Health Information (PHI).
  - *PCI-DSS:* Strict industry standard for organizations that process, store, or transmit credit cardholder data.

---

### 8.2 Threat Landscape, Malware & Attack Vectors

```
┌─────────────────────────────────────────────────────────────┐
│                    MALWARE CLASSIFICATION                   │
│                                                             │
│  • VIRUS       ──▶  Attaches to host file; REQUIRES human   │
│                     action to execute and replicate.        │
│  • WORM        ──▶  Standalone; self-replicates across      │
│                     networks WITHOUT human action.          │
│  • TROJAN      ──▶  Disguised as legitimate utility; opens  │
│                     covert backdoor for remote access.      │
│  • RANSOMWARE  ──▶  Encrypts user files; extorts payment    │
│                     for decryption key.                     │
│  • ROOTKIT     ──▶  Replaces OS kernel binaries to maintain │
│                     stealthy administrative control.        │
└─────────────────────────────────────────────────────────────┘
```

#### Malware Taxonomy

| Malware Type | Spreading Mechanism | Primary Impact & Behaviors | Key Clue on Exam |
|--------------|---------------------|----------------------------|------------------|
| **Virus** | Human executes infected executable file or macro. | Corrupts files, consumes resources, alters system boot sectors. | "User opened an infected email attachment..." |
| **Worm** | Self-replicates across networks automatically via software vulnerabilities. | Rapid network bandwidth exhaustion, automated mass exploitation. | "Spreads across the entire corporate network without user intervention..." |
| **Trojan** | Disguises as useful software (game, utility, free antivirus). | Installs hidden backdoors, keyloggers, or unauthorized remote access tools. | "User downloaded a free screen recorder that opened a backdoor..." |
| **Ransomware** | Phishing email or exploit kit executes strong cryptographic payload. | Encrypts local and network shared files; displays countdown extortion ransom note. | "Files have .locked extensions and demand bitcoin payment..." |
| **Spyware / Keylogger** | Bundled in freeware or drive-by web downloads. | Silently records keystrokes, steals passwords, monitors screen activity. | "Passwords and banking credentials stolen silently in the background..." |
| **Adware** | Bundled with free software installers. | Hijacks browser default search engine and generates continuous intrusive pop-up ads. | "Unwanted pop-up advertisements appear continuously..." |
| **Rootkit** | Exploits system privileges to inject into OS kernel space. | Modifies low-level system binaries; hides active processes from antivirus scanners and Task Manager. | "Malware undetected by standard antivirus that replaces OS kernel files..." |

#### Social Engineering Attacks (Manipulating the Human Element)

| Social Attack | Attack Vector & Methodology | Mitigation Strategy |
|---------------|-----------------------------|---------------------|
| **Phishing** | Broad fraudulent emails impersonating trusted brands (banks, PayPal) with malicious links. | Email spam filters, security awareness training. |
| **Spear Phishing** | Highly customized, researched phishing email targeting a specific individual or department. | Verification protocols for financial transfers. |
| **Whaling** | Spear phishing specifically targeting senior corporate executives (CEO, CFO, Board members). | Strict out-of-band wire transfer confirmation. |
| **Vishing & Smishing** | Voice phishing phone calls (Vishing) or fraudulent SMS text messages (Smishing). | Never share 2FA codes or credentials over phone/text. |
| **Pretexting** | Creating an elaborate invented scenario/backstory to trick an employee into surrendering confidential records. | Employee verification protocols and background checks. |
| **Baiting** | Leaving infected USB flash drives in parking lots, waiting rooms, or lobbies labeled "Confidential Payroll." | Disabling AutoRun, security awareness training, endpoint USB lockouts. |
| **Tailgating (Piggybacking)** | Physically following an authorized person through a secured door or badge turnstile without scanning an access badge. | Security guards, mantraps (two-door airlocks), turnstiles, badge enforcement. |
| **Shoulder Surfing** | Visually spying on another person's screen, keyboard, or PIN pad in public spaces (airports, cafes). | Polarized privacy screen filters, shielding keypad with hand. |
| **Dumpster Diving** | Searching through discarded corporate trash bins for paper documents containing passwords, customer PII, or network diagrams. | Cross-cut paper shredders, locked document disposal bins. |

#### System & Network Attacks
- **Brute Force Attack:** Automated tool attempting every possible mathematical combination of characters until it discovers the correct password.
- **Dictionary Attack:** Automated attack attempting passwords from a precompiled list of common dictionary words, slang, and leaked passwords.
- **Man-in-the-Middle (MitM) / On-Path:** Attacker secretly intercepts, alters, and relays communication between two parties who believe they are communicating securely.
- **Denial of Service (DoS / DDoS):** Overwhelming a target server or network with massive flood traffic to exhaust resources and take services offline (Distributed DoS uses a coordinated **botnet** of compromised zombie devices).

---

### 8.3 Device Hardening, Password Hygiene & Multi-Factor Authentication

```
┌─────────────────────────────────────────────────────────────┐
│             MULTI-FACTOR AUTHENTICATION (MFA)               │
│                                                             │
│   SOMETHING YOU KNOW        SOMETHING YOU HAVE       SOMETHING YOU ARE
│  ┌────────────────────┐    ┌────────────────────┐   ┌────────────────────┐
│  │ • Password         │    │ • Authenticator App│   │ • Fingerprint Scan │
│  │ • PIN Number       │ +  │ • Hardware YubiKey │ + │ • Facial (FaceID)  │
│  │ • Security Question│    │ • Smart Card       │   │ • Iris/Retina Scan │
│  └────────────────────┘    └────────────────────┘   └────────────────────┘
│  *CRUCIAL: Must combine at least 2 DIFFERENT factor categories!*
└─────────────────────────────────────────────────────────────┘
```

#### Password Best Practices & Account Policies
- **Length & Complexity:** Minimum 12–16 characters mixing uppercase letters, lowercase letters, numbers, and special symbols (`!@#$%^&*`). Passphrases consisting of 4+ random unrelated words offer superior entropy and user recall.
- **Account Lockout Policies (Crucial Exam Concept):** Automatically locking a user account after 3 to 5 consecutive failed login attempts. **Neutralizes online brute-force and dictionary attacks**.
- **Password History & Expiration:** Preventing users from recycling their previous 5–10 passwords when rotating credentials.
- **Password Managers:** Secure cryptographic vaults that generate, encrypt, and auto-fill unique, complex passwords for every website.

#### Multi-Factor Authentication (MFA)
MFA requires a user to present **two or more distinct authentication factors** from different categories:

| Factor Category | Description | Real-World Examples |
|-----------------|-------------|---------------------|
| **Something you Know (Knowledge)** | Information the user memorizes | Passwords, PINs, mother's maiden name security questions. |
| **Something you Have (Possession)** | A physical object or hardware device owned by the user | Smartphone (TOTP app codes like Google Authenticator), SMS verification code, hardware token (YubiKey), smart card. |
| **Something you Are (Inherence)** | Biological or biometric characteristics unique to the user | Fingerprint scanner, facial recognition (FaceID), iris/retina scan, voiceprint. |

> **Exam Trap — False MFA:** Combining a **Password** with a **PIN** is **NOT** MFA because both belong to the exact same factor category (*"Something you Know"*).

#### Physical Security Controls
- **Kensington Cable Locks:** Physically securing laptops, desktop chassis, and monitors to immovable desks.
- **Mantrap / Air Lock:** A secure entry area with two interlocking doors where the first door must close before the second opens, preventing tailgating.
- **Clean Desk Policy:** Mandates that all sensitive documents, USB drives, and written notes must be locked away when workstations are unattended.
- **Screen Lockout (Windows + L):** Configuring operating systems to automatically lock the screen after 5–10 minutes of inactivity.

---

### 8.4 Cryptography, Encryption & Public Key Infrastructure (PKI)

```
┌─────────────────────────────────────────────────────────────┐
│                 CRYPTOGRAPHY PARADIGMS                      │
│                                                             │
│  SYMMETRIC ENCRYPTION (Fast / Bulk Data)                    │
│  Plaintext  ──▶  [ SHARED SECRET KEY ]  ──▶  Ciphertext     │
│  Ciphertext ──▶  [ SHARED SECRET KEY ]  ──▶  Plaintext      │
│  (Examples: AES-128, AES-256)                               │
│                                                             │
│  ASYMMETRIC ENCRYPTION (Public Key Infrastructure)          │
│  Plaintext  ──▶  [ RECIPIENT'S PUBLIC KEY ]  ──▶ Ciphertext │
│  Ciphertext ──▶  [ RECIPIENT'S PRIVATE KEY ] ──▶ Plaintext  │
│  (Examples: RSA, ECC, TLS Certificates)                     │
└─────────────────────────────────────────────────────────────┘
```

#### Core Cryptographic Terminology
- **Plaintext:** Original, unencrypted, human-readable data.
- **Ciphertext:** Scrambled, unreadable data generated by applying an encryption algorithm and cryptographic key.
- **Cryptographic Hashing:** A mathematical one-way function that takes arbitrary data and outputs a fixed-length string (checksum).
  - *Purpose:* Verifies data **Integrity**.
  - *Key Trait:* **One-way only** — impossible to reverse-engineer ciphertext back into original plaintext.
  - *Algorithms:* SHA-256, SHA-3, MD5 (MD5 is legacy/deprecated).

#### Symmetric vs. Asymmetric Encryption

| Feature | Symmetric Encryption | Asymmetric Encryption (PKI) |
|---------|----------------------|-----------------------------|
| **Key Count** | 1 Single Shared Secret Key | 2 Mathematically Linked Keys (Public Key + Private Key) |
| **How It Works** | The same key encrypts and decrypts. | **Public Key:** Freely shared; used by anyone to *encrypt* data.<br>**Private Key:** Kept secret; used by owner to *decrypt* data. |
| **Speed & Overhead** | Extremely fast; low CPU overhead. | Slower; higher computational complexity. |
| **Primary Use Case** | Bulk data encryption (data at rest on hard drives). | Key exchange, digital signatures, web identity verification (SSL/TLS). |
| **Leading Algorithms** | AES (128/256-bit), 3DES | RSA, ECC (Elliptic Curve Cryptography) |

#### Data States & Encryption Implementations
- **Data at Rest:** Inactive data stored on physical storage devices (hard drives, SSDs, SANs, USB flash drives).
  - *Protections:* Full Disk Encryption (FDE), BitLocker (Windows), FileVault (macOS).
- **Data in Transit (In Motion):** Data actively traveling across wired networks, Wi-Fi, or the public internet.
  - *Protections:* HTTPS / TLS (secure web), VPN / IPsec (remote network tunnel), SSH (secure console), S/MIME or PGP (encrypted email).
- **Data in Use:** Data actively residing in system RAM, CPU caches, or CPU registers during program execution.

#### Public Key Infrastructure (PKI) & Digital Certificates
- **Certificate Authority (CA):** A trusted third-party organization (e.g., Let's Encrypt, DigiCert) that verifies domain/organizational identity and signs digital certificates.
- **Digital Certificate:** An electronic credential binding an organization's public key to their verified identity (used in HTTPS websites).

---

### 8.5 Small Office / Home Office (SOHO) Wireless Security Configuration

Securing wireless networks is critical because radio frequency signals broadcast outside physical building perimeters.

```
┌─────────────────────────────────────────────────────────────┐
│                 WIRELESS ENCRYPTION EVOLUTION               │
│                                                             │
│   WEP (Obsolete)  ──▶  WPA (Obsolete)  ──▶  WPA2  ──▶  WPA3 │
│  • RC4 Flaws          • TKIP Interim       • AES      • SAE │
│  • Cracked in mins    • Deprecated         • Standard • Top │
└─────────────────────────────────────────────────────────────┘
```

#### Wireless Security Standards Comparison

| Protocol | Release | Encryption Cipher | Security Status & Characteristics |
|----------|---------|-------------------|-----------------------------------|
| **Open / None** | — | None | Zero protection; all network traffic transmitted in plaintext. Used in public hotspots. |
| **WEP** | 1997 | RC4 (64/128-bit) | **Severely Flawed & Deprecated.** Weak initialization vectors allow attackers to crack keys in under 5 minutes. |
| **WPA** | 2003 | TKIP | **Deprecated.** Transitional standard designed to patch WEP flaws; vulnerable to packet spoofing. |
| **WPA2 (802.11i)** | 2004 | **AES-CCMP** | **Current Industry Standard.** Strong encryption; requires complex passphrases to resist offline dictionary attacks. |
| **WPA3** | 2018 | **AES-GCMP / SAE** | **Latest & Most Secure Standard.** Uses Simultaneous Authentication of Equals (SAE) to neutralize offline dictionary attacks; provides individualized session encryption on open networks. |

#### SOHO Router Hardening Best Practices Checklist
1. **Change Default Admin Credentials:** Immediately change the factory username and password (`admin`/`admin` or `admin`/`password`).
2. **Change Default Network Name (SSID):** Rename the Wi-Fi network uniquely without disclosing hardware make/model, address, or personal info.
3. **Select WPA3 or WPA2-AES:** Use WPA3 (or WPA2 Personal with AES); disable WEP and WPA-TKIP entirely.
4. **Disable WPS (Wi-Fi Protected Setup):** WPS PIN feature has an architectural brute-force vulnerability allowing attackers to crack Wi-Fi keys in minutes.
5. **Enable Isolated Guest Network:** Separates untrusted visitor devices and smart IoT gadgets from the primary corporate/home LAN.
6. **Apply Regular Firmware Updates:** Patch known router vulnerabilities and vendor security advisories.
7. **Disable Remote Management:** Prevents external access to the router's web management interface from the public internet WAN side.

---

## 9. Key Terms Master Glossary

A quick-reference list of the most commonly tested terms:

| Term | Definition |
|------|------------|
| **Algorithm** | Step-by-step procedure for solving a problem |
| **API** | Application Programming Interface — lets apps talk to each other |
| **Bandwidth** | Maximum data transfer rate of a network |
| **BIOS** | Basic Input/Output System — firmware that boots the PC |
| **Boot** | Process of starting up a computer |
| **Cache** | Fast temporary storage for frequently accessed data |
| **Client** | Device or software that requests services from a server |
| **Cloud** | Delivering computing services over the internet |
| **CPU** | Central Processing Unit — processes instructions |
| **CRUD** | Create, Read, Update, Delete — core DB operations |
| **Data Center** | Facility housing servers, networking, and storage systems |
| **DHCP** | Dynamic Host Configuration Protocol — auto-assigns IP addresses |
| **DNS** | Domain Name System — translates domain names to IP addresses |
| **Encryption** | Scrambling data so only authorized parties can read it |
| **Firewall** | Security system monitoring network traffic |
| **Firmware** | Software embedded in hardware devices |
| **GUI** | Graphical User Interface — windows, icons, mouse interaction |
| **Hypervisor** | Software that creates and manages virtual machines |
| **IaaS** | Infrastructure as a Service — cloud-based servers/storage |
| **IP Address** | Numerical label identifying a device on a network |
| **ISP** | Internet Service Provider — provides internet access |
| **Kernel** | Core of an operating system — manages hardware resources |
| **LAN** | Local Area Network — network within a building |
| **Latency** | Delay in data transmission |
| **Malware** | Malicious software designed to harm a system |
| **MFA** | Multi-Factor Authentication — two or more verification steps |
| **NIC** | Network Interface Card — connects a device to a network |
| **OS** | Operating System — manages hardware and software |
| **PaaS** | Platform as a Service — cloud development environment |
| **Patch** | Software update fixing bugs or security vulnerabilities |
| **Phishing** | Fraudulent attempt to steal credentials via fake messages |
| **Primary Key** | Unique identifier for each row in a database table |
| **Protocol** | Rules governing data communication between devices |
| **RAM** | Random Access Memory — volatile short-term storage |
| **Ransomware** | Malware that encrypts files and demands a ransom |
| **Router** | Connects different networks; routes traffic |
| **SaaS** | Software as a Service — fully managed cloud applications |
| **Server** | A computer that provides resources/services to clients |
| **SQL** | Structured Query Language — used to query databases |
| **SSD** | Solid State Drive — fast, non-volatile storage |
| **Switch** | Connects devices within the same network |
| **TCP/IP** | Suite of protocols governing internet communication |
| **Throughput** | Actual data transfer rate achieved (vs. max bandwidth) |
| **URL** | Uniform Resource Locator — a web address |
| **VPN** | Virtual Private Network — encrypted internet tunnel |
| **VM** | Virtual Machine — software simulation of a computer |
| **WAN** | Wide Area Network — spans large geographic areas |
| **Wi-Fi** | Wireless networking technology (IEEE 802.11) |
| **WPA2/WPA3** | Wi-Fi security protocols using AES encryption |

---

## 10. Mnemonics & Memory Aids

### Troubleshooting Steps
**"I Eat Tacos Every Vacation Day"**
1. **I**dentify the problem
2. **E**stablish a theory
3. **T**est the theory
4. **E**stablish a plan & implement
5. **V**erify functionality
6. **D**ocument everything

### CIA Triad
**"Can I Anticipate?"**
- **C**onfidentiality
- **I**ntegrity
- **A**vailability

### Number System Bases
**"Big Dogs Often Hate"**
- **B**inary = Base **2**
- **D**ecimal = Base **10**
- **O**ctal = Base **8**
- **H**exadecimal = Base **16**

### Cloud Service Models (bottom to top)
**"I Passed the SAT"**
- **I**aaS → most control for user
- **P**aaS → middle ground
- **S**aaS → least control; fully managed

### MFA Factors
**"Know, Have, Are"**
- Something you **Know** (password)
- Something you **Have** (phone/token)
- Something you **Are** (biometrics)

### Backup Types
**"Full = Fat, Incremental = Infrequent space, Differential = Decent balance"**
- **Full:** copies everything (most space)
- **Incremental:** only changes since last backup (least space, slowest restore)
- **Differential:** changes since last full backup (medium)

### CRUD
**"Can Robots Unpack Dishes?"**
- **C**reate → INSERT
- **R**ead → SELECT
- **U**pdate → UPDATE
- **D**elete → DELETE

---

## 11. Practice Question Strategies

### How to Approach Multiple-Choice Questions

1. **Read the full question** before looking at the answers
2. **Identify key words:** "BEST," "FIRST," "MOST likely," "EXCEPT"
3. **Eliminate obviously wrong answers** (usually 1–2 are clearly off)
4. **Watch for absolutes:** words like "always," "never," "only" are often wrong
5. **If two answers seem correct**, look for the one that is *most complete* or *most relevant*
6. **Scenario questions:** always identify *what problem is being described* before answering

### Common Question Traps

| Trap | What to Watch For |
|------|-------------------|
| **Almost-right answers** | Two answers are similar; one has a subtle wrong detail |
| **Out-of-order steps** | Troubleshooting steps in the wrong order |
| **Confusing Mb vs. MB** | Megabits vs. Megabytes (context clues: storage = Bytes, speed = bits) |
| **IaaS vs. PaaS vs. SaaS** | Who manages what in each model |
| **Correlation vs. Causation** | "What caused X?" vs. "What happened after X?" |
| **Best practice vs. any practice** | The "BEST" answer may not be the only valid one |

### Sample Practice Questions

**Q1:** A user reports their computer is running slowly after visiting a website. What is the FIRST step a technician should take?
- A) Reboot the computer
- B) Identify and document the problem symptoms
- C) Install antivirus software
- D) Restore from backup

> **Correct: B** — The first step in troubleshooting is always to identify the problem.

---

**Q2:** Which number system uses digits 0–9 and letters A–F?
- A) Binary
- B) Octal
- C) Decimal
- D) Hexadecimal

> **Correct: D** — Hexadecimal is base-16 and uses 0–9 plus A–F.

---

**Q3:** A company stores its applications on a third-party provider's servers and pays monthly. Employees access the apps through a web browser. What cloud model is this?
- A) IaaS
- B) PaaS
- C) SaaS
- D) Private Cloud

> **Correct: C** — SaaS delivers full applications over the internet on a subscription basis.

---

**Q4:** Which authentication method provides the HIGHEST level of security?
- A) Password only
- B) PIN only
- C) Password + fingerprint
- D) Security questions only

> **Correct: C** — Combining something you "know" (password) + something you "are" (fingerprint) = MFA = most secure.

---

**Q5:** Which backup method copies ONLY the data that has changed since the last backup of ANY type?
- A) Full backup
- B) Differential backup
- C) Incremental backup
- D) Mirror backup

> **Correct: C** — Incremental backups copy only changes since the last backup (of any kind).

---

## 12. Exam Day Checklist

### Night Before the Exam
- [ ] Review your personal notes and flashcards (light review — no cramming)
- [ ] Do 20–30 practice questions to build confidence
- [ ] Prepare your ID (government-issued photo ID required for Pearson VUE)
- [ ] If online proctored: test your system at home.pearsonvue.com
- [ ] Get a good night's sleep (7–8 hours minimum)
- [ ] Avoid alcohol; eat a balanced meal
- [ ] Set 2 alarms if your test is in the morning

### Morning of the Exam
- [ ] Eat a proper meal (brain needs fuel)
- [ ] Avoid excess caffeine (causes jitteriness and anxiety)
- [ ] Arrive 30 minutes early if in-person
- [ ] Bring: valid photo ID + exam voucher/confirmation
- [ ] Leave phone in your car or locker (not allowed in testing room)

### During the Exam
- [ ] Read every question fully before looking at answers
- [ ] Flag difficult questions and come back to them
- [ ] Pace yourself: ~50 seconds per question
- [ ] Don't leave any question blank — there's no penalty for guessing
- [ ] Review flagged questions if time allows
- [ ] Trust your preparation — go with your first instinct unless you find a clear reason to change

### After the Exam
- [ ] You'll receive your score immediately on screen at Pearson VUE
- [ ] If you pass: your certificate will be emailed within a few days
- [ ] If you don't pass: review your score report to identify weak domains, wait the required time, and rebook
- [ ] Celebrate if you pass!

---

## 13. Resources & Tools

### Official CompTIA Resources
| Resource | What It Is | Cost |
|----------|-----------|------|
| **Exam Objectives PDF** | Official topic list — your study bible | Free |
| **CertMaster Learn** | Interactive eLearning + practice | Paid |
| **CertMaster Practice** | Adaptive practice test engine | Paid |
| **CertMaster Labs** | Hands-on virtual lab environment | Paid |
| **CompTIA Study Guide** | Official textbook | Paid (~$30–50) |

### Free Resources
| Resource | Type | Notes |
|----------|------|-------|
| **Professor Messer (professormesser.com)** | Video + notes | Free FC0-U71 course; very popular |
| **YouTube — "FC0-U71"** | Video | Search this exact code for current content |
| **r/CompTIA (Reddit)** | Community | Exam tips, AMA threads, pass stories |
| **Quizlet** | Flashcards | Search "CompTIA Tech+ FC0-U71" |
| **ExamCompass.com** | Practice tests | Free practice quizzes |

### Paid Resources (Best Value)
| Resource | Platform | Notes |
|----------|----------|-------|
| **CompTIA Tech+ Course** | Udemy | Buy during sales (~$12–15) |
| **FC0-U71 Learning Path** | Pluralsight | Monthly subscription |
| **Tech+ Course** | Coursera | Some free to audit |

### Study Tools
| Tool | Purpose |
|------|---------|
| **Anki** | Spaced repetition flashcard app (free) |
| **Notion / OneNote** | Note organization and review |
| **Timer (Pomodoro)** | 25 min study / 5 min break cycles |
| **Google Sheets** | Track practice test scores by domain |

---

## 14. Progress Tracker

Use this section to track your readiness before the exam.

### Domain Mastery Self-Assessment

Rate yourself 1–5 on each domain after studying:
*(1 = Need major review | 3 = Getting there | 5 = Ready)*

| Domain | Weight | Self-Rating (1–5) | Last Reviewed | Notes |
|--------|--------|-------------------|---------------|-------|
| IT Concepts & Terminology | 26% | | | |
| Infrastructure | 18% | | | |
| Applications & Software | 14% | | | |
| Software Development Concepts | 10% | | | |
| Database Fundamentals | 13% | | | |
| Security | 19% | | | |

### Practice Test Score Log

| Date | Test Source | Score (%) | Weakest Domain | Notes |
|------|------------|-----------|----------------|-------|
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |

> **Target:** Consistently scoring **75%+** on practice tests before booking the real exam.

### Study Hours Log

| Week | Hours Studied | Topics Covered |
|------|--------------|----------------|
| Week 1 | | |
| Week 2 | | |
| Week 3 | | |
| Week 4 | | |
| Total | | |

---

## Final Advice

> **1. Know the 6-step troubleshooting process cold.** It appears in multiple questions across domains.
>
> **2. Understand *why*, not just *what*.** CompTIA's scenario questions test applied thinking.
>
> **3. Focus on Domains 1 and 6.** Together they are 45% of the exam — they make or break your score.
>
> **4. Practice tests are not optional.** They're the #1 predictor of exam success.
>
> **5. Don't use brain dumps.** You'll fail when scenarios are worded differently. Understand concepts.
>
> **6. Book the exam when you're consistently scoring 75%+.** Scheduling creates accountability.

---

*Created: August 2025 | CompTIA Tech+ Exam Code: FC0-U71 | Passing Score: 650/900*
