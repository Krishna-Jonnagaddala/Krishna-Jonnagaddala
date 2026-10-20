<p><samp>krishna@security:~$ whoami</samp></p>

<h1><samp>Krishna Jonnagaddala_</samp></h1>

<p><samp>SOC L2 ANALYST &nbsp; / &nbsp; SECURITY RESEARCHER &nbsp; / &nbsp; LONDON, UK</samp></p>

```diff
+ Investigating threats across endpoints, identities and networks.
+ Authorised bug bounty research outside the SOC.
+ Developing my skills in AI application and agent security.
```

[ `./operations` ](#operations) &nbsp; [ `./toolkit` ](#toolkit) &nbsp; [ `./research` ](#research) &nbsp; [ `./credentials` ](#credentials) &nbsp; [ `./bounty` ](#bounty) &nbsp; [ `./contact` ](#contact)

---

<a id="operations"></a>

### `$ cat operations.md`

I work with **Microsoft Sentinel, Defender XDR and KQL** to investigate phishing, malware, suspicious sign-ins and unauthorised access.

Most of my work is following the evidence: correlating logs, checking process activity, validating IOCs and working out which users or systems are affected. I document what I find, recommend response actions and feed the findings back into detections.

`alert triage` `incident scoping` `threat hunting` `detection tuning` `MITRE ATT&CK`

<details>
<summary><samp>+ background / before the SOC</samp></summary>

I previously provided L1/L2 IT support to **150+ users** across Windows, Active Directory, Microsoft 365, VPN and enterprise applications. Troubleshooting those systems gave me a useful starting point for investigating their security logs.

</details>

<a id="toolkit"></a>

### `$ cat toolkit.yml`

```yaml
detection:
  platforms: [Microsoft Sentinel, Splunk]
  queries:   [KQL, SPL]

endpoint_and_identity:
  platforms: [Microsoft Defender XDR, Entra ID, Active Directory]
  telemetry: [Device timelines, Process activity, Sign-in logs]

investigation:
  methods:   [Log correlation, IOC validation, Threat hunting]
  context:   [MITRE ATT&CK, Threat intelligence]

systems:
  platforms: [Windows, Linux, Microsoft 365]
  network:   [TCP/IP, DNS, DHCP, VPN, Firewall logs]

scripting:
  languages: [Python, PowerShell]
  workflow:  [Git, ServiceNow, Jira Service Management]
```

<a id="research"></a>

### `$ cat research/README.md`

I'm interested in what happens when AI applications can read documents, retrieve data and call tools. The security questions I'm working through:

- **Prompt injection** — can untrusted content change an agent's behaviour?
- **RAG security** — what happens when retrieved content is poisoned or exposes data?
- **Agent permissions** — does a tool call stay within the user's authority?
- **AI in the SOC** — can an assistant explain its findings with evidence an analyst can check?

**Next on my workbench:** an AI security assessment around EVOPT, repeatable detection tests and an analyst-reviewed SOC automation workflow.

[ `ls -la repositories/` →](https://github.com/Krishna-Jonnagaddala?tab=repositories)

<a id="credentials"></a>

### `$ cat credentials.txt`

`SC-200` &nbsp; `Security+` &nbsp; `BTL1` &nbsp; `C|CT` &nbsp; `Google Cybersecurity` &nbsp; `AI1` &nbsp; `SEC1`

<details>
<summary><samp>+ expand / certificates and issuers</samp></summary>

- **Microsoft Certified: Security Operations Analyst Associate (SC-200)** — Microsoft
- **CompTIA Security+ (SY0-701)** — CompTIA
- **Blue Team Level 1 (BTL1)** — Centri
- **Certified Cybersecurity Technician (C|CT)** — EC-Council
- **Google Cybersecurity Professional Certificate** — Google
- **AI Security (AI1) Certificate** — TryHackMe
- **Cyber Security 101 (SEC1) Certificate** — TryHackMe

</details>

<a id="bounty"></a>

### `$ cat bounty/profiles.conf`

I spend time outside work doing bug bounty research within programme scope.

[![Intigriti](https://img.shields.io/badge/INTIGRITI-181C18?style=for-the-badge&logo=intigriti&logoColor=8CEB75)](https://app.intigriti.com/researcher/profile/krishna_jonnagaddala)
[![HackerOne](https://img.shields.io/badge/HACKERONE-181C18?style=for-the-badge&logo=hackerone&logoColor=8CEB75)](https://hackerone.com/krishnajonnagaddala?type=user)
[![Bugcrowd](https://img.shields.io/badge/BUGCROWD-181C18?style=for-the-badge&logo=bugcrowd&logoColor=8CEB75)](https://bugcrowd.com/h/krishna_jonnagaddala)

<a id="contact"></a>

### `$ cat contact.txt`

Open to conversations about **security operations, detection engineering and AI security**.

[ `LinkedIn` ](https://www.linkedin.com/in/krishna-jonnagaddala-2b858119a/) &nbsp; / &nbsp; [ `kp.jonnagaddala@gmail.com` ](mailto:kp.jonnagaddala@gmail.com)

---

<samp>krishna@security:~$ <b>▍</b></samp>
