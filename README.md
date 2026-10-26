# Anthony DeAngelis

**Cloud Security | Identity & Access Management | Security Automation**

I am a Network Operations / Security Operations Intern at **Willkie Farr & Gallagher LLP** and an Information Technology student at **St. Francis College**, graduating in **May 2027**. My work spans Windows Server and Active Directory administration, PowerShell automation, SIEM investigations, phishing analysis, and vulnerability remediation.

I build hands-on labs that connect infrastructure, identity, and detection: deploy the environment, control access, collect telemetry, test the behavior, and document the results. My current focus is Azure security, Microsoft Entra ID, and automation with Python, PowerShell, Terraform, and GitHub Actions.

## Featured projects

### [Azure NSG Security Automation](https://github.com/Anthonydeangelis/azure-nsg-security-automation)
**Python · Azure Functions · Terraform · Microsoft Sentinel · Managed Identity**

- Built a Python SDK workflow that inspects NSG rules for unrestricted-source inbound SSH, saves current findings in Table Storage, and sends structured detection events through a Data Collection Rule to Sentinel.
- Connected configuration-change alerts to a Logic App with a 30-minute grace period; verified an ingested finding and Sentinel incident in a controlled test. Added a private findings dashboard with Azure tokens kept on the VM backend.

### [Entra ID & Azure Automation](https://github.com/Anthonydeangelis/Entra-PowerShell-Automation-Project)
**PowerShell · Microsoft Graph · Azure Automation · Key Vault · GitHub Actions OIDC**

- Automated CSV-based Entra user provisioning and department security-group membership. Recorded results show **25 lab users created, six department groups populated, and 26 direct user memberships verified**, including my existing account.
- Used a runbook managed identity for Graph, Blob Storage, and Key Vault access; deployed runbooks through GitHub Actions with OIDC and explicit PowerShell runtime selection.

### [Azure Infrastructure & Security Lab](https://github.com/Anthonydeangelis/Azure-Infra-Security-Lab)
**Terraform · Ansible · Azure Monitor · KQL · Microsoft Sentinel · Logic Apps**

- Provisioned **five Ubuntu VMs across two peered VNets**, configured Nginx and Unbound DNS, and verified private workload access and web-tier network restrictions.
- Built detections for NSG changes, repeated invalid-user SSH activity, and a controlled DNS reputation scenario enriched with VirusTotal. Verified alert-backed incidents and automatic email notifications for all three.
- Implemented GitHub Actions deployment with OIDC, remote Terraform state, and a reviewed, manually triggered saved-plan apply workflow.

### [Hybrid Identity & Security Homelab](https://github.com/Anthonydeangelis/hybridhomelab)
**Proxmox · Active Directory · Entra Connect · Application Proxy · Conditional Access · Wazuh**

- Built a private Windows/Linux environment with scoped AD-to-Entra synchronization, group-based SMB permissions, and an internal Nginx application published through Entra Application Proxy with MFA.
- Centralized telemetry from **five Wazuh agents** and tested detections for AD account/group changes, Entra Connect service interruptions, repeated SMB authentication failures, and sudo activity.

Each featured repository includes implementation notes, screenshots or verification output, troubleshooting, and scope limitations. These are learning environments with controlled lab tests.

## Technical skills

| Area | Tools and experience |
| --- | --- |
| Cloud & infrastructure | Azure, Terraform, Ansible, GitHub Actions, VNets, peering, NSGs, DNS, Windows Server, Linux, Proxmox |
| Identity & access | Active Directory, Microsoft Entra ID, Entra Connect, Application Proxy, Conditional Access, MFA, Microsoft Graph, Azure RBAC, managed identities |
| Security operations | IBM QRadar, CrowdStrike Falcon Next-Gen SIEM, Microsoft Sentinel, Wazuh, Proofpoint, Abnormal AI, Mimecast, Zscaler, Qualys |
| Automation & workflow | PowerShell, Python, Bash, KQL, Logic Apps, Azure Automation, Zendesk, ServiceNow |

## Certifications

- Microsoft Certified: Azure Administrator Associate (AZ-104)
- Microsoft Certified: Identity and Access Administrator Associate (SC-300)
- Microsoft Certified: Azure Fundamentals (AZ-900)
- CompTIA Security+
- CompTIA Network+

## Connect

[LinkedIn](https://www.linkedin.com/in/anthony-deangelis/) · [Email](mailto:antdeangelis2@gmail.com)
