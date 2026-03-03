# SOP-00001: SOP Registry and Corporate Equivalency

**Status:** Draft (intended for ratification via next Operational Pack)

**Version:** 1.0.0

**Owner:** SOLOMON DAO LLC (via Governance System)

**Applies to:** Head Steward, Subcommittee Members, and persons exercising
authority under the Company Agreement.

**Effective date:** Upon ratification (or earlier as an Interim SOP adopted
by the Head Steward or by Subcommittees acting within their existing
authority, per Founding Charter §8.2)

**Operational Pack:** None

**Confidentiality classification:** Public

**Supersedes:** None

**Related:** SOP-00000 (Order of Business for Operational Packs)

---

## Intellectual Property Firewall

**"Protocol"** in this SOP has the same meaning as **"Protocol IP"** as
defined in the Company Agreement of SOLOMON DAO LLC
(Operating Agreement §2.1(17)) -- design, documentation, code, repositories,
and other intellectual property. It does not mean an operating business,
service, issuer, custodian, counterparty, or other person or entity.

Nothing in this SOP authorizes the Company, the Head Steward, or any
Subcommittee to direct, supervise, or control the operations of any
Licensee, counterparty, service provider, or other person. Any external
obligations arise only under the applicable License or other written
agreement, and only to the extent expressly stated there.

---

## 1. Purpose

### 1.1 Establishment

This SOP establishes the SOP Registry as the DAO's internal governance
and compliance manual: the canonical location where Company-side
operational and security procedures are recorded, versioned, and
(when appropriate) ratified as Tertiary Instruments of the
Company Agreement.

The intent is to make explicit that the DAO operates a conventional corporate
governance playbook -- with on-chain execution and cryptographic recordkeeping
as the implementation layer.

### 1.2 Registry scope

The SOP Registry is the canonical publication venue for:

1. **Living instruments (current ratified copies).** The current operative
    versions of ratified governance instruments (including registries and any
    operative superseding texts), organized so a reader can find the current
    state without searching across superseded proposals.

2. **Interim SOPs.** Draft or interim Tertiary Instruments published for
    immediate operational use within existing authority and queued for
    ratification (or rejection) via the next Operational Pack.

3. **Confidential or redacted instruments by integrity record.** Entries that
    publish hash/CID and metadata (with optional redactions) when full text
    cannot be disclosed. Reasons include but are not limited to operational
    security, proprietary methods, trade secrets, and counterparty
    agreements or licenses where disclosure would increase exploit risk or
    compromise commercial confidentiality.

---

## 2. Authority, hierarchy, and scope limits

### 2.1 Definitions

Terms defined in the Operating Agreement have the same meaning in this SOP
unless otherwise specified.

- **SOP / Standard Operating Procedure.** A documented operational or
    security procedure governing routine activities, controls, or response
    processes (Operating Agreement §2.1(23)).

- **Operational Pack.** A periodic governance proposal that ratifies a batch
    of Tertiary Instruments, including their hashes or content identifiers and
    effective date (Operating Agreement §2.1(24)).

- **Living instrument (current copy).** A convenience publication of the
    current operative text of a ratified governance instrument as of the
    latest effective change. A living instrument does not override the
    adopting Resolution or the underlying Primary or Secondary Instrument.

- **Registry entry.** A record in the SOP Registry for an instrument, which
    may be full text, redacted, or hash-only. At minimum it includes
    identifier, title, status, scope, effective date, and (where applicable)
    hash/CID.

- **Hash-only entry.** A registry entry that publishes only metadata and
    hash/CID for a confidential instrument, with ratification referencing
    the hash/CID.

### 2.2 Document hierarchy

The Company Agreement comprises:

- **Primary Instruments:** the Operating Agreement, the Founding Charter,
    and the IP License Framework.
- **Secondary Instruments:** the Smart Contract Registry, Website Registry,
    Intellectual Property Registry, IP License & Assignment Register, and
    the Counterparty Agreements Register.
- **Tertiary Instruments:** the SOP: Order of Business for Operational
    Packs, and this SOP Registry (including its contents).
- **Proposal Memoranda:** governance proposal documents maintained in the
    proposal repository, for transparency and best practice only.

In the event of conflict, the order of precedence established in Operating
Agreement §2.2(1) applies:

1. mandatory law;
2. Primary Instruments (in order: Operating Agreement, Founding Charter,
   IP License Framework);
3. Secondary Instruments;
4. Tertiary Instruments; and
5. Proposal Memoranda.

### 2.3 Scope limits

SOPs are Tertiary Instruments. A Tertiary Instrument may not:

1. expand authority beyond what Primary and Secondary Instruments and
   on-chain constraints permit;
2. expand economic powers or custody rights;
3. modify Primary or Secondary Instruments;
4. create obligations for Members beyond existing obligations;
5. grant new rights to access or move Company Treasury Accounts; or
6. override or recharacterize the instrument hierarchy.

(Founding Charter §8.2, §8.4; Operating Agreement §6.5(4); SOP-00000
Section 3.)

---

## 3. The SOP Registry as compliance manual

