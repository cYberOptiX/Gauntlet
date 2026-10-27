# Gauntlet Completion Program

**Program location:** `/Users/Miancore/Developer/Projects/Software/Gauntlet`  
**Canonical skill source:** `/Users/Miancore/Resources/Skills/gauntlet`  
**Pi skill link:** `/Users/Miancore/.pi/agent/skills/gauntlet`  
**Program status ledger:** `/Users/Miancore/Developer/Projects/Software/Gauntlet/PROGRAM-STATUS.json`  
**Created:** 2026-10-06  
**Execution model:** eight sequential phases; complete and verify one phase before starting the next.

---

## 1. Program objective

Gauntlet v7.0 is already a valid, locally released review system. This program does not reopen v7 as unfinished. It extends that proven baseline through eight controlled phases:

1. Resolve calibration debt.
2. Expand mutation fixtures.
3. Add deeper runtime evidence and adapters.
4. Calibrate additional executors.
5. Broaden browser, operating-system, device, accessibility, and signing coverage.
6. Build Gauntlet Mission Control.
7. Complete the remaining P1/P2 scale capabilities.
8. Package and establish the chosen distribution process.

"Complete" never means omniscient or universally proven. It means every promised capability has an implemented contract, tested evidence, an honest capability-degradation path, and a fresh release gate. Unavailable environments remain explicit rather than being converted into inferred passes.

---

## 2. Trusted baseline

The current canonical release is the starting point for Phase 1.

| Item | Value |
|---|---|
| Release | Gauntlet 7.0.0 |
| Run ID | `GNT-20261006-131635-b0f002` |
| Gate | `READY` |
| Target fingerprint | `e0b9df8818b05e37bea1932ff1d08dc2bfa82e67e296f94ebb45c2b80b13e675` |
| Coverage | 65/65 mandatory surfaces |
| Checks | 67/67 completed |
| Findings | 0 supported release findings |
| Tests | 77 passed; 1 platform-dependent skip |
| Rules | 129 unique first-party rules |
| Calibration | `CLEARED_FRONTIER_TWO_PASS` |
| Calibration severe identities | 17/17 matched; 0 unsupported severe clean-control findings |

### Baseline artifacts

- Release directory: `/Users/Miancore/Resources/Skills/.gauntlet-releases/v7.0-20261006`
- Calibration archive: `/Users/Miancore/Resources/Skills/.gauntlet-calibration/v7.0-20261006`
- Manifest SHA-256: `7077ad74c5b2aa739c28a67b4ed75f82149bca8c5d52a80737a48b47b2755e2e`
- Candidate ledger SHA-256: `a0fd810c00278ce3bbd6696efa6d575d564dfa301705c984f1fd1b921206dc98`
- Verifier SHA-256: `16ef60dcad6d77e061f7e35a8d8e2c3e9757108f6566b6405d1ccfc4d5413cad`
- Gate SHA-256: `9fd7f3cea0ef1a9e9fd1913d19dc6b98b2c8828d1533f27d9f372e3da7fab3e5`
- Report SHA-256: `5e8f3ae9d076b4f59645bee9d61ebe7351089fac69b5c75412e9b01accdd840a`
- Release index SHA-256: `2f8a1e8a24f51ac2d2f0b38b46a0be9fd8b80a82c24546b5c662bbab7fef932f`
- Calibration index SHA-256: `89cec1dbdad2904d6c9509a040f1dc1fb8b7d5226a1b2d67c556de581569c715`

The archived run at `/Users/Miancore/Resources/Skills/.gauntlet-releases/v7.0-20261006-postqa-stale-131557` is historical evidence only. It is explicitly invalidated and must never be used as a release baseline.

---

## 3. Non-negotiable program rules

These rules apply to every phase and every fresh session.

1. **One phase at a time.** Work on the lowest-numbered incomplete phase. Do not begin the next phase until the current phase meets its exit gate and `PROGRAM-STATUS.json` records it as complete.
2. **The canonical source is singular.** Edit `/Users/Miancore/Resources/Skills/gauntlet`. Do not create a second operational copy. The project folder holds plans, status, companion-product source where explicitly planned, and program records.
3. **Gauntlet remains first-party and independently authored.** Do not import, copy, depend on, or establish compatibility with another review product.
4. **Targets are read-only by default.** Never execute unknown target code. Runtime adapters may run only an explicitly authorized, controlled command in an isolated environment and must record what ran.
5. **The engine core remains Python-standard-library based.** Optional specialist tools may be capability providers around the core, but absence of those tools must produce a typed limitation, not a crash or invented result.
6. **Static matches remain candidates.** Discovery cannot approve itself. Execution status and criterion result remain separate.
7. **Every target mutation creates a new review epoch.** Never rewrite an old manifest, receipt, ledger, verifier record, gate, report, or release index. Preserve prior evidence and create a fresh run after the final source mutation.
8. **Use `PYTHONDONTWRITEBYTECODE=1` and `python3 -B` for every Python operation against the skill.** No `__pycache__` or `.pyc` may enter the target.
9. **Evidence stays outside reviewed targets.** Receipts directories must begin fresh and empty. Outputs may not overwrite targets or bound evidence.
10. **Secrets remain local and redacted.** Raw secret candidates may not enter prompts, receipts, ledgers, reports, exceptions, paths, archive labels, formulas, telemetry, screenshots, or release names.
11. **Git scopes use immutable Git objects.** Commit and range review must include base-side deleted content and must not substitute ambient worktree bytes.
12. **Sealed calibration stays sealed.** Executors never receive answer keys. Answer-key or severity-policy changes require explicit revision, new hashes, and owner-side scoring.
13. **No unsupported clean bill.** Missing hardware, credentials, browsers, operating systems, signing identities, specialist tools, or remote services must be recorded as `cannot_verify`, `blocked`, or an equivalent typed limitation.
14. **Historical files remain non-operational.** The blueprint and v5 specimen under `analysis/` are context, not executable contracts.
15. **Do not disturb unrelated projects.** RepoVault, ODS, and other worktrees are outside this program unless the user explicitly designates one as a test target.
16. **Ask only at real decision boundaries.** Examples are paid credentials, physical-device access, public/private distribution, signing identity, legal ownership, or an irreversible action. Otherwise inspect, implement, and verify autonomously.
17. **No phase is complete from prose alone.** Completion requires implementation, fixtures, tests, durable evidence, and the phase exit gate.

