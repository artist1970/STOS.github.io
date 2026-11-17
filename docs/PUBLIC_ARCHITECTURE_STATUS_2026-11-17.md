# STOS — Public Architecture Status
Updated: 2026-11-17

STOS is a sovereign terminal operating system under native development. This public repository is its **informational portal**, not a terminal gateway or privileged backend.

## Intended layers
- **STOS interface:** terminal workbench, user workflows and capability displays; no browser-held privileged persistence.
- **Native services:** bounded modules handling terminal identities, repository context, permissions, IPC and storage beneath the interface.
- **Secure storage:** explicit authorization, scoped records, integrity checks and recovery; development tests must not be represented as production certification.
- **Service terminals:** designated service-hosting slots rather than arbitrary remote shells, commissioned one at a time.
- **Continuity goal:** multi-host Khaedropulation across four or more secure server ports, subject to deployment verification.

## What has been tested
Selected native macOS storage behaviors have passed isolated tests for no-replace publication, post-crash duplicate refusal and nonempty payload integrity. Those results do **not** mean public downloads, cross-platform production deployment, automatic recovery or Academy Account Cloud commissioning are complete.

## Public protections
A public STOS edition must expose **features only**, not internal architecture, administrative operations, confidential records, protected recovery packages or privileged control surfaces. Public-facing content must not serve as an access path to protected runtime state.

Historic Wix/SSH/tmux gateway demonstrations, where retained, are legacy reference designs and not the current native production authority. No live services or download availability are implied by this document.
