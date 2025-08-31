# STIG – Outlook Security Update (April 2024) (Plugin ID: 193266)

## Before
- **Finding:** Microsoft Outlook is missing the April 2024 security update.  
- **Risk:** Spoofing vulnerability – attackers can send specially crafted emails that leak Net-NTLMv2 hashes, enabling relay attacks.  
- **Evidence:**  

![Before – Tenable Finding](before-tenable-finding.png)  
![Before – Outlook Details](before-outlook-details.png)  

---

## Remediation
- Apply the missing Outlook April 2024 security update.  
- **Steps:**  
  1. Run **Windows Update** and install pending security patches.  
  2. Alternatively, download and install the update manually from Microsoft Update Catalog.  
- **Verification:** Confirm Outlook version is at or above **1.2023.0322.0100**.  

---

## After Remediation
(Placeholder – will add screenshot once fixed and rescanned)  

- Confirm Tenable no longer reports Plugin ID 193266.  
- **Proof to be added:**  

![After – Outlook Details Placeholder](after-outlook-details.png)  
![After – Tenable Rescan Placeholder](after-tenable-rescan.png)  



