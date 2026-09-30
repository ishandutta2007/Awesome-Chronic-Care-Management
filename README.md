# Awesome-Chronic-Care-Management

## Top Chronic Care Management (CCM) Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Medicare CCM Programs, Care Coordination, Monthly Outreach, Care Plans, RPM Integration & Value-Based Care*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Chronic Care Management (CCM)**. These systems help practices and health systems enroll eligible patients, document care plans, track monthly non-face-to-face time, coordinate outreach, and support billing for chronic care management programs (often alongside RPM and related codes).



**Examples** include WellSky, CareHarmony, ChartSpan, ThoroughCare, Prevounce, TimeDoc Health, CoachCare, Signallamp Health, Optimize Health, and Health Recovery Solutions (the category leaders).



**Open-source emphasis**: Production CCM is almost entirely commercial due to billing compliance, EHR integration, and clinical workflow requirements. Open foundations exist via **FHIR-based chronic care / eCare planning projects** and broader open health platforms. This section expands those while remaining realistic about the commercial gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[WellSky](https://wellsky.com/)**  

  Broad care management and home health platform with chronic care and coordination capabilities for post-acute and related settings.



- **[CareHarmony](https://www.careharmony.com/)**  

  Chronic care management and care coordination services/platform focused on improving outcomes for patients with multiple chronic conditions.



- **[ChartSpan](https://www.chartspan.com/)**  

  Leading full-service / turnkey CCM provider handling enrollment, outreach, documentation, and billing-ready workflows for practices.



- **[ThoroughCare](https://www.thoroughcare.net/)**  

  Software platform with guided workflows across CCM, RPM, TCM, BHI, and related programs, emphasizing care-plan and coordination depth.



- **[Prevounce](https://www.prevounce.com/)**  

  Compliance-oriented CCM and RPM platform supporting enrollment, time tracking, documentation, and billing workflows.



- **[TimeDoc Health](https://www.timedochealth.com/)**  

  Chronic care management platform and services focused on scalable CCM delivery for primary care and specialty practices.



- **[CoachCare](https://www.coachcare.com/)**  

  Remote patient monitoring and chronic care management platform combining devices, software, and care workflows.



- **[Signallamp Health](https://www.signallamphealth.com/)**  

  Care management platform supporting CCM and related value-based care programs with clinical and operational tooling.



- **[Optimize Health](https://www.optimize.health/)**  

  RPM- and CCM-oriented platform often used by practices combining remote monitoring with chronic care management.



- **[Health Recovery Solutions](https://www.healthrecoverysolutions.com/)**  

  Remote care and chronic condition management solutions spanning telehealth, RPM, and related care coordination.



## Open-Source GitHub Projects

- **[Chronic Care / MCC eCare Plan projects](https://github.com/chronic-care)**  

  Open FHIR-based chronic care and multiple chronic conditions (MCC) eCare planning applications and sample data for patient and clinician use.



- **[MyCarePlanner / eCarePlanner](https://github.com/chronic-care)**  

  SMART-on-FHIR apps and related open components developed for electronic care planning around chronic conditions.



- **[OpenMRS](https://github.com/openmrs)**  

  Leading open-source electronic medical record platform frequently extended for care coordination and chronic disease programs in low-resource settings.



- **[FHIR Care Plan and PlanDefinition resources](https://github.com/)**  

  Open implementations and profiles for structured care plans, goals, and activities used in chronic care workflows.



- **[CQL / CDS logic for chronic conditions](https://github.com/chronic-care)**  

  Clinical decision support and quality logic expressed in CQL and FHIR PlanDefinition for chronic care scenarios.



- **[Open source care coordination dashboards](https://github.com/)**  

  Community prototypes for tracking outreach, time, and care-plan status on top of open EHRs or FHIR stores.



- **[Patient engagement open tools](https://github.com/)**  

  Messaging and reminder patterns that can support non-face-to-face chronic care contacts in research settings.



- **[Documentation and eCare / chronic-care playbooks](https://ecareplan.ahrq.gov/)**  

  Guides and architecture notes from public chronic care and MCC eCare planning initiatives.



- **[Self-hosted FHIR care-plan stacks](https://github.com/)**  

  Patterns combining open FHIR servers, care-plan apps, and simple outreach logs for non-production use.



- **[Open quality measure and CCM-adjacent tooling](https://github.com/)**  

  Libraries supporting chronic disease quality measures and care-gap identification.



### Additional Strong Open-Source Options

- Exploring **chronic-care / MCC eCare** SMART-on-FHIR apps for care-plan transparency and research.

- Extending **OpenMRS** for chronic disease programs where full commercial CCM is not available.

- Building internal prototypes on open FHIR CarePlan resources and CQL logic.

- Accepting that Medicare CCM billing compliance, certified EHR integration, full-service staffing models, audit-ready time tracking, and scale still require commercial platforms (ChartSpan, ThoroughCare, Prevounce, TimeDoc Health, Optimize Health, WellSky, etc.).

- Focusing open-source efforts on standards-based care plans, patient-facing tools, and transparent clinical logic.



**Frameworks for building custom systems**: Use open FHIR CarePlan + SMART apps → track contacts in a simple log or open EHR → apply CQL for care gaps → report internally. Suitable for research, public health, and low-resource programs. U.S. practices billing CCM almost always run commercial software or full-service partners.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Chronic care management involves clinical care and regulated billing. Open-source tools are not substitutes for compliant commercial CCM platforms. This list is not medical, billing, or legal advice.



---

**Made for care management teams, value-based care operators, and open health informatics advocates.**

Let's keep chronic care coordinated, standards-based, and as open as practical where appropriate.
