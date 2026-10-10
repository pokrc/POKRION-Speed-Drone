# POKRC repositories | 仓库导航

Updated: 2026-10-10. This index describes repositories owned by [@pokrc](https://github.com/pokrc) at the snapshot date. It distinguishes **original projects** from **forks**; neither a GitHub fork nor an experimental research note establishes authorship of upstream work, operational capability, or award eligibility.

## Original projects | 原创项目

| Repository | Area | Scope |
| --- | --- | --- |
| [POKRION-Speed-Drone](https://github.com/pokrc/POKRION-Speed-Drone) | UAV / hardware | Experimental high-speed micro-quadcopter airframe, selected CAD assets and documented flight-test workflow; not a certified design |
| [tune-betaflight-pid](https://github.com/pokrc/tune-betaflight-pid) | UAV / software | Codex skill for evidence-gated Betaflight Blackbox log analysis and staged CLI suggestions; companion to POKRION |
| [jsp_claim](https://github.com/pokrc/jsp_claim) | Mathematics / Lean 4 | Lean source, theorem-scope records and reproducible checks related to Justin Sun Prize problems; formal theorem checks do not automatically establish prize eligibility |

## Forks | 上游项目分支

| Repository | Original upstream | Role and boundaries |
| --- | --- | --- |
| [awards](https://github.com/pokrc/awards) | [TheJustinSunPrize/awards](https://github.com/TheJustinSunPrize/awards) | Working fork of the official prize catalog; official rules and decisions remain with the upstream maintainers |
| [C9M3mini](https://github.com/pokrc/C9M3mini) | [Pumpkin173/C9M3mini](https://github.com/Pumpkin173/C9M3mini) | Camera application / hardware reference fork; keep upstream attribution |
| [Hasselblad-X-System-CIM-Firmware-Research-Feature-Extensions](https://github.com/pokrc/Hasselblad-X-System-CIM-Firmware-Research-Feature-Extensions) | [derrickyau9/original](https://github.com/derrickyau9/Hasselblad-X-System-CIM-Firmware-Research-Feature-Extensions) | Firmware research reference, not a tested consumer firmware release |
| [Hasselblad-X-System-QEMU-DevKit](https://github.com/pokrc/Hasselblad-X-System-QEMU-DevKit) | [derrickyau9/original](https://github.com/derrickyau9/Hasselblad-X-System-QEMU-DevKit) | Offline UI experimentation / development workbench; does not establish physical-camera functionality |
| [x2d-907-one-click-extension-toolkit](https://github.com/pokrc/x2d-907-one-click-extension-toolkit) | [jkl987/original](https://github.com/jkl987/x2d-907-one-click-extension-toolkit) | Existing extension-toolkit code fork; read its own compatibility, verification and risk documentation before device operations |

## Navigation by goal | 按目标查找

- **Airframe, propulsion, CAD, test methods:** [POKRION](https://github.com/pokrc/POKRION-Speed-Drone).
- **Flight-log data and PID/filter recommendations:** [tune-betaflight-pid](https://github.com/pokrc/tune-betaflight-pid).
- **Prize problem formalization, proof scope, priority and audit:** [jsp_claim](https://github.com/pokrc/jsp_claim). Official records belong to [TheJustinSunPrize/awards](https://github.com/TheJustinSunPrize/awards), not the fork.
- **Hasselblad firmware analysis:** [CIM research fork](https://github.com/pokrc/Hasselblad-X-System-CIM-Firmware-Research-Feature-Extensions) for offline research; [QEMU DevKit fork](https://github.com/pokrc/Hasselblad-X-System-QEMU-DevKit) for emulator testing; [extension-toolkit fork](https://github.com/pokrc/x2d-907-one-click-extension-toolkit) for its documented extension workflows.
- **Other camera hardware / Qt software:** [C9M3mini](https://github.com/pokrc/C9M3mini).

## Repository hygiene | 仓库维护原则

1. Do not delete branches, rewrite commit history, archive projects or merge unrelated projects merely to reduce repository count.
2. For forks, preserve upstream attribution, licensing and synchronization compatibility. Avoid claiming the upstream author's work as your own.
3. For proof repositories, separate an exact theorem statement, verified auxiliary lemmas and a complete proof of the original problem. A green CI build does not settle the last question.
4. For device / flight-control research, distinguish simulation, static evidence and hardware verification. Do not publish proprietary firmware, personal logs, secrets, account credentials or unsupported compatibility claims.
5. Keep project-specific documentation and code in their original repositories; this is a **navigation index**, not a mirror or unified build.

## Snapshot notes (2026-10-10)

- 8 public repositories: **3 original, 5 forks**, none archived at inventory time.
- `jsp_claim` default branch contains several theorem modules whose scope is narrower than the source Erdős problem. Award eligibility must be assessed theorem-by-theorem. Research-only branches should stay separate from approved submissions.
- `awards` is a working fork with several historical JSP-named branches; their presence does **not** imply a pending award or accepted solution.
- The five forks have separate upstream projects; verify divergence and licensing before suggesting upstream synchronization.

This file is a maintained **snapshot**, not a live dashboard. Check repository history and the corresponding upstream site for current decisions.
