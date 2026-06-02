# Technical Specification for Deposit, Proof and Trigger Operation

## for the Set-OutlookSignatures Benefactor Circle add-on

**Date:** June 2nd, 2026

## 1. Purpose

This technical specification supplements the public Software Fallback and Project Stewardship Covenant for the **Set-OutlookSignatures Benefactor Circle add-on**.

It describes in particular:

- the technical deposit model;
- the public proof model;
- the inspection and demonstration right;
- the integration of proof materials into the build process;
- and the practical process in the event of a Trigger.

## 2. Repositories

### 2.1 Canonical Project Repository

The canonical public project repository is:

`https://github.com/Set-OutlookSignatures/Set-OutlookSignatures`

### 2.2 Secret Repository

The Set-OutlookSignatures Benefactor Circle add-on is maintained in a non-public repository controlled by ExplicIT Consulting GmbH.

### 2.3 Proof Repository

The public Proof Repository is:

`https://github.com/Set-OutlookSignatures/benefactor-circle-add-on-proof-of-escrow`

It is used exclusively for publication of:

- covenant versions;
- technical specifications;
- proof manifests;
- hash files;
- trigger notices;
- successor statements;
- and other governance documents.

It is **not** used for advance disclosure of the source code.

## 3. Deposit Model

### 3.1 Content of the Deposit Package

The Deposit Package includes the items defined in the Covenant as Categories A and B and excludes Category C.

### 3.2 Form

The Deposit Package shall be created as a compressed archive, for example ZIP.

### 3.3 Versioning

A separate Deposit Package shall be created for each Production Release.

### 3.4 Storage

Until a Trigger occurs, the Deposit Package remains in non-public storage under the control of ExplicIT Consulting GmbH.

## 4. Public Proof of Existence

### 4.1 Deadline

Within ten (10) business days after each Production Release, a public proof record shall be published in the Proof Repository.

### 4.2 Minimum Content

Each proof record shall contain at least:

- product name;
- version or build identifier;
- UTC date of creation;
- deposit package file name;
- SHA-256 hash;
- indication of included scope;
- indication of excluded categories;
- reference to the current Covenant version.

### 4.3 Directory Structure

Recommended structure in the Proof Repository:

`/proof/vX.Y.Z/`

containing at least:

- `deposit-manifest.json`
- `SHA256SUMS.txt`
- `README.md`

### 4.4 Additional Publication

The documents should additionally be published on or linked from `set-outlooksignatures.com`.

## 5. Inspection and Demonstration Right

### 5.1 Frequency

The Project Administrators are entitled to a demonstration:

- after each update of the Secret Repository;
- and at least once per calendar quarter.

### 5.2 Scope of the Demonstration

The demonstration must show:

- that the Secret Repository actually exists;
- that the current state of the repository is technically accessible;
- that the available build script is executable;
- and that it can be used to create a fully functional version of the Set-OutlookSignatures Benefactor Circle add-on.

### 5.3 Permitted Forms

Permitted forms include in particular:

- live screen sharing;
- live build demonstration;
- documented demonstration with a traceable process;
- or equivalent technical proof.

### 5.4 Protection of Confidential Content

ExplicIT Consulting GmbH may redact or otherwise protect sensitive content during the demonstration provided the core proof is not frustrated.

### 5.5 Documentation

A short record should be created for each demonstration, at least including:

- date and time;
- participating persons;
- version / commit reference shown;
- result of the demonstration;
- any limitations or reservations.

## 6. Trigger Process

### 6.1 Express Discontinuation

In the event of an express discontinuation statement by ExplicIT Consulting GmbH, the trigger notice shall be documented in the Proof Repository without delay.

### 6.2 Other Triggers

In all other trigger cases, the Project Administrators shall publish a `trigger-notice.md` in the Proof Repository.

### 6.3 Resolution

Where a decision by the Project Administrators is required, a two-thirds majority shall be required.

### 6.4 Waiting Period

Unless the Covenant provides for immediate effect, a waiting period of 90 calendar days shall apply.

## 7. Handover Upon a Trigger

### 7.1 Delivery

After the Trigger becomes effective, ExplicIT Consulting GmbH shall hand over the current Deposit Package to the Project Administrators.

### 7.2 Initial Takeover

Initial technical takeover shall occur in a separate repository.

### 7.3 Confidentiality Until Publication Decision

Until the Project Administrators decide to publish, the Deposit Package shall be treated as confidential.

### 7.4 Later Publication

Any later public release and the applicable open-source licence shall be decided by the Project Administrators by two-thirds majority.

## 8. Recommended Folder Structure of the Proof Repository

```text
/covenant
  covenant-de.md
  covenant-en.md
  technical-spec-de.md
  technical-spec-en.md

/proof
  /vX.Y.Z
    deposit-manifest.json
    SHA256SUMS.txt
    README.md

/notices
  trigger-notice-template.md
  successor-assumption-template.md
```

## 9. Signature and Publication

1. The official version of the Covenant should additionally be published as a PDF.
2. The official published version may be made available either as a digitally signed PDF or as a scan of a manually signed printout.
3. The Markdown working versions serve transparency, traceability and version control.

## 10. Practical Minimum Process

1. Finalize the internal Production Release.
2. Create the Deposit Package.
3. Calculate SHA-256.
4. Generate the manifest.
5. Structure the materials.
6. Publish the public proof record to the Proof Repository.
7. After repository updates, or at least quarterly, perform the demonstration for the Project Administrators.
8. Store the demonstration record.
