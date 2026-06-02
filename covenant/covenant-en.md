# Public Software Fallback and Project Stewardship Covenant

## for the Set-OutlookSignatures Benefactor Circle add-on

**Date:** June 2nd, 2026

**Issuer:**  
**ExplicIT Consulting GmbH**  
Kaiser-Ebersdorfer Straße 206b/3/2  
1110 Vienna  
Austria  
Registered at the Commercial Court of Vienna (Handelsgericht Wien)  
Registration number: FN 607013t

## 1. Preamble

1. ExplicIT Consulting GmbH ("**ExplicIT**") develops, creates and distributes the commercial software product **"Set-OutlookSignatures Benefactor Circle add-on"**, also referred to as the **"Benefactor Circle add-on for Set-OutlookSignatures"**.

2. ExplicIT acknowledges the importance of the free and open project **Set-OutlookSignatures**. The project is currently represented in particular by the GitHub organization and the canonical repository `Set-OutlookSignatures/Set-OutlookSignatures`.

3. By this public covenant, ExplicIT intends to safeguard the technical and organizational continuity of the Set-OutlookSignatures Benefactor Circle add-on for the benefit of the Set-OutlookSignatures project.

4. This instrument is intended as a **public unilateral covenant**. It may in particular be relied upon by the then-current administrators of the canonical Set-OutlookSignatures repository.

## 2. Definitions

### 2.1 Product

"**Set-OutlookSignatures Benefactor Circle add-on**" and "**Benefactor Circle add-on for Set-OutlookSignatures**" mean the commercial add-on created and distributed by ExplicIT under that designation.

### 2.2 Project

"**Project**" means the unincorporated open-source project / community **Set-OutlookSignatures**, currently identified by the GitHub organization and the canonical repository `Set-OutlookSignatures/Set-OutlookSignatures`.

### 2.3 Project Administrators

"**Project Administrators**" means the persons who, at the relevant time, are administrators of the Project’s canonical repository.

### 2.4 Deposit Package

"**Deposit Package**" means the technical package maintained by ExplicIT under Section 4.

### 2.5 Secret Repository

"**Secret Repository**" means the non-public source code repository controlled by ExplicIT in which the current version of the Set-OutlookSignatures Benefactor Circle add-on is maintained.

### 2.6 Production Release

"**Production Release**" means any version designated by ExplicIT for productive use.

### 2.7 Repository Update

"**Repository Update**" means any change to the Secret Repository that changes its contents, build logic, build scripts, or product-relevant metadata.

### 2.8 Proof Repository

"**Proof Repository**" means the public GitHub repository `Set-OutlookSignatures/benefactor-circle-add-on-proof-of-escrow`, used to publish proofs, statements, trigger notices and supplementary documents under this covenant.

### 2.9 Successor

"**Successor**" means a natural or legal person that validly assumes maintenance and/or distribution of the Set-OutlookSignatures Benefactor Circle add-on and assumes this covenant or a materially equivalent commitment in writing towards the Project.

## 3. Beneficiary and Representation of the Project

1. The beneficiary is the **Set-OutlookSignatures Project** as an unincorporated project / community.

2. For purposes of this covenant, the Project is represented by the then-current **Project Administrators** of the canonical repository.

3. Wherever this covenant refers to decisions, resolutions or statements of the Project Administrators, a **two-thirds majority of the then-current Project Administrators** is required.

## 4. Scope of the Deposit Package

1. ExplicIT shall maintain an up-to-date Deposit Package for the Set-OutlookSignatures Benefactor Circle add-on.

2. The Deposit Package shall include at least the following:

### Category A – mandatory

- full source code of the Set-OutlookSignatures Benefactor Circle add-on;
- build and packaging instructions required for technical continuation;
- dependency lists and/or an SBOM, where available;
- configuration and schema definitions;
- tests reasonably useful for maintainability and takeover;
- release and architecture notes reasonably required for understanding and continuation.

### Category B – additionally included

- CI/CD workflows and definitions;
- packaging scripts;
- internal technical documentation reasonably useful for project continuity.

3. The Deposit Package shall expressly exclude:

