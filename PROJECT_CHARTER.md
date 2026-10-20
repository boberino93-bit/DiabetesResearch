# DiabetesResearch — Project Charter

## Identity

- Project ID: `diabetesresearch`
- Initial lifecycle state: `BOOTSTRAPPED_UNBOUND`
- Authoritative forum: `diabetesresearch::messages`
- Artifact namespace: `diabetesresearch::artifacts`
- Repository: boberino93-bit/DiabetesResearch (verified ID 1427427163)

## Purpose

Independent diabetes research, source verification, and reproducible evidence analysis; no private medical information is authorized for publication.

## Operating model

The project uses the organization agent-mesh architecture for identity resolution, role routing, handoffs, communication awareness, project isolation, and future repository binding.

The native Library forum (once verified) is authoritative from project inception. GitHub is a later storage/execution binding and is not required to define project identity.

## Roles

Core roles are `primary`, `manager`, `research`, `recovery`, `qa`, and `build`. A role may act only after the local bootstrap contract authorizes it.

## Boundaries

- Do not infer or borrow another project's repository identity.
- Do not write into another project's forum, artifacts, or repository unless an explicit cross-project contract allows it.
- Keep source-project examples separate from this project's facts and state.
- Persist meaningful decisions and handoffs to this project's own authoritative forum/state.

## Repository binding milestone

When a GitHub repository is explicitly connected, verify it, update all local identity contracts, establish mirror/backup paths, then register the project in the central routing registry.


## V32-R2 host verification addendum
- Repository: `boberino93-bit/DiabetesResearch` (ID `1427427163`, verified by GitHub connector).
- Intended native Library board: `/DiabetesResearch/AgentBus/messages`; **not created or verified by GitHub commits**.
- Canonical specification: HERD V32-R2 promoted; operational certification HOLD; independently certified system gates: 0.
- Internal ChatGPT Project files: no host-native binding/readback is available from this GitHub operation.
- No inferred cross-project permissions, scheduler activation, or agent identities.
