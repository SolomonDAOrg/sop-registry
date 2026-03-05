# SOP-00002: Futurnetic Principles

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

**Related:** SOP-00001 (SOP Registry and Corporate Equivalency)

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

**Implementation perimeter.** This SOP is about Company-side stewardship of
Protocol IP (governance posture, control discipline, and internal
accountability for persons exercising authority under the Company
Agreement). It is not an operating manual for any implementation and does
not prescribe how any Licensee (or other third party) must build, deploy,
run, or supervise an implementation. Protocol Implementations and
implementation operations are out of scope.

---

## 1. Purpose and perimeter

These principles bind only persons exercising authority under the Company
Agreement when acting for the Company. They are intentionally
implementation-agnostic and do not set requirements for any Licensee
operations unless a specific provision is expressly incorporated by
reference into a separate written agreement.

These principles make explicit (publicly) the Company-side governance and
operational posture used to steward Protocol IP. The intent is not to be
pessimistic or to micromanage -- it is to run a professionally governed DAO
with repeatable controls, clear accountability, and high-signal decision-
making that others can look to and reuse.

This SOP adopts a **Futurnetic** framework: a **"pragmatic system of
decentralized governance"** in which Members govern the Company through the
Futarchic Mechanism (Futarchy), while Cybernetic principles govern day-to-day
operations, control loops, and execution discipline for the Head Steward,
Subcommittees, and other persons exercising authority under
the Company Agreement.

The purpose is to make the DAO's operating philosophy explicit as part
of the Compliance Manual so it can be referenced by governance, audits,
and Operational Packs, and to set a consistent, professional standard for
Company-side stewardship of Protocol IP. It is not a hidden "rulebook"
for Licensee operations or implementation operations.

**Futarchy attribution and role.**
The Company's governance system uses futarchy-based governance
mechanisms ("Futarchy"), including the Futarchic Mechanism identified
in the Company Agreement. The Company acknowledges and gives credit to
futarchy as the market-based governance model underlying Member proposal
adoption and rejection, and to MetaDAO as the source of the
futarchy-based governance intellectual property referenced in
the Company Agreement.

This SOP does not modify the Company's legal position under the
Company Agreement: the Company participates in the Futarchic Mechanism
as a user and does not operate, maintain, or have administrative authority
over the futarchy smart contracts.

### Perimeter / Non-reliance (important)

1. This SOP is an internal governance and contracting artefact. It is
   not user-facing terms, an assurance report, a security certification,
   or professional advice.

2. Nothing in this SOP is intended to create or expand any fiduciary duty,
   duty of care, professional standard of care, or negligence benchmark to
   any person. It is not a promise that any particular control exists or
   will be effective.

3. No third party is an intended beneficiary of this SOP, and no rights
   are granted to any person by its publication.

4. Nothing here modifies (i) the Company Agreement hierarchy
   (Operating Agreement §2.2(1)), (ii) any agreement recorded in the
   Counterparty Agreements Register, (iii) the IP License Framework or any
   License granted under it, or (iv) any repository LICENSE. If there is a
   conflict, higher-precedence instruments and executed agreements control.

5. This SOP does not describe, certify, or govern any Production
   Implementation or implementation operations (including software
   deployments, services, custody, trading, infrastructure, operational
   methods, or business processes) of any Licensee or other third party.

---

## 2. Principles (normative)

### (a) Futarchic governance, Cybernetic operations

Members govern the Company through the Governance System
(including Futarchy) by adopting or rejecting proposals and Resolutions.
Day-to-day execution, risk handling, and operational adaptation are
governed by Cybernetic principles applied within the authority limits
set by the Company Agreement, the Founding Charter, and valid Resolutions.

### (b) Purpose through function

The purpose of a system is what it does. Evaluate by observed behavior and
outcomes, not stated intentions.

### (c) Pragmatism over ideology

Prefer workable solutions that reduce risk and improve reliability over
aesthetic or ideological purity.

### (d) Defensive design

Assume failure modes, adversarial inputs, and edge cases. Build guardrails,
invariants, and monitoring accordingly. 

### (e) Separation of concerns

Distinct responsibilities, explicit interfaces, minimal coupling, and clear
ownership boundaries. 
When Members serve on Subcommittees, they act within delegated scope under
the Company Agreement and applicable Resolutions, and remain bound by
these principles in that delegated operational capacity.

### (f) Least privilege

Grant the minimum permissions needed to perform a function; prefer
time-bounded, scoped access; continuously review access. 

### (g) Compartmentalization

Design isolation boundaries to limit blast radius (keys, services, release
pipelines, roles, and on-chain authorities). 

### (h) Holistic integration

Local optimizations can kill the system. Ensure components operate
coherently as an integrated whole (technical + governance + legal perimeter). 

### (i) Standard operating procedures

Routine operations and incident response should be governed by documented,
repeatable SOPs and runbooks maintained in the SOP Registry.

### (j) High standards

Expect excellence in code quality and professional conduct: testing, review
discipline, incident reporting, and strict respect for governance-set limits.

### (k) Foresight and adaptability

Avoid designs that lock the system into irreversible states, cascading
failures, or terminal spirals. Prefer recoverability, migration paths, and
well-defined escape hatches.

### (l) Culture of care (critical infrastructure posture)

Adopt a critical-infrastructure posture for Protocol IP work: clear
documentation, robust testing, honest incident reporting, and strict
adherence to scope limits and controls. This is an internal posture and
does not create external third-party rights.

### (m) Supply-chain and operational security