---

## 4. Per-phase operating procedure

Every phase follows this sequence.

### A. Enter the phase

1. Read this plan completely.
2. Read `PROGRAM-STATUS.json` and select the first phase whose status is not `complete`.
3. Verify the canonical paths, Pi symlink, latest valid release index, and absence of bytecode residue.
4. Change that phase to `in_progress`, record the UTC start time, and save a concise baseline note in the status ledger.
5. Inventory the exact gap before editing. Do not trust the historical blueprint's old capability scores without checking current v7 behavior.

### B. Design and implement

1. Write explicit acceptance criteria and threat boundaries for the phase.
2. Prefer small, composable contracts over one-off branches.
3. Add or update schemas before emitting new machine records.
4. Add positive, negative, ambiguous, failure, stale-state, and secret-safety tests as applicable.
5. Keep generated evidence outside the canonical skill tree.
6. Update operational documentation, version metadata, and migration notes with the implementation.

### C. Verify before release

At minimum:

- Parse every JSON file.
- AST-parse every Python file.
- Validate Agent Skills frontmatter and the 1,024-character description limit.
- Run the full unit suite with bytecode disabled.
- Validate every first-party rule pack and unique rule ID.
- Run targeted phase fixtures and mutation tests.
- Confirm no prohibited references and no raw secret candidates in evidence.
- Confirm no `__pycache__` or `.pyc` exists.
- Recheck Pi discovery and direct skill invocation when the skill contract changes.
- Perform responsive and interaction QA when reports or UI change.

### D. Create the phase release epoch

After the final source edit:

1. Create a new, uniquely named release directory. Never overwrite the v7.0 release.
2. Create a new full manifest over the exact canonical skill tree.
3. Probe into a fresh empty receipts directory.
4. Semantically adjudicate every candidate and account for every mandatory surface.
5. Create the exact candidate ledger.
6. Run the independent findings verifier.
7. Compute the coverage-aware gate.
8. Require a cryptographically bound `READY` result for an unrestricted phase completion. If the intended phase genuinely introduces declared unavailable environments, use the narrower documented verdict rather than weakening policy.
9. Generate the report, run static report inspection, and perform visual QA if applicable.
10. Generate and independently verify a release index covering every release artifact except the index itself.
11. Reopen and hash-validate the manifest, candidate ledger, verifier receipt, gate receipt, report source, and release index.

### E. Exit the phase

Update `PROGRAM-STATUS.json` with:

- status: `complete`, `blocked`, or `in_progress`;
- version and run ID;
- target fingerprint;
- release and calibration paths;
- core artifact hashes;
- tests and fixture metrics;
- remaining limitations;
- exact next action.

Only then may the next phase begin.

---

## 5. Program roadmap and estimates

| Phase | Name | Primary dependency | Estimated focused effort |
|---:|---|---|---:|
| 1 | Calibration debt resolution | v7 baseline and sealed corpus | 1-2 days |
| 2 | Multi-artifact mutation fixtures | Phase 1 severity policy | 2-4 days |
| 3 | Runtime adapters and evidence | Phase 2 fixtures and adapter contract | 2-4 weeks |
| 4 | Additional executor calibration | Phases 1-3 stable contracts | 3-6 hours per model |
| 5 | Environment coverage | Phase 3 runtime harness | 1-3 weeks plus external access |
| 6 | Gauntlet Mission Control | Stable run/evidence APIs from Phases 3-5 | 1-2 weeks |
| 7 | P1/P2 scale capabilities | All prior contracts | 2-4 weeks |
| 8 | Packaging and distribution | Final source and product surfaces | 1-5 days plus external approvals |

Estimates are engineering effort, not promises about unattended elapsed time. Hardware procurement, model downloads, credentials, notarization, remote test services, and external review can add calendar delay.

---

# Phase 1: Resolve calibration debt

## Purpose

Eliminate the eight recorded medium-severity overstatements and improve primary workbook discovery so the independent verifier no longer has to rescue the three previously understated workbook risks. Preserve the verifier as an independent control rather than optimizing it away.

## Workstreams

1. **Debt inventory**
   - Reopen the current calibration archive and identify all eight medium overstatements individually.
   - Record expected identity, observed identity, expected severity, observed severity, clustering behavior, evidence class, and root cause.
   - Categorize each as severity inflation, likelihood inflation, scope inflation, duplicate clustering, anchor error, or fixture/policy ambiguity.

2. **Severity policy reconciliation**
   - Test each proposed policy change against consequence and likelihood, not fixture labels alone.
   - Add ambiguous and clean controls before lowering or raising policy.
   - If expected severities change, explicitly revise the affected sealed answer key, update declared hashes, and create an owner-side policy migration record.

3. **Workbook first-pass improvements**
   - Ensure the discovery receipt makes hidden dependencies, external formulas/links, macros, calculation freshness, and omitted adjacent ranges available as secret-safe structural evidence.
   - Require discovery to recognize the three formerly understated material risks before the verifier pass.
   - Keep formulas, URLs, names, and potential credentials redacted or normalized in external evidence.

4. **Calibration harness**
   - Add regression tests for all debt identities.
   - Add clean and ambiguous cases that would catch overcorrection.
   - Preserve sealed discovery, separate verifier, seal audit, and owner-side score.

## Required deliverables

- Versioned calibration-debt ledger with one terminal disposition per debt item.
- Updated severity guidance, detectors, workbook receipt fields, fixtures, and tests where justified.
- Revised hash-locked fixture manifest if any fixture or answer key changes.
- Fresh sealed two-pass calibration archive.
- Fresh exact-tree Gauntlet release epoch.

## Exit gate

- Eight of eight debt items have explicit, evidence-supported terminal dispositions; none remains silently unresolved.
- Primary discovery finds and correctly characterizes the three workbook risks previously corrected by the verifier.
- All protected CRITICAL/HIGH identities still match.
- Clean controls produce zero unsupported CRITICAL/HIGH findings.
- New ambiguous controls prevent severity tuning to the answer key.
- No raw seeded secret enters any evidence plane.
- Full mechanics and report tests pass.
- Fresh release gate and release index validate.