### 3.1 Binding effect

- **Interim SOPs** may be adopted or amended by the Head Steward or by
    Subcommittees acting within their existing authority (Founding Charter
    §8.2; Operating Agreement §6.5(4)). Pending ratification, interim
    SOPs are guidance only and do not expand the authority of any person
    or Subcommittee (Operating Agreement §6.5(4)). Interim SOPs set
    operational expectations for the Head Steward, Subcommittee Members,
    and persons exercising authority under the Company Agreement, within
    the scope of existing authority granted by the Primary Instruments.

- **Ratified SOPs** (via an Operational Pack adopted by Resolution) are
    binding Tertiary Instruments for all persons exercising authority
    within scope, subject to the hierarchy in Section 2.2 above.

### 3.2 Non-compliance and contractual incorporation limits

Operating outside applicable ratified SOPs (within scope) may constitute:

- grounds for the Head Steward or a Subcommittee to invoke existing
remedies under the Company Agreement, including reporting to Members,
recommending corrective Resolution, or exercising emergency action under
Operating Agreement §10.4(2) where applicable;

- with respect to a Licensee, where (and only where) a specific requirement,
control, specification, or integrity condition published in the SOP
Registry is expressly incorporated into that Licensee's License or other
written agreement, grounds for action under the IP License Framework
(including revocation, narrowing, suspension, or reassignment under §3.5)
or the applicable agreement, to the extent provided there; and

- for counterparties, grounds for action under the applicable counterparty
agreement as recorded in the Counterparty Agreements Register.

This SOP does not create new enforcement mechanics. It operationalizes
existing remedies in the Primary Instruments and applicable agreements.

This SOP does not create duties for Members and does not create duties
to supervise, direct, or control any Licensee's or counterparty's
operations. It is an internal control system for persons exercising
authority under the Company Agreement and a publication and integrity
framework for instruments that may be referenced by separate agreements.

Nothing in this SOP creates or implies any partnership, joint venture
 employment, fiduciary, or agency relationship between the Company and
 any Licensee, counterparty, or other person.

### 3.3 Licensee perimeter and no-agency clarification

For avoidance of doubt, the SOP Registry is a governance and record-keeping
instrument within the Company Agreement hierarchy. It does not by itself
impose obligations on any Licensee, counterparty, or third party unless a
separate written agreement expressly incorporates a specific SOP provision.

Where a License incorporates a specific SOP provision, that incorporation
operates only as a condition on permission to use Protocol IP (including
attribution, integrity, security, scope, or compliance-related boundaries
tied to the License). It does not constitute Company direction, approval,
supervision, or control of the Licensee's business or any Implementation.

No inference of Company direction, control, approval, supervision, agency,
partnership, fiduciary status, or intermediary role may be drawn from:
1. the existence of this SOP Registry;
2. the existence or content of any SOP;
3. the incorporation of any SOP provision into a License;
4. similarities or differences between SOP-incorporation terms across
Licenses; or
5. the Company's exercise of revocation, narrowing, suspension, or
reassignment rights under the IP License Framework.

Nothing in this SOP creates any duty for the Company, the Head Steward,
or any Subcommittee to monitor, police, investigate, supervise, or control
any Licensee or any Implementation.

---

## 4. Corporate equivalency mapping

DAO tooling is unfamiliar; the governance substance is conventional.

| Traditional corporate artefact | DAO / Company Agreement equivalent |
| --- | --- |
| **Bylaws / Constitution** | Operating Agreement, Founding Charter, IP License Framework (Primary Instruments). |
| **Board minutes / Resolutions** | Proposals, vote outcomes, Resolution text, Execution Bundle review, execution evidence, governance log and metadata. |
| **Officer appointments** | Head Steward appointment; Subcommittee establishment by Resolution with defined scope (Founding Charter Article IV); multisig controls. |
| **Compliance manual (internal controls)** | SOP Registry (this) for Company-side governance controls, SOPs, runbooks, key registries, and security policies as Tertiary Instruments; not an operations manual for Licensees or counterparties except where a specific standard is expressly incorporated by reference into a separate agreement. |
| **Annual governance review / AGM** | Periodic Operational Pack proposals: batch ratification of Tertiary Instruments, change log, hashes/CIDs, effective dates, review windows. |
| **Registrar filings** | Certificate of Formation, Beneficial Owner Information Reports (Form 2), annual filings (Form 4), filed by the Head Steward as Representative Agent. |
| **Third-party audits** | Security audits and independent review processes commissioned by Resolution or by Subcommittees within mandate; compensating transparency when details cannot be safely published (Founding Charter Article V). |
| **Public filings / official venues** | Proposal repository, SOP Registry, public chain records, official governance venues designated in the Website Registry. |
| **Board oversight / committees** | Subcommittees with explicit scope limits (Founding Charter Article IV); Audit Subcommittee (Founding Charter §4.5); on-chain constraints and post-execution reporting. |
| **Standard of care** | Good faith within scope of authority; commercially reasonable efforts; covenant of good faith and fair dealing (Operating Agreement §4.3); safe harbour for good faith actions (Founding Charter §6.4). |
| **Limited liability structure** | DAO LLC as the liability wrapper (Operating Agreement §4.2); natural person protections (Founding Charter Article X); separate legal counterparties under the Counterparty Agreements Register. |
| **IP licensing program** | IP License Framework (Primary Instrument); Licenses recorded in the IP License & Assignment Register; Licensee independence and IP firewall. |

