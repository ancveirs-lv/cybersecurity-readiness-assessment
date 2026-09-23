# Cybersecurity Readiness Self-Assessment

> This assessment is a readiness and evidence-gap instrument. It is not a compliance determination, certification, audit or substitute for sector-specific requirements.

## Response states

- `UNKNOWN` — Unknown / not evidenced
- `CLAIMED` — Claimed
- `DOCUMENTED` — Documented
- `IMPLEMENTED` — Implemented
- `VERIFIED` — Verified

## Assessment

### Govern

#### C01

Cybersecurity objectives are linked to business mission, critical services and stakeholder needs.

**Recommended action:** Document the outcomes cybersecurity must protect and who depends on them.

**Sources:** `nist_csf20`

#### C02

Cybersecurity roles, decision rights and risk ownership are explicit.

**Recommended action:** Assign accountable owners and define who may accept material cyber risk.

**Sources:** `nist_csf20`, `nis2`

#### C03

Leadership defines or approves cybersecurity risk tolerance and priorities.

**Recommended action:** Record risk tolerance and use it to resolve competing decisions.

**Sources:** `nist_csf20`, `nis2`

#### C04

Material cybersecurity policies are implemented, reviewed and tied to accountable owners.

**Recommended action:** For each policy identify owner, implementation evidence and review date.

**Sources:** `nist_csf20`

#### C05

Supplier and regulatory cyber obligations are identified and assigned to controls and owners.

**Recommended action:** Create an obligation and supplier-risk map linked to owners and evidence.

**Sources:** `nist_csf20`, `nis2`, `enisa_sme_maturity`

### Identify

#### C06

The organisation maintains an inventory of systems, services, devices and significant software dependencies.

**Recommended action:** Build a minimum viable inventory and identify assets supporting critical services.

**Sources:** `nist_csf20`

#### C07

Critical data and its locations, owners and sensitivity are known.

**Recommended action:** Identify critical data sets, owners, locations and handling requirements.

**Sources:** `nist_csf20`

#### C08

External dependencies and single points of failure are identified for critical services.

**Recommended action:** Map critical third parties, connectivity and platform dependencies to services.

**Sources:** `nist_csf20`, `nis2`

#### C09

Vulnerabilities and insecure configurations are discovered through defined processes.

**Recommended action:** Define how weaknesses are found, recorded and assigned.

**Sources:** `nist_csf20`, `enisa_sme_maturity`

#### C10

Cyber risks are recorded with business impact, assumptions, owners and treatment decisions.

**Recommended action:** Use a risk register that distinguishes evidence, assumptions and treatment status.

**Sources:** `nist_csf20`

### Protect

#### C11

Access to important systems follows least privilege and strong authentication.

**Recommended action:** Review privileged and remote access first; remove unnecessary rights.

**Sources:** `nist_csf20`, `nis2`

#### C12

Security updates and configuration baselines are managed for supported systems.

**Recommended action:** Define patch and configuration expectations by criticality and track exceptions.

**Sources:** `nist_csf20`, `nis2`

#### C13

Backups are protected from the same failure or compromise as production systems.

**Recommended action:** Separate critical backups and test them after a realistic compromise scenario.

**Sources:** `nist_csf20`

#### C14

Personnel receive role-appropriate cybersecurity guidance and training.

**Recommended action:** Prioritise high-risk roles and tie training to real workflows.

**Sources:** `nist_csf20`, `nis2`

#### C15

Sensitive data is protected in storage, transfer and disposal according to risk.

**Recommended action:** Define minimum protection rules and verify implementation.

**Sources:** `nist_csf20`

### Detect

#### C16

Security-relevant logs exist for critical systems and are retained long enough to investigate incidents.

**Recommended action:** Identify the minimum logs needed to detect and reconstruct high-impact incidents.

**Sources:** `nist_csf20`

#### C17

Monitoring has defined owners, alert routes and response expectations.

**Recommended action:** Define receiver, response time and escalation for critical alert sources.

**Sources:** `nist_csf20`

#### C18

The organisation can recognise meaningful anomalies in critical services and identities.

**Recommended action:** Define high-value abnormal conditions and confirm they are detectable.

**Sources:** `nist_csf20`

#### C19

Detection includes material third-party and cloud signals where the organisation depends on them.

**Recommended action:** Identify supplier and cloud signals that must reach incident response.

**Sources:** `nist_csf20`, `nis2`

#### C20

Detection coverage is tested with realistic scenarios rather than assumed from tool deployment.

**Recommended action:** Run controlled detection tests and record expected versus observed alerts.

**Sources:** `nist_csf20`

### Respond

#### C21

A usable incident-response plan defines roles, authority and escalation paths.

**Recommended action:** Build the plan around real decision rights and contact paths.

**Sources:** `nist_csf20`, `nis2`

#### C22

Internal, customer, supplier and regulatory communication responsibilities are defined before an incident.

**Recommended action:** Predefine communication owners, approval routes and required information.

**Sources:** `nist_csf20`, `nis2`

#### C23

The organisation can contain affected accounts, devices or services without improvising basic access.

**Recommended action:** Prepare and test containment actions for plausible high-impact incidents.

**Sources:** `nist_csf20`

#### C24

Incident evidence is preserved sufficiently for investigation, learning and required reporting.

**Recommended action:** Define minimum evidence-preservation steps before an incident occurs.

**Sources:** `nist_csf20`, `nis2`

#### C25

Exercises test real people, decisions and dependencies, not only the existence of a plan.

**Recommended action:** Run a scenario forcing escalation, containment, communication and supplier coordination.

**Sources:** `nist_csf20`

### Recover

#### C26

Critical systems and data have tested recovery procedures.

**Recommended action:** Perform and retain evidence from an end-to-end recovery test.

**Sources:** `nist_csf20`

#### C27

Recovery priorities and time/data-loss objectives are defined from business needs.

**Recommended action:** Agree service recovery order and tolerable time/data loss with business owners.

**Sources:** `nist_csf20`

#### C28

Critical processes have a defined degraded or alternative operating mode.

**Recommended action:** Define the minimum viable service when normal systems are unavailable.

**Sources:** `nist_csf20`

#### C29

Recovery plans account for critical suppliers and external dependencies.

**Recommended action:** Test recovery when a critical supplier is unavailable or compromised.

**Sources:** `nist_csf20`, `nis2`

#### C30

Post-incident lessons produce owned improvements that are later verified.

**Recommended action:** Track lessons to owners, due dates and verification evidence.

**Sources:** `nist_csf20`, `enisa_sme_maturity`