## Phase 1 individual prompt

```text
Continue the Gauntlet Completion Program with Phase 1 only: Resolve calibration debt.

Read these files completely before editing:
- /Users/Miancore/Developer/Projects/Software/Gauntlet/GAUNTLET-COMPLETION-PLAN.md
- /Users/Miancore/Developer/Projects/Software/Gauntlet/PROGRAM-STATUS.json
- /Users/Miancore/Resources/Skills/gauntlet/SKILL.md
- /Users/Miancore/Resources/Skills/gauntlet/modules/calibration.md
- /Users/Miancore/Resources/Skills/.gauntlet-calibration/v7.0-20261006/owner-score.json
- /Users/Miancore/Resources/Skills/.gauntlet-calibration/v7.0-20261006/calibration-seal-audit.json
- the relevant workbook receipts, discovery results, verifier result, fixture manifest, and sealed answer keys; keep answer keys out of executor contexts.

Canonical source: /Users/Miancore/Resources/Skills/gauntlet
Trusted baseline run: GNT-20261006-131635-b0f002
Trusted baseline fingerprint: e0b9df8818b05e37bea1932ff1d08dc2bfa82e67e296f94ebb45c2b80b13e675

Do implementation work, not just another plan. Inventory all eight medium overstatements and the three workbook risks that required verifier correction. Build an explicit debt ledger. Correct severity, clustering, scope, anchoring, detector evidence, and workbook first-pass behavior without tuning blindly to the answer key. Add positive, negative, and ambiguous regression fixtures. Any severity-policy or answer-key change must be explicit, hash-locked, and owner-scored. Run a fresh sealed discovery pass followed by an independent verifier pass. Never expose answer keys to either executor.

Follow every global invariant in the completion plan. In particular, use PYTHONDONTWRITEBYTECODE=1 and python3 -B, never execute unknown target code, keep evidence outside the target, never overwrite bound evidence, and begin a fresh release epoch after the final source mutation. Do not begin Phase 2.

Phase 1 is complete only when all eight debt items have terminal evidence-supported dispositions, primary workbook discovery independently catches the three previously understated risks, protected severe recall remains complete, clean severe false positives remain zero, all mechanics pass, and a fresh hash-bound release gate and index validate. Update PROGRAM-STATUS.json with exact paths, run ID, hashes, metrics, limitations, and next action. If genuinely blocked by an external dependency, record the blocker precisely and stop without claiming completion.
```

---

# Phase 2: Expand multi-artifact mutation fixtures

## Purpose

Turn mutation proof into a first-class quality system across every supported artifact family. A claimed guard must fail when its protected defect is restored and pass after correction.

## Workstreams

1. **Mutation contract**
   - Define a versioned mutation recipe and receipt schema.
   - Bind baseline artifact, mutation operation, expected detector/rule, expected severity range, expected anchor, command/tool identity, failing-before proof, passing-after proof, cleanup, and hashes.
   - Reject a mutation receipt that cannot prove it tested the intended bytes.

2. **Fixture families**
   - Repositories and Git histories.
   - Packaged application topology.
   - Websites and standalone HTML.
   - Workbooks, data, and configuration.
   - Documents, PDFs, media, and archives.
   - Prompts, skills, and agents.
   - Plans/specifications and mixed submissions.

3. **Control design**
   - Positive seeded defects.
   - Clean controls.
   - Ambiguous controls.
   - Counter-control fixtures where a hidden mitigation should suppress or reduce a finding.
   - Stale, deleted, renamed, inaccessible, sampled, and budget-exhausted surfaces.

4. **Benchmark metrics**
   - Identity recall, severe recall, false-severe rate, severity accuracy, anchor accuracy, duplicate/root-cause accuracy, coverage accounting, runtime, and cost where applicable.
   - Lock targets and keys by hash.
   - Keep real credentials and personal data out of fixtures.

## Required deliverables

- Mutation schema and engine support.
- Deterministic fixture generators where binary artifacts are required.
- Versioned fixture matrix and sealed keys.
- Failing-before and passing-after receipts.
- Benchmark summary and release thresholds.
- Fresh release epoch.

## Exit gate

- Every active first-party adapter has positive, negative, and ambiguous mutation coverage or an explicit unsupported-boundary record.
- Every fixed protected CRITICAL/HIGH guard represented in the suite has failing-before and passing-after proof.
- Fixture generation is byte-deterministic where promised.
- Mutation cleanup leaves target trees unchanged.
- Reduced scope cannot falsely mark old findings fixed.
- Secret-safety and stale-target tests pass.
- Fresh release gate and index validate.

## Phase 2 individual prompt

```text
Continue the Gauntlet Completion Program with Phase 2 only: Expand multi-artifact mutation fixtures.

Read completely:
- /Users/Miancore/Developer/Projects/Software/Gauntlet/GAUNTLET-COMPLETION-PLAN.md
- /Users/Miancore/Developer/Projects/Software/Gauntlet/PROGRAM-STATUS.json
- the Phase 1 completion artifacts and fresh release index
- /Users/Miancore/Resources/Skills/gauntlet/modules/calibration.md
- /Users/Miancore/Resources/Skills/gauntlet/modules/engine.md
- /Users/Miancore/Resources/Skills/gauntlet/fixtures/universal/README.md
- current fixture manifests, generators, schemas, adapters, tests, and rule packs.

Canonical source: /Users/Miancore/Resources/Skills/gauntlet

Do implementation work. Define a first-class mutation recipe and receipt contract that binds exact baseline bytes, exact mutation, expected rule/identity/severity/anchor, failing-before evidence, passing-after evidence, cleanup, and hashes. Expand deterministic seeded faults, clean controls, ambiguous controls, and hidden-mitigation controls across repositories, app topology, sites, standalone HTML, workbooks, data/config, documents/PDFs, media, archives, prompts/skills/agents, plans/specs, and mixed targets. Do not use real secrets or execute unknown fixture code.

Measure recall, false-severe rate, severity accuracy, anchor accuracy, duplicate/root-cause accuracy, coverage, runtime, and cost where available. Hash-lock targets and sealed keys. Prove critical guards fail when the defect is restored and pass after correction. Add stale, deleted, renamed, inaccessible, sampled, and interrupted cases. Do not begin Phase 3.

Follow all program invariants, including bytecode suppression, read-only targets, fresh external evidence directories, independent verifier use, and a fresh exact-tree release epoch after final mutation. Mark Phase 2 complete only when every active adapter has meaningful positive, negative, and ambiguous mutation coverage or an explicit typed boundary, all required mutation receipts validate, the full suite passes, and the fresh gate and release index validate. Update PROGRAM-STATUS.json with exact evidence and stop.
```

