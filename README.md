<h1 align="center">Danielle Respes</h1>
<p align="center">
<strong>Senior Endpoint Technician &nbsp;|&nbsp; Threat Hunting &nbsp;|&nbsp; Detection Engineering &nbsp;|&nbsp; Incident Response</strong>
</p>
<p align="center">
<a href="https://www.linkedin.com/in/danielle-respes-64113767/">LinkedIn</a> &nbsp;|&nbsp;
<strong>   CompTIA Security+ (expected November 2026)</strong> &nbsp;|&nbsp;
<strong>   U.S. Citizen · Security Clearance Eligible</strong>
</p>

---

**Cyber Range Internship:** LOG(N) Pacific | **Tools:** Sentinel · KQL · Defender XDR · Tenable · MITRE ATT&CK · NIST

---

I'm a Senior Endpoint Technician at Council Rock School District (8,000+ users) transitioning into threat detection and incident response. I'm interning at LOG(N) Pacific on detection engineering and vulnerability management — self-funded and self-directed. Learning by doing real investigations, writing detection and hunting queries, and documenting my methodology so my work is transparent and reproducible.

---

## Current Threat Hunts

| Investigation | Focus | Status |
|---|---|---|
| [Threat Hunt: EchoLeak (Oct 2026)](https://github.com/Danielle-Respes/Threat-Hunt-EchoLeak-Copilot-Prompt-Injection-Sentinel-KQL-Oct-2026) | Investigated how hidden instructions in an email attachment hijacked Microsoft 365 Copilot (CVE-2025-32711), leading to 13 confidential files being accessed and leaked through image links. Used Sentinel and KQL across Office, Copilot and Entra logs. | Completed |

---


## Professional Focus

I remain deeply curious and engaged in my day-to-day Help Desk and endpoint role. I continuously expand my original scope of work by taking ownership of security triage, Advanced Hunting with KQL, automated SOAR playbook correlation, and cross-team containment efforts. These real-world investigations bridge frontline IT operations with proactive cybersecurity, deliberately building the practical foundation for my next position in threat detection and incident response.

## October 2026 Incident Triage Tracker

<table width="100%">
  <thead>
    <tr style="background-color: #14532d; color: white;">
      <th style="background-color: #14532d; color: white; padding: 12px; text-align: left; font-weight: bold; border-top-left-radius: 6px;">Security Platform / Tool</th>
      <th style="background-color: #14532d; color: white; padding: 12px; text-align: left; font-weight: bold;">Operational Focus & Investigation Summary</th>
      <th style="background-color: #14532d; color: white; padding: 12px; text-align: left; font-weight: bold; border-top-right-radius: 6px;">Advanced KQL & Telemetry Analysis</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 12px; vertical-align: top;"><strong>Microsoft Defender for Endpoint</strong></td>
      <td style="padding: 12px; vertical-align: top;"><strong>Endpoint Malware Containment:</strong> Investigated behavioral alerts (<code>SuspMasqueradedRenPyExe</code>), coordinated workstation isolation with IT leadership, arranged clean base image reimaging, and performed user communication and credential resets with a high-empathy approach.</td>
      <td style="padding: 12px; vertical-align: top;">• Inspected raw device process telemetry (<code>DeviceProcessEvents</code>, <code>DeviceFileEvents</code>) to trace unauthorized script execution paths and command-line flags.<br><br>• Verified file drop locations in user-space directories to confirm isolation boundaries.</td>
    </tr>
    <tr>
      <td style="padding: 12px; vertical-align: top;"><strong>Adlumin / Entra ID / Windows SOAR</strong></td>
      <td style="padding: 12px; vertical-align: top;"><strong>Cloud Identity & SOAR Automation:</strong> Managed high-severity M365 risky sign-ins (password spray patterns under MITRE <code>T1110.003</code> / <code>T1110.001</code>), tracked automated <code>domain_account/disable</code> playbooks executing across regional domain controllers, and guided users through Classlink recovery and AD sync windows (~1 hour).</td>
      <td style="padding: 12px; vertical-align: top;">• <strong>Entra ID Log Analysis:</strong> Traced authentication error code sequences (<code>ErrorCode 50140</code> and <code>ErrorCode 399218</code>) to establish user behavior patterns.<br><br>• <strong>Tenant-Wide Scoping:</strong> Executed scoping checks (<code>UniqueUsers = 1</code>) to rule out broad brute-force campaigns and confirm single-target impact.<br><br>• <strong>SOAR Correlation:</strong> Mapped automated playbook execution timestamps against identity risk scoring.</td>
    </tr>
    <tr>
      <td style="padding: 12px; vertical-align: top;"><strong>Microsoft Defender for Endpoint & KQL</strong></td>
      <td style="padding: 12px; vertical-align: top;"><strong>False Positive Validation:</strong> Differentiated genuine credential threats from legitimate Chromium browser profile migrations (<code>--utility-sub-type=chrome.mojom.ProfileImport</code>) using targeted KQL log queries on lab workstation assets.</td>
      <td style="padding: 12px; vertical-align: top;">• Ran targeted Advanced Hunting queries against <code>DeviceProcessEvents</code> to isolate installer command-line flags, confirming benign profile migration behavior without user disruption.</td>
    </tr>
  </tbody>
</table>

---

## Completed Investigations

| Project | Description | Tools |
|---|---|---|
| [Hidden Directive DFIR](https://github.com/Danielle-Respes/Hidden-Directive-Threat-Hunt-Investigation-Sentinel-MDE-2026) | 12-phase incident reconstruction — Greenfield Logistics intrusion. Sentinel + Defender XDR telemetry. Full incident report with evidence citations. Completed August 2026. | Sentinel · Defender XDR · KQL |
| [Northpeak Descent](https://github.com/Danielle-Respes/Northpeak-Descent-Cross-Platform-Intrusion-Sentinel-KQL-2026) | Cross-platform intrusion reconstruction across Windows and Linux. Initial theory was wrong — worked it from evidence instead. Traced from quiet login through pivots to attacker workstation. | Sentinel · Defender XDR · KQL |
| [Vulnerability Management Program](https://github.com/Danielle-Respes/Vulnerability-Management) | Full program lifecycle: policy drafting, authenticated Tenable scans, CVSS prioritization, 4 remediation rounds, Change Advisory Board presentation. | Tenable · Azure VMs · NIST |
---



## Area of Focus

**Detection Engineering:** Building KQL hunting queries and Sentinel detections for MITRE ATT&CK techniques. Full cycle: research → query → test → deploy → analyst playbook. Part of LOG(N) Pacific internship.

**Threat Hunting:**     Lateral movement detection (practicing about 3 hunts per month through the LOG(N) Pacific internship)

---

## Technical Stack

**SIEM / XDR:** Microsoft Sentinel · Defender for Endpoint · Defender XDR

**Detection & Hunting:** KQL · Advanced Hunting · Tenable Nessus · CVSS

**Identity & Access:**  Entra ID (formerly Azure AD) · MFA · Conditional Access · Microsoft 365 · Intune

**Frameworks:** NIST CSF · NIST 800-53 · NIST 800-61 · MITRE ATT&CK

**Scripting:** PowerShell · KQL

**Security Operations:** Incident response · Log analysis · Artifact analysis 

---

## Education & Certifications

**In Progress:**    CompTIA Security+ (expected November 2026)

**Coursework:** MD-102 (Endpoint Administrator) · AZ-104 (Azure Administrator)

**Clearance:** U.S. Citizen · Ability to Obtain Security Clearance