- customer or user data;
- customer-specific customizations where disclosure would be unlawful or contractually prohibited;
- credentials, passwords, secrets, certificates and private keys;
- third-party proprietary components that ExplicIT may not disclose or relicense;
- internal commercial records, price lists, calculations, bookkeeping data and similar business records.

## 5. Rights Before a Trigger

1. Until a Trigger under Section 8 occurs, all rights in the Set-OutlookSignatures Benefactor Circle add-on remain with ExplicIT unless expressly stated otherwise in this covenant.

2. Until a Trigger occurs, ExplicIT remains free to develop, modify, commercially distribute, discontinue, withdraw, price or otherwise exploit the Set-OutlookSignatures Benefactor Circle add-on at its discretion.

3. Before a Trigger occurs, the Project has no right to disclosure of the source code and no right to permanent access to the Deposit Package or to the Secret Repository.

4. This does not affect only:
   - the public proof right under Section 6; and
   - the inspection and demonstration right under Section 7.

## 6. Public Proof After Production Releases

1. ExplicIT shall update the Deposit Package **within ten (10) business days after each Production Release** of the Set-OutlookSignatures Benefactor Circle add-on.

2. Within the same period, ExplicIT shall publish in the Proof Repository a **public proof record** containing at least:
   - product name;
   - version designation or unique build identifier;
   - UTC timestamp of creation of the Deposit Package;
   - short description of the scope of the Deposit Package;
   - designation of the excluded categories;
   - SHA-256 hash of the Deposit Package;
   - reference to the current version of this covenant.

3. The public proof record merely evidences that a Deposit Package existed at a certain time; it does not create a right to receive the Deposit Package or to access the Secret Repository before a Trigger.

4. The Deposit Package itself remains non-public until a Trigger occurs.

## 7. Inspection and Demonstration Right of the Project Administrators

1. The Project Administrators have the right, after each Repository Update, and at least once per calendar quarter, to be shown:
   - that the Secret Repository actually exists; and
   - that a fully functional version of the Set-OutlookSignatures Benefactor Circle add-on can be built using the build script available there.

2. This is a **demonstration and verification right**, not a general right to copy, export, permanently access or disclose the Secret Repository.

3. The demonstration may, at ExplicIT’s choice, be carried out by:
   - live screen sharing;
   - shared inspection with the Project Administrators;
   - a documented build demonstration;
   - or equivalent technical forms of proof.

4. ExplicIT may take reasonable measures to protect confidential content, secrets, credentials, internal operational information and other sensitive elements from disclosure.

5. Where the exercise of this right requires decisions, nominations or confirmations by the Project Administrators, the two-thirds majority rule under Section 3 shall apply.

## 8. Trigger Events

A Trigger exists only in one of the following cases:

### 8.1 Express Discontinuation

ExplicIT expressly states in writing that the **Set-OutlookSignatures Benefactor Circle add-on** is permanently discontinued, permanently withdrawn from commercial offering, or permanently no longer maintained, **and** that no Successor has been designated for continued maintenance and distribution.

### 8.2 Business Continuity Trigger Without a Successor

A business continuity trigger exists if:

- ExplicIT is dissolved;
- ExplicIT is deleted from the commercial register;
- the legal existence of ExplicIT finally ends;
- or the Set-OutlookSignatures Benefactor Circle add-on is transferred to a third party without that third party assuming both product maintenance and this covenant, or a materially equivalent covenant, in writing.

### 8.3 Express Non-triggers

The following are expressly **not** triggers:

- absence of public releases or updates;
- absence of security fixes;
- death, illness or incapacity of individuals;
- internal organizational changes within ExplicIT;
- the mere opening of insolvency proceedings;
- a mere strategic change;
  unless one of the cases in Sections 8.1 or 8.2 is also met.

## 9. Determination and Assertion of a Trigger

1. A Trigger may be determined and asserted by:
   - ExplicIT itself; or
   - the Project Administrators by **two-thirds majority**.

2. In the case of a Trigger under Section 8.1, the Trigger becomes effective upon publication of the express discontinuation statement.

3. In all other cases, a Trigger must be asserted by a **public trigger notice** in the Proof Repository. The trigger notice must:
   - describe the alleged Trigger;
   - state the relevant facts;
   - and provide for a period of **90 calendar days** from publication.