---

# Phase 3: Add deeper runtime adapters and evidence

## Purpose

Move from static structural confidence to controlled observed behavior without weakening Gauntlet's safety model or executing unknown target code by default.

## Workstreams

1. **Universal adapter contract**
   - `detect`, `inventory`, `static_probe`, optional `runtime_probe`, `findings`, `receipts`, `cleanup`, and `capability_degradation`.
   - Version, provenance, applicability, required tools, permissions, safety class, budgets, and evidence ceiling.
   - Uniform receipts for command, scope, environment, tool version, start/end, duration, exit, output hashes, produced artifacts, cleanup, limitations, and target fingerprint.

2. **Capability provider boundary**
   - Keep the engine core standard-library only.
   - Treat browser drivers, LibreOffice, media decoders, signing tools, emulators, and specialist parsers as optional declared providers.
   - Discover capabilities without installing or downloading silently.
   - Require explicit authorization before building or launching submitted applications or code.

3. **Artifact runtime families**
   - Documents/PDFs: render, pagination, fonts, links, forms, metadata, active content, signatures, and extraction parity.
   - Workbooks: clean-environment recalculation, cached-value comparison, locale/date behavior, exports, macros as unavailable unless safely analyzed, and lineage.
   - Media: safe decode, duration/stream integrity, metadata, frame/audio characteristics, and playback limitations.
   - Archives/binaries: existing no-extraction baseline plus optional disposable-sandbox inspection under strict budgets.
   - Data/config: parser round trips, schema/invariant checks, migrations in disposable copies, and environment drift.
   - Standalone HTML/web: file protocol, offline, narrow/wide layout, controls, console, network, storage, accessibility, and exports through browser CDP where available.
   - Packaged apps: build/launch only with explicit trust and isolation; first run, permissions, persistence, interruption, update, rollback, and removal.
   - AI agents: versioned simulations for hierarchy, injection, tools, memory, autonomy, budgets, fallback, and stop behavior without granting unsafe real-world authority.

4. **Capability degradation**
   - Every unavailable runtime proof emits a typed limitation naming the missing provider and exact settling check.
   - Static evidence must never be promoted to runtime evidence.

## Required deliverables

- Versioned adapter and capability-provider contracts.
- Runtime receipt schema and validators.
- First-party implementations for the listed families where locally safe.
- Explicit providers and degradation records where specialist environments are unavailable.
- Runtime fixtures and mutation tests.
- Updated rule routing and documentation.
- Fresh release epoch.

## Exit gate

- New artifact support can be added without changing core reasoning semantics.
- Every runtime claim resolves to a validated receipt and exact target fingerprint.
- Unknown target code never executes implicitly.
- Optional-tool absence degrades honestly and deterministically.
- Runtime fixtures include success, failure, timeout, interruption, stale artifact, cleanup, and secret-safety cases.
- Full regression suite and fresh release gate pass.

## Phase 3 individual prompt

```text
Continue the Gauntlet Completion Program with Phase 3 only: Add deeper runtime adapters and evidence.

Read completely:
- /Users/Miancore/Developer/Projects/Software/Gauntlet/GAUNTLET-COMPLETION-PLAN.md
- /Users/Miancore/Developer/Projects/Software/Gauntlet/PROGRAM-STATUS.json
- completion artifacts from Phases 1 and 2
- /Users/Miancore/Resources/Skills/gauntlet/modules/engine.md
- modules/artifacts.md, spreadsheets.md, runtime.md, platform.md, operations.md, ai.md, toolchains.md, and sources.md
- all current adapter, receipt-schema, rule-routing, and mutation-fixture code.

Canonical source: /Users/Miancore/Resources/Skills/gauntlet

Implement a versioned universal adapter contract with detect, inventory, static probe, optional runtime/render probe, findings, receipts, cleanup, and capability degradation. Keep the core Python-standard-library based. Model browsers, LibreOffice, media tools, signing tools, emulators, and specialist parsers as optional declared capability providers; do not silently install tools. Never execute unknown target code. Building or launching submitted code requires explicit trust, isolation, and a recorded authorization boundary.

Add controlled runtime evidence for documents/PDFs, workbook recalculation, media, archives/binaries, data/config migrations, standalone HTML/web, packaged apps, and AI-agent simulations. Work family by family with fixtures. Receipts must bind command/tool/environment/scope/timing/exit/output hashes/cleanup/limitations to the exact target fingerprint. Tool absence must produce a typed limitation with the exact settling check, never an inferred pass. Add success, failure, timeout, interruption, stale artifact, cleanup, and secret-safety tests. Do not begin Phase 4.

Follow every global invariant in the plan. After final source edits, create a fresh exact-tree review epoch and release. Complete Phase 3 only when the adapter contract is extensible without changing core reasoning semantics, every supported runtime claim has validated evidence, unsafe implicit execution is impossible, all fixtures and regressions pass, and the new gate and release index validate. Update PROGRAM-STATUS.json and stop.
```

---

# Phase 4: Calibrate additional executors

## Purpose

Prove which installed or intended frontier, heavy-local, mid-local, and light executors may perform which Gauntlet work. Capability is earned by evidence, not model name.

## Workstreams

1. **Executor inventory**
   - Enumerate actually available providers/models, exact versions or digests, context limits, tool access, structured-output support, runtime constraints, and privacy boundary.
   - Do not assume a model is installed or reachable.

2. **Executor registry**
   - Tier, approved task classes, prohibited task classes, required protocol, evidence ceiling, fixture suite version, score, independent-verifier requirement, calibration date, expiration/retest triggers, and failure history.
   - Embedding models remain retrieval-only.

