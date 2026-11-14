# URGENT — LPM / AI OPS / IP OPS / ALL PROJECTS — DALEGEND NATIVE GIT + DBRE OPERATIONAL TRANSITION
Record: LPM-DIR-2026-11-14-DALEGEND-NATIVE-GIT-CUTOVER-001
Issued: 2026-11-14 UTC
Authority: DALEGEND owner — one-time organization-wide legacy publication exception
Applies: AP-000, all active portfolio repositories, project engineering chats, and any existing engineering task subject to its established product/release rights.
Status: OWNER DIRECTIVE — NEW NATIVE OPERATIONAL ROUTE. NOT HISTORICAL MIGRATION.

## Terminology and source precedence
From this directive forward: **Git = DALEGEND Git**, the owner-controlled private Forgejo on DALEGEND VPS. **GitHub = external GitHub**, only when specifically named. Do not interpret Git as GitHub.
DALEGEND DBRE = the shared private Build & Release Engine, not an application-specific repository or unconditional production release mechanism.
Legacy GitHub/Drive remain READ-ONLY references for historical decisions, rights, specifications, existing branches and exact source verification until native current-source parity is individually accepted. This one-time circular/handoff package is the last normal GitHub/Drive write. No additional recurring or unsolicited legacy writes; separately authorized disaster-recovery/backups are future policy, not activated now.

## Native infrastructure already verified
Private Forgejo owner account `dalegend-owner` runs on VPS loopback 127.0.0.1:33300, accessed through the owner's authenticated SSH tunnel, without public web exposure. DBRE v0.3 has accepted Git push -> watcher -> durable job -> constrained Docker test -> five scanner checks -> SHA-gated package -> permitted private HTTP deployment -> readback/rollback, and independently restored encrypted offsite Git/DB/receipts.
Accepted native DBRE engine reference: `dalegend-owner/dalegend-dbre-acceptance`, live main commit `4c9d0b1b7f0b0dd1eaeecb6e9a497f9988bbc5f4`. Separate scoped `qa/php` branch passed PHP/Python CI without authorization to deploy. Source acceptance is AP-000 owner-private, not blanket approval for existing applications.

## Immediate project action
(1) Read your matching project-specific native Forgejo handoff at `dalegend-owner/<exact-repository-name>/docs/handoffs/DALEGEND_NATIVE_GIT_PROJECT_START_2026-11-14.md` and the shared portfolio announcement/capability ledger.
(2) Use DALEGEND Direct Infrastructure (VPS first), the exact owner-authorized Forgejo Git transport and DBRE services; verify repo identity, permissions, owner/source/branch, latest accepted checkpoint, true active branch and rights. Do not create duplicate repository or rebuild DBRE.
(3) Promote only the CURRENT approved implementation baseline into its designated separate private DALEGEND Git repository after source validation, with source SHA/provenance and rollback receipt. This is a controlled ACTIVE BASELINE ONBOARDING, not a bulk historical import. Keep original GitHub commits/history unchanged there; do not force-push over this native orientation commit. Existing GitHub main SHA printed in the handoff is a dated pointer, NOT proof of the newest work branch.
(4) Enroll exact repository/branch/project profiles in DBRE with per-project isolation, strict source roots, least-privilege Git identity, security negative gates, private deploy/readback/rollback and distinct human/public/financial release authority. A freshly created empty repository or docs-only commit is NOT an accepted source cutover.
(5) After independent native source/workflow acceptance, all NEW code commits, branches, DBRE receipts, portfolio announcements, capability updates and continuity belong to DALEGEND Git and native private ledgers. Preserve relevant CURRENT governing legacy docs as read-only until their authority is safely reconciled.
(6) Continue the real project implementation. No repeat architectural restart, unneeded manual chat handoff, GitHub Action expenditure, unauthorized public deployment, AI billing, real payments, cross-project data pooling or credential sharing.

## ILPM/LPM shared intelligence
The owner-private Unix socket `/run/dalegend-dbre-control.sock` exposes READ-ONLY `/v1/intelligence/projects`, `/v1/intelligence/capabilities`, `/v1/intelligence/notices`, `/v1/intelligence/inbox/<project>/pending`, `/v1/intelligence/audit`, `/v1/intelligence/native-sources`, engineering work `/v1/projects/<project>`, and Forgejo acceptance `/v1/forgejo`. Call through DALEGEND Direct's authorized VPS identity, not a public IP endpoint. Project identity and acknowledgement remain explicit; do not claim cross-chat automatic consumption where not verified.
Preserve owner authority, supersession, IP/licensing provenance and published-vs-tested distinctions. Existing tasks may need their OWN exact native onboarding and command-path updates before they can obey this route; mere publication does not modify their execution code.

## Strict deferral / no new scheduled jobs
NO portfolio-wide historical GitHub/Drive commit/document migration or automated historical migration task until the full owner-controlled end-to-end operating system is accepted and owner authorizes that separately. Maintain original dates, commit authorship, imported-at metadata, supersession and no-overwrite collision gates on future migration.
NO weekly sweep, propagation scheduler, Drive backup policy, or new recurring migration/communication tasks authorized in this circular.
MFA remains owner-deferred; do not invent MFA approval. All source, production, commercial and financial release authorities stay separate.

## One-time communication package
This circular plus a project-specific handoff is being placed in each existing GitHub repository, each corresponding accessible Drive project folder, and in the private Forgejo repositories. A central LPM announcement is authoritative for the routing decision. Publication once; routine external writes stop after verified distribution. Unavailable or unwritable destinations must be reported, not silently claimed complete.
