## GRC Policies & Risk

This project demonstrates core Governance, Risk, and Compliance (GRC) skills used across cybersecurity programs.
It includes security policies, risk matrices, governance documentation, and framework mapping to standards such as NIST CSF, NIST 800-53, ISO27001, and PCI-DSS.

## 🎯 Objectives

- Create enterprise-grade security policies
- Perform qualitative & semi-quantitative risk analysis
- Build a standardized risk matrix
- Document governance requirements
- Map controls to industry frameworks

## 📁 What’s Inside
docs/       - Policies, risk matrix, templates, framework mappings
lab/        - Optional evidence: screenshots, findings, posture data
scripts/    - Optional automation (policy checks, CSV handling)
.github/    - Issue/PR templates

## 📜 Security Policies Included

This repo includes (or will include) several foundational security policies:

- Acceptable Use Policy (AUP)
- Access Control Policy
- Incident Response Policy
- Change Management Policy
- Vulnerability Management Policy
- Logging & Monitoring Policy
- Backup & Recovery Policy


Each policy follows a professional structure:
- Purpose
- Scope
- Roles & responsibilities
- Requirements
- Enforcement
- Definitions (optional)
- Versioning

## 📊 Risk Management

This repo includes:


- Risk Matrix (Likelihood × Impact)
- Heat map representation
- Risk scoring methodology
- Controls mapped to risks
- Recommendations section

You populate the Risk_Matrix_TEMPLATE.csv with actual risks from:

- network scans
- cloud configurations
- identity misconfigurations
- policy gaps
- general security scenarios

This gives you real GRC practice.

## 🧪 Lab Setup (Optional)
Most GRC work is documentation-based, but this repo may reference:

- screenshots from Azure Secure Score
- evidence from vulnerability scans
- OS hardening gaps
- audit logs showing misconfigurations

You can include these in /lab/ to support risk scoring or control justification.

## ▶️ How to Use This Repo
**1. Fill out the Risk Matrix**

Use realistic organizational risks such as:
- Weak password policies
- Open RDP to the internet
- Missing MFA
- Vulnerable software
- No logging or monitoring
- Lack of backups

Score each one on:

- Likelihood
- Impact
- Risk rating
- Assigned controls

**2. Write or refine security policies**

Each policy should include:
- Purpose
- Scope
- Responsibilities
- Requirements
- Enforcement
- Version control

Use the templates inside docs/.

**3. Map policies to frameworks**

Optional but extremely impressive to recruiters:

- NIST CSF
- NIST 800-53
- ISO27001 Annex A
- PCI-DSS
- CIS Controls

## 📊 Deliverables
✅ Security policies

✅ Completed risk matrix

✅ Control mapping

✅ Governance documentation

✅ Optional audit evidence

✅ Optional diagrams

## 🧠 What I Learned
- How risk is calculated using qualitative & semi-quantitative scoring
- How policies support technical and administrative controls
- The structure of real-world security documentation
- Why governance is foundational to cybersecurity maturity
- How compliance frameworks overlap and differ
- How to translate technical vulnerabilities into business risk

## ✅ Next Steps
- Add more detailed policies (e.g., Data Classification, Mobile Device Security)
- Build a full risk register
- Map your own Vuln Management repo findings into this risk matrix
- Create a small compliance checklist for NIST CSF
- Add “audit evidence” examples in the lab folder
- Add a Policy Exception Request form (very realistic enterprise artifact)

## ⚖️ License
MIT – see `LICENSE`.