4. If ExplicIT disputes the trigger notice in writing and with substantiated reasons within those 90 days, the Trigger shall not take effect until resolved.

5. If no substantiated dispute is made within those 90 days, the Trigger shall become effective upon expiry of the period.

## 10. Legal Effect of a Trigger – Project-First Transfer

1. Once a Trigger becomes effective, ExplicIT grants the Project, represented by the Project Administrators, a **worldwide, royalty-free, perpetual, irrevocable, non-exclusive licence** and the right to receive the then-current Deposit Package.

2. These rights include the right to:
   - receive the Deposit Package;
   - make it internally accessible;
   - reproduce it;
   - run it;
   - maintain it;
   - analyse it;
   - modify it;
   - further develop it;
   - and share it with contributors as necessary for continuity of the Project.

3. The first technical takeover shall initially occur in a **separate repository** and not necessarily directly in the Project’s main canonical repository.

4. Until any later publication is decided by the Project, the Project Administrators and contributors properly involved by them shall treat the Deposit Package as confidential to the extent and for as long as public disclosure has not been decided.

5. Whether, when, and under which recognized open-source licence the transferred Deposit Package or derivative works will be publicly published shall be decided by the Project Administrators by **two-thirds majority**.

6. Upon the Trigger, ExplicIT grants the Project the right to make the transferred version and derivative works publicly available under a recognized open-source licence selected by the Project Administrators by two-thirds majority.

7. There is no obligation to publish.

## 11. Trademarks, Names and Domains

1. Unless expressly agreed otherwise in writing, this covenant transfers **no trademark, trade name, domain name, logo or other naming rights** relating to "Benefactor Circle add-on", "Set-OutlookSignatures", "ExplicIT", related logos, domains or other protected signs.

2. After a Trigger, the Project may refer descriptively to the historical origin of the transferred Deposit Package, but may not use protected signs in a way that falsely suggests continuing origin, authorization or commercial affiliation with ExplicIT where none exists.

## 12. Warranty, Support and Liability

1. The Deposit Package is provided **"as is"** upon a Trigger.

2. ExplicIT provides no warranty regarding:
   - correctness;
   - completeness;
   - suitability for a particular purpose;
   - buildability in every environment;
   - or non-infringement of third-party rights,
     to the extent permitted by law.

3. After a Trigger, ExplicIT has no obligation to:
   - provide support;
   - extend documentation;
   - answer questions;
   - fix defects;
   - or produce additional releases.

4. To the extent permitted by law, ExplicIT’s liability under or in connection with this covenant shall be limited to intent and gross negligence; liability for loss of profit, consequential and indirect damages shall be excluded where permissible.

## 13. Successor Rule

1. If a Successor assumes maintenance and distribution of the Set-OutlookSignatures Benefactor Circle add-on and assumes this covenant or a materially equivalent arrangement **in writing**, no Trigger under Section 8.2 shall occur to that extent.

2. A mere transfer of assets, source code or distribution rights without written assumption of the continuation role and this covenant shall not be sufficient.

## 14. Publication, Versions and Signature

1. This covenant shall be published:
   - in the Proof Repository `Set-OutlookSignatures/benefactor-circle-add-on-proof-of-escrow`;
   - and on `set-outlooksignatures.com`.

2. The working publication may be made available in Markdown form.

3. The official published version should additionally be made available as a **PDF**.

4. The official published version may be made available either as a digitally signed PDF or as a scan of a manually signed printout. This covenant does not commit to any single signature method.

5. This covenant may be published in German and English. **The German version shall prevail.**

## 15. Governing Law and Venue

1. This covenant shall be governed by **Austrian law**.

2. To the extent legally permissible, the competent court in Vienna, in particular the **Commercial Court of Vienna (Handelsgericht Wien)**, shall have exclusive jurisdiction over disputes arising out of or in connection with this covenant.

## 16. Entry into Force

This covenant takes effect upon its public publication and signature by ExplicIT.

Wien, 2. Juni 2026

**ExplicIT Consulting GmbH**  
represented by its Managing Director  
**Markus Gruber**