3. **Sealed runs**
   - Run the universal and mutation suites without answer keys in context.
   - Preserve session seals and access audits.
   - Use a separate verifier pass and owner-side scoring.
   - For small-context models, enforce one module or adapter group per pass with manifest/ledger continuity.

4. **Decision policy**
   - Downgrade or reject models that miss protected findings, invent severe findings, leak secrets, violate coverage, or cannot maintain evidence contracts.
   - Light models may only perform narrow mechanical passes reverified by a higher tier.

## Required deliverables

- Versioned executor registry.
- One sealed calibration archive per available candidate.
- Comparative scorecard across artifact families and task classes.
- Routing policy used by the skill and Mission Control.
- Explicit unavailable-model records rather than fabricated results.
- Fresh release epoch if operational routing or source changes.

## Exit gate

- Every intended executor has a current pass/fail/limited record tied to an exact model identity and fixture version.
- No uncleared non-frontier executor can run an unrestricted real review.
- Protected severe recall and clean-control thresholds hold for approved scopes.
- Session seal audits show no answer-key access.
- Routing tests enforce all restrictions.

## Phase 4 individual prompt

```text
Continue the Gauntlet Completion Program with Phase 4 only: Calibrate additional executors.

Read completely:
- /Users/Miancore/Developer/Projects/Software/Gauntlet/GAUNTLET-COMPLETION-PLAN.md
- /Users/Miancore/Developer/Projects/Software/Gauntlet/PROGRAM-STATUS.json
- /Users/Miancore/Resources/Skills/gauntlet/modules/calibration.md
- the final fixture, mutation, adapter, severity, and verifier contracts from Phases 1-3
- the latest valid calibration indexes and seal-audit format.

Inventory only models and providers that are actually installed or reachable. Record exact model identity or digest, context limit, tool access, privacy boundary, structured-output ability, and runtime constraints. Create a versioned executor registry covering tier, allowed and prohibited tasks, required pass protocol, evidence ceiling, suite version, score, calibration date, expiration/retest triggers, and failure history. Embedding models are retrieval-only.

Run each intended non-frontier executor blind against the sealed universal and mutation suites. Never place answer keys in executor context. Enforce one-module-per-pass and ledger continuity for constrained models. Use a separate verifier and owner-side scoring. Reject, downgrade, or scope-limit any model that misses a protected defect, invents a severe clean-control finding, leaks a secret, violates coverage, or cannot preserve the finding contract. Do not claim results for unavailable models and do not begin Phase 5.

If the intended model set is genuinely ambiguous after inventory, ask one concise question listing the available candidates and a recommended set; otherwise proceed. Follow all global safety and release rules. Complete Phase 4 only when every intended executor has an exact current pass/fail/limited record, routing enforcement tests pass, seal audits hold, and any source changes have a fresh valid release epoch. Update PROGRAM-STATUS.json and stop.
```

---

# Phase 5: Broaden environment coverage

## Purpose

Add reproducible evidence across the environments where reviewed products actually ship, while keeping unavailable hardware, operating systems, credentials, and assistive technologies explicit.

## Workstreams

1. **Environment matrix**
   - Browser engines and versions.
   - macOS, Windows, Linux, iOS, and Android as applicable.
   - Narrow/wide screens, pixel density, keyboard/pointer/touch, reduced motion, increased contrast, zoom, and text scaling.
   - VoiceOver and other available assistive technologies.
   - Offline, slow, interrupted, denied-permission, low-storage, first-run, upgrade, rollback, and uninstall states.

2. **Execution providers**
   - Local browsers through declared automation interfaces.
   - Virtual machines, simulators, emulators, physical devices, or remote labs only when authorized and available.
   - Provider identity, OS build, browser/app build, device profile, and evidence capture in every receipt.

3. **Signing and distribution evidence**
   - Stable signing identity, entitlements, packaged artifact identity, notarization or platform reputation where required, clean-machine install, update, rollback, and removal.
   - Use the dedicated notarization skill and current Apple tooling for macOS distribution work.
   - Never expose signing credentials in evidence.

4. **Coverage policy**
   - Define minimum matrices by artifact and intended audience.
   - Distinguish local proof, remote-provider attestation, physical-device proof, and unavailable evidence.

## Required deliverables

- Versioned environment matrix schema and receipts.
- Local automated browser/accessibility checks.
- Configurable providers for remote/virtual/device testing.
- Signing/package verification integration.
- Environment coverage report and capability gaps.
- Fixtures for matrix accounting and unavailable-provider behavior.
- Fresh release epoch for source changes.

## Exit gate

- Every required environment cell has a terminal state and evidence or reason.
- No single-browser run is described as browser-matrix proof.
- Accessibility claims distinguish static semantics from assistive-technology observation.
- Signing credentials never enter evidence.
- Clean install/update/rollback/removal checks are reproducible where applicable.
- Missing external access cannot yield unrestricted readiness.

## Phase 5 individual prompt

```text
Continue the Gauntlet Completion Program with Phase 5 only: Broaden browser, operating-system, device, accessibility, and signing coverage.

Read completely:
- /Users/Miancore/Developer/Projects/Software/Gauntlet/GAUNTLET-COMPLETION-PLAN.md
- /Users/Miancore/Developer/Projects/Software/Gauntlet/PROGRAM-STATUS.json
- final runtime/provider contracts from Phase 3 and executor routing from Phase 4
- /Users/Miancore/Resources/Skills/gauntlet/modules/platform.md
- modules/experience.md, premium.md, operations.md, runtime.md, toolchains.md, and sources.md.

Inventory actual local browsers, OS capabilities, simulators/emulators, assistive technologies, signing tools, identities, physical devices, and authorized remote providers. Build a versioned environment-matrix contract and receipts covering browser/OS/build/device profile, viewport/input, accessibility settings, network/storage/permission states, package identity, timing, outputs, and limitations. Implement local automated coverage first, then configurable external providers. Do not silently install paid tools, enroll devices, upload private targets, or use signing credentials without authorization.

Add explicit checks for keyboard, touch where available, zoom/text scaling, reduced motion, increased contrast, VoiceOver or other available assistive technology, offline/interrupted/denied states, clean installation, update, rollback, removal, signing, and notarization where applicable. Use the dedicated notarization skill for macOS notarization work. Keep all credentials and private target content out of receipts. Every matrix cell must end with evidence or a typed reason. Do not begin Phase 6.

Ask only when a real hardware, credential, paid-provider, or upload decision is required; recommend the safest default. Never turn unavailable environments into passes. Complete Phase 5 when matrix accounting and provider tests pass, local evidence is reproducible, limitations are explicit, and all source changes have a fresh valid release. Update PROGRAM-STATUS.json and stop.
```