Assume sophisticated adversaries exist. Maintain operational security
appropriate to role (MFA/hardware keys, hardware wallets/offline signing
where applicable, provenance verification, access reviews, rotations,
rebuild discipline after suspected compromise).

### (n) Observability and feedback loops

Operate on instrumented reality: measurable signals, explicit
dashboards/alerts, post-incident learning, and rapid feedback into
controls and SOPs.

### (o) Reversibility by default

Prefer changes that can be rolled back, paused, or migrated with bounded
blast radius. Where reversibility is impossible (on-chain constraints,
keys, immutability), treat the decision as high-assurance and
escalation-worthy.

### (p) Traceability and audit trails

Default to written records: decisions, approvals, execution evidence,
and post-incident outcomes. If it cannot be explained, reproduced, or
evidenced, treat it as not done.

### (q) Explicit authority boundaries

Act only under explicit scope and delegation. If authority is unclear,
pause and escalate rather than "fill in the blanks" with implied permission.

### (r) Change control and staged rollout

Prefer small, testable changes with clear rollback paths. Use staging,
gates, and independent review for high-impact or irreversible changes.

### (s) Compensating transparency

When details cannot be disclosed safely or publicly, publish integrity
anchors (hash/CID), scope, and outcome-level reporting. Limit disclosure
without creating an accountability gap.

### (t) Two-person integrity for high-risk actions

For actions with significant blast radius (keys, on-chain authorities,
treasury-adjacent permissions, and Protocol IP releases (e.g., repository
releases)), require a second independent reviewer/sign-off within scope.

### (u) Decision hygiene

Separate facts, assumptions, forecasts, and preferences. Record what
would change the decision, and what signal will confirm or falsify
the chosen path.

### (v) Simplicity is a security control

Prefer simpler mechanisms with explicit invariants over cleverness.
Complexity multiplies failure modes and makes oversight brittle.

### (w) Path of least resistance

Systems drift toward the easiest available behavior. Make the safe, compliant,
and reversible path the default. Make high-blast-radius actions require
deliberate friction (gates, approvals, staging, additional signers).

### (x) Unmeasured is unquantified

If you cannot or are not measuring it, you do not know it. Use proxies and
leading indicators where direct measurement is impractical. Do not claim
precision that cannot be evidenced.

### (y) Risk is never zero

Assume risk exists even when it is not obvious. Quantify risk where possible.
Where it cannot be quantified, approximate it with conservative bounds,
scenario analysis, and explicit assumptions. Revisit approximations when new
signals arrive.

### (z) Avoid circular dependencies

Avoid cycles in authority, process, or technical dependencies. Cycles create
deadlocks, responsibility ambiguity, and hidden failure propagation. Break
cycles with explicit layering, escalation paths, and clear handoffs.

### (aa) Avoid singular brittle dependencies

Avoid single points of failure (people, keys, vendors, pipelines, RPCs, or
critical services). Where a singular dependency is unavoidable, document it,
monitor it, and mitigate with redundancy, rotation, escrow/backup, and
practiced recovery.

---

## 3. Binding effect and enforcement (internal)

1. This SOP is a **Tertiary Instrument**. It supports mandates but cannot
   override Primary or Secondary Instruments or expand custody/economic
   authority (Operating Agreement §6.5(4); Founding Charter §8.4).

2. Pending ratification, interim adoption is guidance only and does not
   expand the authority of any person or Subcommittee
   (Operating Agreement §6.5(4)). Interim SOPs set operational expectations
   for persons exercising authority under the Company Agreement, within the
   scope of existing authority granted by the Primary Instruments (Founding
   Charter §8.2). For licensees and counterparties, binding effect arises only
   to the extent their agreements incorporate these principles.

3. Non-compliance with ratified SOPs by persons exercising authority within
   scope may constitute grounds for existing remedies under the Company
   Agreement, including reporting to Members, recommending corrective
   Resolution, or exercising emergency action under Operating Agreement
   §10.4(2) where applicable. For Licensees, binding effect (if any) arises
   only where and to the extent a specific provision of this SOP is expressly
   incorporated into the applicable License or related written agreement. Any
   consequence of non-compliance in that case is a contractual licensing
   remedy affecting permission to use Protocol IP only, and does not create
   any right or duty for the Company, the Head Steward, or any Subcommittee
   to direct, supervise, or control the Licensee's operations.
   For avoidance of doubt, nothing in this SOP makes the Company a reviewer,
   auditor, operator, controller, or supervisor of any Licensee
   implementation.

4. This SOP does not create new Member duties. It is an internal
   control system for persons exercising authority and for counterparties
   bound by their own agreements.

Nothing in this SOP creates or implies any agency, partnership, joint
venture, employment, fiduciary, or supervisory relationship between the
Company and any Licensee, counterparty, or other person.

---

## 4. Security-sensitive implementation note

Detailed security runbooks, key-ceremony specifics, custody arrangements,
exploit-relevant operational details, and other Security-Sensitive
Information (Operating Agreement §2.1(25)) may be handled via redaction or
hash-only publication, with confidential review available when needed
(SOP-00001 Section 6).

---

## 5. Amendment

This SOP is a Tertiary Instrument. It may be amended on an interim basis
by the Head Steward or by Subcommittees acting within their existing
authority (Founding Charter §8.2), in accordance with Operating Agreement
§6.5(4). Such amendments must be recorded in the SOP Registry and are
subject to objection by Resolution.

No amendment is effective until any required Execution Bundle is executed
and the amended instrument is recorded in the SOP Registry in accordance
with the Founding Charter.
