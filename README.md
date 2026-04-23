# CareFusion / BD (carefusion)
CareFusion is a medical technology brand, acquired by BD (Becton, Dickinson and Company) in 2015, best known for the Alaris infusion system and the Pyxis automated dispensing product line. CareFusion does not expose a public developer API; instead, its devices and dispensing systems interoperate with hospital EMRs and pharmacy systems over HL7 v2 messaging, smart-pump interoperability middleware, and vendor-managed integration services. The Alaris Infusion Interoperability program wirelessly transmits orders from EMRs (such as Epic and Cerner) into Alaris large-volume and syringe modules and returns infusion status back to the EMR in near real time, using the Alaris Guardrails drug library as a safety layer.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/carefusion/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **x-type:** company
- **Position:** Consumer
- **Access:** Partner

## Tags

- Automated Dispensing
- BD
- CareFusion
- Connected Devices
- EMR Integration
- Healthcare
- HL7
- Infusion Pumps
- Medical Devices
- Pyxis
- Smart Pumps

## Overview

BD acquired CareFusion for about $12.2 billion in 2015, folding the Alaris smart-pump and Pyxis automated dispensing cabinet product lines into BD's Medical segment. Today, CareFusion-branded products are marketed under BD's brand families page and integrate with healthcare IT via HL7 v2 and device interoperability middleware rather than a public REST API. For infusion, Alaris Interoperability bridges EMRs and pumps so that nurses no longer have to program pumps manually; for dispensing, Pyxis MedStation ES connects to pharmacy systems and EMRs for medication profile management, inventory, and diversion analytics. Developer access is not self-service - integrations are scoped and delivered through BD's Interoperability and Connected Care services teams.

## APIs

### Alaris Infusion Interoperability
The Alaris Infusion Interoperability solution connects the Alaris System (large-volume pump modules and syringe modules) to hospital EMR platforms so that physician infusion orders flow wirelessly into pumps and live infusion status is returned to the EMR. The integration is delivered through BD's infusion interoperability middleware and is typically deployed with Epic and Cerner EMRs using HL7 v2 messaging. The Alaris Guardrails drug library provides the clinical decision support and safety layer that validates dose, concentration, and delivery parameters before a pump accepts an order.

**Human URL:** [https://www.bd.com/en-us/products-and-solutions/products/product-families/alaris-infusion-system](https://www.bd.com/en-us/products-and-solutions/products/product-families/alaris-infusion-system)

#### Features

- EMR-to-pump order transmission for large-volume and syringe modules
- Near real-time infusion status returned to the EMR
- Alaris Guardrails drug library for clinical decision support
- HL7 v2 messaging through BD interoperability middleware
- Epic, Cerner, and other major EMR compatibility
- Reduces error-prone manual pump programming
- Auto-documentation of infusion events in the patient record

#### Use Cases

- Closed-loop infusion pump integration with EMR
- Nursing workflow reduction for high-volume infusions
- Sepsis, anesthesia, and oncology infusion safety
- Medication administration record (MAR) auto-charting
- Infusion analytics and drug library governance

### Pyxis Automated Dispensing Integration
Pyxis MedStation and Pyxis ES automated dispensing cabinets integrate with hospital pharmacy information systems and EMRs so that medication profiles, inventory, and dispense events are synchronized. Integration is delivered through BD Pyxis interoperability services using HL7 v2 messaging (ADT, ORM, RDE, RDS) and direct pharmacy system connectors rather than a public REST API.

**Human URL:** [https://www.bd.com/en-us/products-and-solutions/products/product-families/bd-pyxis-medstation-es-system](https://www.bd.com/en-us/products-and-solutions/products/product-families/bd-pyxis-medstation-es-system)

#### Features

- Pharmacy system and EMR integration via HL7 v2
- ADT-based patient profile synchronization
- Medication order, dispense, and inventory messages
- Controlled-substance diversion analytics
- Pharmacy and unit-based cabinet configuration

#### Use Cases

- Nursing unit medication dispensing
- Pharmacy inventory replenishment
- Controlled-substance chain-of-custody
- Drug diversion analytics and reporting
- ADT-driven medication profile updates

## Common Properties

- [Website](https://www.bd.com/en-us/products-and-solutions/brand-families/carefusion)
- [Alaris Product Page](https://www.bd.com/en-us/products-and-solutions/products/product-families/alaris-infusion-system)
- [Pyxis Product Page](https://www.bd.com/en-us/products-and-solutions/products/product-families/bd-pyxis-medstation-es-system)
- [BD Corporate Site](https://www.bd.com/)
- [Contact](https://www.bd.com/en-us/about-bd/contact-us)
- [Terms of Use](https://www.bd.com/en-us/terms-of-use)
- [Privacy Policy](https://www.bd.com/en-us/our-company/privacy)
- [LinkedIn](https://www.linkedin.com/company/bd1/)
- [X](https://x.com/BDandCo)

## Timestamps

- **Created:** 2026-03-23
- **Modified:** 2026-04-23

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