---

# Phase 6: Build Gauntlet Mission Control

## Purpose

Create a premium, distinct review surface that lets a reviewer understand coverage, checks, findings, evidence, gates, remediation, waivers, and revision history without reading raw transcripts.

## Recommended architecture

Build Mission Control as a companion application under `/Users/Miancore/Developer/Projects/Software/Gauntlet/mission-control`, not as generated residue inside the canonical skill. It consumes versioned Gauntlet artifacts through a read-only boundary. Any operational protocol or schema changes still belong in the canonical skill and require a fresh skill release.

## Workstreams

1. **Research and product definition**
   - Before UI implementation, load the `frontend-design`, `mobbin-search` or `mobbin`, and relevant security guidance skills.
   - Define reviewer jobs, information hierarchy, sensitive-data policy, and accessibility target.

2. **Read-only evidence layer**
   - Open release indexes first, verify hashes, then expose only validated artifacts.
   - Never rewrite manifests, receipts, ledgers, verifier records, gates, or reports.
   - Sanitize paths, labels, authored fragments, and exceptions.
   - Store user preferences and annotations separately from bound evidence.

3. **Core surfaces**
   - Run library and status.
   - Target identity and scope.
   - Coverage tree with terminal-state reasons.
   - Checks and receipts.
   - Findings, evidence classes, anchors, counter-evidence, severity, confidence, and status.
   - Gate explanation and blockers.
   - Re-review delta.
   - Remediation, accepted decisions, watch items, and revision comparison.
   - Executor, environment, calibration, runtime-provider, and benchmark views.

4. **Experience quality**
   - Keyboard-first navigation, visible focus, screen-reader semantics, reduced motion, responsive layouts, empty/loading/error/stale/tampered states, large-run virtualization, safe export, and print/PDF behavior.
   - Deliberate visual identity rather than a generic dashboard.

5. **Security and privacy**
   - Local-first by default.
   - No raw transcripts or target content in telemetry.
   - No active rendering of untrusted evidence.
   - Strict content security and inert previews.

## Required deliverables

- Mission Control source, architecture record, and threat model.
- Versioned read-only artifact API.
- Core screens and interactions.
- Automated unit/integration/accessibility/security tests.
- Visual evidence board and responsive QA.
- Install/run documentation.
- Independent Gauntlet review of Mission Control itself.

## Exit gate

- A reviewer can explain a run, its coverage, evidence, findings, limitations, and gate without raw transcripts.
- Tampered or stale evidence is visibly blocked.
- Mission Control cannot overwrite bound evidence.
- Secret/path sanitization tests pass.
- Keyboard, screen-reader semantics, reduced motion, narrow/wide layouts, and failure states are verified.
- Mission Control passes its own independent Gauntlet release review.

## Phase 6 individual prompt

```text
Continue the Gauntlet Completion Program with Phase 6 only: Build Gauntlet Mission Control.

Read completely:
- /Users/Miancore/Developer/Projects/Software/Gauntlet/GAUNTLET-COMPLETION-PLAN.md
- /Users/Miancore/Developer/Projects/Software/Gauntlet/PROGRAM-STATUS.json
- final schemas, release index, runtime/provider, executor, environment, gate, delta, and report contracts from Phases 1-5
- /Users/Miancore/Resources/Skills/gauntlet/modules/design.md
- modules/experience.md, premium.md, security.md, data.md, operations.md, and platform.md.

Before designing, load and follow the frontend-design skill and the Mobbin search skill; use real interface references deliberately rather than producing a generic dashboard. Build Mission Control as a companion application at /Users/Miancore/Developer/Projects/Software/Gauntlet/mission-control unless evidence proves a safer architecture. It must consume validated Gauntlet release artifacts through a read-only interface. Verify release-index hashes before opening evidence. Never rewrite a manifest, receipt, ledger, verifier record, gate, report, or calibration record. Keep annotations and preferences separate.

Implement the run library, target/scope view, coverage tree, checks/receipts, finding detail and evidence, gate explanation, re-review delta, remediation/accepted/watch state, revision comparison, and executor/environment/calibration/provider views. Include tampered, stale, empty, loading, error, partial, and large-run states. Make it local-first, secret-safe, inert toward untrusted content, responsive, keyboard-first, screen-reader semantic, and reduced-motion aware. Add automated unit, integration, accessibility, and security tests plus desktop/mobile visual QA. Do not begin Phase 7.

Run an independent Gauntlet review against Mission Control itself. Phase 6 is complete only when a reviewer can explain a run without raw transcripts, tampered evidence is blocked, bound evidence cannot be overwritten, privacy tests pass, accessibility and responsive behavior are evidenced, and the companion app has a valid release record. Update PROGRAM-STATUS.json and stop.
```

---

# Phase 7: Complete remaining P1/P2 scale capabilities

## Purpose

Finish the operational capabilities needed for large, persistent, measurable reviews. Reconcile the historical blueprint against the current implementation rather than treating old scores as truth.

## Workstreams

1. **Current gap matrix**
   - Re-evaluate every P1/P2 blueprint item against the current source and Phases 1-6.
   - Mark complete, partial, superseded, or missing with evidence.

2. **Dynamic applicability and typed routing**
   - Machine-readable adapter/module/rule/check selection and exclusion reasons.
   - Rule provenance, version, applicability, and fixture coverage.

3. **Stable runner and machine outputs**
   - First-party runner contract.
   - Equivalent terminal, agent, editor, and CI behavior.
   - JSON and code-oriented SARIF where appropriate.
   - Policy-controlled exit codes for severity, coverage, unknowns, stale evidence, and blocked providers.

4. **Semantic batching and bounded concurrency**
   - Risk-aware deterministic grouping.
   - Bounded workers, cancellation, cleanup, and cross-group synthesis.
   - No duplicate work, omitted surfaces, or race-dependent results.