---

## 5. Registry mechanics

### 5.1 Canonical locations

The **proposal repository** is the canonical historical record for proposal
history, drafts, discussion context, and execution artefacts.

The **SOP Registry repository** is the canonical source for the current
ratified versions of living instruments and Tertiary Instruments.

The current canonical locations are recorded in SOP-00000 Section 9 and may
be updated by Resolution.

### 5.2 Numbering and naming

- **SOP-00000:** Order of Business for Operational Packs.
- **SOP-00001:** This document (Registry and Corporate Equivalency).
- **SOP-00002 onward:** Subsequent SOPs numbered sequentially.

File naming: `SOP-#####_<kebab-name>.md`

IDs are never reused. If an SOP is superseded, it retains its ID and the
superseding SOP references it.

### 5.3 Required header fields

Each SOP must include:

- **Status:** Draft, Interim, or Ratified.
- **Version.**
- **Effective date** (or "upon ratification").
- **Applies to** (which persons exercising authority it binds).
- **Confidentiality classification:** Public, Redacted + Hash, or
    Confidential + Hash.
- **Supersedes** (if any).
- **Hash/CID** (if referenced in an Operational Pack).
- **External applicability (if any):** Internal-only, or
"Contractual incorporation only" (with agreement/register reference).
- **Relationship boundary statement (required if external applicability
is not Internal-only):** A statement that the SOP sets Company-side
governance controls and/or Protocol IP standards only, and does not
direct, supervise, or control external operations or create agency.

---

## 6. Security-sensitivity, confidentiality, and hash-first publication

### 6.1 Security-Sensitive Information

Security-Sensitive Information is defined in Operating Agreement §2.1(25)
and includes private keys, signing infrastructure, incident-response
runbooks, security controls, vulnerability details pending remediation, and
sensitive arrangements where disclosure would increase exploit risk.

Confidential Information is defined in Operating Agreement §2.1(27).

### 6.2 Allowed publication patterns

For any SOP or registry entry, choose one:

1. **Public full text.**
2. **Redacted public text + published hash/CID.**
3. **Confidential instrument + published hash/CID**, with ratification
   by hash/CID.

In all cases, the SOP Registry must contain a public registry entry
sufficient for integrity verification (identifier, title, status, scope,
effective date, and hash/CID), even when full text is withheld.

### 6.3 No accountability gap

Limiting disclosure is permitted for security and confidentiality, but is
not a shield against accountability:

- Use compensating transparency (on-chain constraints, audits,
  post-execution reporting).
- If a concern remains, governance can appoint a confidential review
  committee or engage an independent reviewer under appropriate controls,
  with a scoped public assurance statement (Founding Charter
  §5.2 through §5.4).

---

## 7. Operational Packs

All SOP changes are batched into periodic Operational Packs (SOP-00000
Section 4) which include:

- scope statement;
- change log;
- document hashes/CIDs;
- effective date; and
- review date.

**Format note (non-substantive).** SOP-00000 controls the normative content
and adoption mechanics for Operational Packs. Future SOPs may designate a
standard presentation template (headings, annex layout, metadata fields,
rendering pack references) for Operational Packs to improve consistency
and tooling. Any such template SOP is administrative only and does not
modify authority limits, adoption requirements, or instrument hierarchy.

Ratification occurs when the Operational Pack is adopted by valid
Resolution (and any required Execution Bundle is executed). Until
ratification, interim SOPs are guidance only and do not expand the
authority of any person or Subcommittee (Operating Agreement §6.5(4)).

---

## 8. SOP incorporation standard for Licenses and counterparties

Any SOP provision intended to apply to a Licensee or counterparty must be
expressly incorporated by reference in the applicable License or agreement.
Incorporation by reference must identify the SOP and, where practical,
the specific section(s) incorporated.

No SOP may be used to prescribe or manage a Licensee's independent business
operations except to the limited extent a License conditions permission
to use Protocol IP on compliance with specified Protocol IP-related terms.
SOPs shall not be drafted or interpreted as employment manuals, operating
directives, or management instructions for Licensees.

Blanket incorporation of the entire SOP Registry into a License is
disfavored and should be avoided unless expressly approved by Resolution
with a stated reason and scope limitation.

---

## 9. Amendment

This SOP is a Tertiary Instrument. It may be amended on an interim basis
by the Head Steward or by Subcommittees acting within their existing
authority (Founding Charter §8.2), in accordance with Operating Agreement
§6.5(4). Such amendments must be recorded in the SOP Registry and are
subject to objection by Resolution.

No amendment is effective until any required Execution Bundle is executed
and the amended instrument is recorded in the SOP Registry in accordance
with the Founding Charter.
