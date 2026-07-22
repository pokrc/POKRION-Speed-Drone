# Contributing to POKRION

Thank you for helping improve the POKRION high-speed micro quadcopter platform. The most useful contributions are reproducible engineering observations: a measured improvement, a clearly described failure, a manufacturing correction, or a safe flight-test method.

## Before opening an issue

Please search existing issues first. For a design or flight report, include:

- the repository commit or file revision;
- aircraft mass and major hardware revisions;
- motor, propeller, battery, ESC, and flight-controller details;
- material, printer, layer settings, post-processing, or machining notes;
- firmware version and relevant configuration changes;
- test location type, weather, battery state, and test duration;
- measured current, temperature, vibration, Blackbox findings, or photographs;
- the smallest reproducible change and the result.

Never upload GitHub tokens, receiver identifiers, private addresses, personal information, or unredacted telemetry that identifies a person or location.

## CAD and manufacturing contributions

Describe units, coordinate system, revision, tolerances, intended material, and the manufacturing process. For STL/3MF or other binary files, explain the change in the pull request and keep filenames stable unless a rename is necessary. Do not replace a known-good file silently; state what changed and why.

Before proposing a flight-ready revision, perform a dry fit and a no-propeller bench inspection. Check propeller clearance, motor-bell clearance, fastener retention, cable routing, battery restraint, cooling, and structural interference.

## Flight and tuning contributions

Use a clear, legal test area and follow the safety requirements in the README. Save the configuration backup and preserve the original log. For PID or filter changes, make one parameter-family change per short test flight and report abort conditions.

The companion [Tune Betaflight PID from Blackbox Logs](https://github.com/pokrc/tune-betaflight-pid) project can help turn a `.bbl` log into a staged, evidence-based candidate. It does not replace mechanical inspection, temperature checks, or pilot judgment.

## Pull requests

Pull requests should explain:

1. what changed;
2. which revision or hardware it targets;
3. how it was validated;
4. what remains unverified;
5. any license or attribution implications.

By contributing, you confirm that you have the right to submit the material and that your contribution can be distributed under the repository's applicable license. Commercial use remains restricted by [`LICENSE.txt`](LICENSE.txt).

## Safety and scope

This is experimental high-speed aircraft work. Remove propellers for configuration and bench work, use safe LiPo procedures, and stop after an impact, failsafe, abnormal sound, loss of control, or excessive temperature. Do not contribute military, weapon, armed, or combat-related applications.