5. **Budgets, checkpoints, and resume**
   - Time, token, cost, tool, surface, expansion, and concurrency budgets.
   - Fingerprint-compatible checkpoints.
   - Honest `PARTIAL`/blocked outcomes on interruption or exhaustion.
   - Resume only exact compatible work.

6. **Privacy-aware observability**
   - Duration, model/provider, tools, cost, failures, and coverage without source content by default.
   - Explicit retention policy for transcripts or target-derived material.
   - Telemetry redaction tests.

7. **Large-target and benchmark proof**
   - Large mixed fixtures, cancellation, resume, concurrency, deterministic ordering, and cross-domain findings.
   - Publish precision, recall, severity, anchor, coverage, runtime, and cost metrics against locked suites.

## Required deliverables

- Evidence-backed P1/P2 gap matrix.
- Typed applicability/routing enhancements.
- Stable runner, JSON/SARIF outputs, and CI policy.
- Deterministic grouping, concurrency, cancellation, budgets, checkpoints, and resume.
- Privacy-aware telemetry and retention controls.
- Large/mixed benchmark fixtures and results.
- Mission Control integration.
- Fresh release epoch.

## Exit gate

- Same target and configuration produce equivalent identity, coverage, ledger, and verdict across supported invocation modes.
- Interrupted or budget-limited runs cannot silently lose work or return unrestricted readiness.
- Resume rejects incompatible fingerprints and reuses only bound compatible evidence.
- Concurrency does not change deterministic output or miss cross-group defects.
- Default telemetry contains no source or secret material.
- Locked large-target benchmarks meet declared thresholds.

## Phase 7 individual prompt

```text
Continue the Gauntlet Completion Program with Phase 7 only: Complete remaining P1/P2 scale capabilities.

Read completely:
- /Users/Miancore/Developer/Projects/Software/Gauntlet/GAUNTLET-COMPLETION-PLAN.md
- /Users/Miancore/Developer/Projects/Software/Gauntlet/PROGRAM-STATUS.json
- all completion and release artifacts from Phases 1-6
- /Users/Miancore/Resources/Skills/gauntlet/analysis/README.md
- the roadmap and capability sections of analysis/gauntlet-universal-blueprint.html as historical context only
- current engine, schemas, rules, runner surfaces, tests, and Mission Control interfaces.

First produce an evidence-backed delta showing which P1/P2 capabilities are complete, partial, superseded, or missing now; do not trust historical capability scores. Then implement the remaining operational gaps: machine-readable applicability and routing, rule provenance/version/fixture coverage, a stable first-party runner, equivalent terminal/agent/editor/CI behavior, JSON and appropriate SARIF output, policy exit codes, deterministic risk-aware batching, bounded concurrency, cancellation and cleanup, time/token/cost/tool/surface budgets, fingerprint-compatible checkpoints and resume, privacy-aware telemetry, retention controls, and large mixed-target benchmarks.

Prove that interruption or budget exhaustion yields honest partial/blocked state, never unrestricted readiness. Resume must reject incompatible target fingerprints. Concurrency must not alter deterministic output, lose surfaces, duplicate work, or hide cross-group defects. Default telemetry must exclude source content and secrets. Integrate the resulting run controls and evidence into Mission Control. Do not begin Phase 8.

Follow all global invariants and preserve the standard-library core. Complete Phase 7 only when supported invocation modes agree on target identity, coverage, ledger, and verdict; scale/cancellation/resume/privacy fixtures pass; benchmark thresholds are published and met; and a fresh exact-tree release gate and index validate. Update PROGRAM-STATUS.json and stop.
```

---

# Phase 8: Package and establish distribution

## Purpose

Turn the completed system into a reproducible, installable, updateable, rollback-safe release through an explicitly chosen private or public channel.

## Decision gate

Before publication, obtain one explicit user decision covering:

- private or public distribution;
- repository/release host;
- whether Mission Control ships with the skill or as a separate companion package;
- signing/notarization expectations;
- supported installation methods and update policy.

Prepare a recommendation and all non-destructive work before asking.

## Workstreams

1. **Distribution boundary**
   - Separate public/runtime files from owner-only sealed answer keys, scoring data, raw sessions, credentials, private calibration archives, and private target evidence.
   - Preserve a secure owner calibration plane so public release cannot invalidate the sealed test.

2. **Source and release hygiene**
   - Review version control state and pre-existing changes.
   - Commit coherently without overwriting unrelated work.
   - Version, tag, changelog, release notes, licenses, notices, dependency/SBOM records, and provenance.

3. **Packages**
   - Pi skill package/install path.
   - Mission Control package if included.
   - Reproducible archives with checksums and signed provenance where available.
   - No mutable repository or state inside a replaceable application bundle.

4. **Lifecycle**
   - Install, first run, configuration, update, migration, rollback, uninstall, data retention, and recovery.
   - Missing volume/path behavior and explicit failure rather than silent fallback.
   - Backward compatibility and schema migration tests.

5. **Signing and publication**
   - Sign/notarize distributable applications where required using authorized credentials.
   - Publish only after clean-machine verification and final release-index validation.
   - Never place credentials in logs or archives.

6. **Post-release verification**
   - Install from the released artifact, not the source tree.
   - Run Pi discovery/direct invocation and Mission Control smoke tests.
   - Verify checksums, update/rollback, and owner-only calibration access.

## Required deliverables

- Distribution decision record.
- Public/private file manifest.
- Versioned source commits/tags where authorized.
- Reproducible package(s), checksums, provenance, and signatures where applicable.
- Install/update/rollback/uninstall documentation.
- Clean-machine smoke evidence.
- Final release notes and independently validated release index.

## Exit gate

- The chosen channel and support policy are explicit.
- Sealed answer keys, private sessions, credentials, and private evidence are absent from public packages.
- Installation and direct invocation work from the released artifact.
- Update, migration, rollback, and uninstall behavior are verified.
- Checksums/provenance validate and signing/notarization holds where required.
- The final published artifact passes Gauntlet independently.

## Phase 8 individual prompt

```text
Continue the Gauntlet Completion Program with Phase 8 only: Package and establish distribution.

Read completely:
- /Users/Miancore/Developer/Projects/Software/Gauntlet/GAUNTLET-COMPLETION-PLAN.md
- /Users/Miancore/Developer/Projects/Software/Gauntlet/PROGRAM-STATUS.json
- final release indexes and completion records from Phases 1-7
- current source-control state, licenses, notices, package metadata, Pi packaging documentation, Mission Control build/install documentation, signing requirements, and owner-only calibration records.

First inventory all intended runtime/public files and all owner-only material. Design a hard distribution boundary that excludes sealed answer keys, owner scoring, raw sessions, credentials, private calibration archives, and private target evidence from public packages while retaining a secure owner calibration plane. Prepare a concrete recommendation for private versus public channel, repository/release host, whether Mission Control ships separately, signing/notarization, installation methods, and update policy. Ask the user one focused decision question only after the recommendation and all safe preparatory work are ready.

Then implement the authorized distribution path: review and preserve pre-existing source changes, create coherent commits/tags if authorized, finalize version/changelog/release notes/licenses/notices/SBOM/provenance, build reproducible packages and checksum manifests, document install/first-run/config/update/migration/rollback/uninstall/recovery, sign and notarize applicable apps using the dedicated notarization workflow, and test from the released artifact on a clean environment. Never expose credentials or place mutable state inside a replaceable app bundle.

Do not publish until checksums, provenance, package contents, direct Pi invocation, Mission Control smoke tests, migrations, rollback, uninstall, and owner-only calibration separation are verified. Run an independent final Gauntlet review against the exact distributable. Phase 8 is complete only when the chosen channel is live or the only remaining blocker is an explicitly named external approval/credential that the user has not supplied. Update PROGRAM-STATUS.json with final URLs or package paths, tags, hashes, signing state, evidence, limitations, and support policy.
```

---

# Master continuation prompt for a fresh session

Copy and paste the following prompt into any fresh coding-agent session. It is intentionally phase-selecting: the same prompt can be reused after each completed phase.

```text
Continue the Gauntlet Completion Program autonomously, one phase at a time.

Read these files completely before doing anything else:
1. /Users/Miancore/Developer/Projects/Software/Gauntlet/GAUNTLET-COMPLETION-PLAN.md
2. /Users/Miancore/Developer/Projects/Software/Gauntlet/PROGRAM-STATUS.json
3. /Users/Miancore/Resources/Skills/gauntlet/SKILL.md
4. The modules, schemas, fixtures, tests, release artifacts, and prior-phase evidence named by the first incomplete phase.

Canonical skill source: /Users/Miancore/Resources/Skills/gauntlet
Pi skill link: /Users/Miancore/.pi/agent/skills/gauntlet
Trusted v7 baseline release: /Users/Miancore/Resources/Skills/.gauntlet-releases/v7.0-20261006
Trusted v7 baseline run: GNT-20261006-131635-b0f002
Trusted v7 baseline fingerprint: e0b9df8818b05e37bea1932ff1d08dc2bfa82e67e296f94ebb45c2b80b13e675
The post-QA stale archive ending in 131557 is invalidated historical evidence and must not be used as a release baseline.

Select the lowest-numbered phase in PROGRAM-STATUS.json that is not complete. Work only on that phase. Mark it in_progress with a UTC timestamp, verify the latest valid baseline and absence of bytecode residue, inventory the exact gap, then implement the phase rather than merely proposing it. If the phase cannot fit safely in one context, complete a coherent tested tranche, persist an exact checkpoint and next action in PROGRAM-STATUS.json, and leave the phase in_progress. Never skip ahead.

Obey every non-negotiable rule in the plan. Gauntlet must remain independently authored and first-party. Never execute unknown target code. Keep the engine core Python-standard-library based. Use PYTHONDONTWRITEBYTECODE=1 and python3 -B for every Python operation touching the skill. Keep all evidence outside reviewed targets. Use fresh empty receipt directories. Never overwrite targets or bound evidence. Static matches are candidates, not findings. Discovery cannot approve itself. Raw secret candidates must never enter external evidence. Keep sealed answer keys out of executor contexts. Treat unavailable tools, hardware, credentials, browsers, operating systems, devices, signing identities, and external services as explicit limitations rather than passes.

Any source mutation ends the compatibility of the previous live manifest. Preserve previous releases, finish source edits, then create a fresh exact-tree epoch: manifest, probes, semantic adjudication, candidate ledger, independent verifier, coverage-aware gate, report, applicable visual QA, and complete release index. If anything changes after the manifest, invalidate that epoch and start another. Do not mark a phase complete until its section-specific exit gate holds and all release hashes validate.

Update operational docs, schemas, fixtures, tests, version metadata, changelog, and migration notes as part of the work. Run all global verification listed in the plan plus the phase-specific suite. Ask the user only at a true external decision boundary such as paid credentials, physical-device access, target upload, public/private distribution, signing identity, legal ownership, or an irreversible action. When asking, provide a recommended default and the minimum choices needed.

At the end of this session, report:
- phase and status;
- implementation completed;
- tests and calibrated metrics;
- release run, gate, paths, and hashes if complete;
- explicit limitations or blockers;
- exact next action.

Persist the same information in PROGRAM-STATUS.json. Do not begin the next phase in the same session unless the user explicitly requests it after reviewing the completed phase.
```

---

## 6. Final program definition of done

The eight-phase program is complete only when:

- all eight phase records are `complete`;
- no phase relies on stale or overwritten evidence;
- calibration debt is closed with preserved severe recall and clean controls;
- multi-artifact mutation proof is operational;
- runtime claims are receipt-backed and capability-aware;
- every intended executor is calibrated and correctly routed;
- environment matrices expose real proof and real gaps;
- Mission Control safely explains validated runs;
- scale, budgets, resume, machine outputs, CI policy, and telemetry pass adversarial fixtures;
- the chosen package and distribution path is reproducible, secret-safe, installable, updateable, rollback-safe, and independently reviewed;
- final release artifacts and their indexes are reopened and hash-validated before delivery.

The system may still have declared specialist or external limits. Those limits do not make the program incomplete if they are accurately represented, enforced by the gate, and paired with the exact evidence needed to lift them.
