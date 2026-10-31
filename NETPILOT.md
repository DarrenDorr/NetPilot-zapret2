# NetPilot-managed zapret2 fork

This repository preserves upstream `bol-van/zapret2` history and attribution. NetPilot does not treat the moving upstream `master` branch as a trusted production source.

## Reviewed source boundary

The authoritative NetPilot review line is `netpilot/reviewed-v1.0.6-uaf-r43` and starts from upstream commit `4a33055448ce5f4e7acc704e1fbe0d8a8a6aa08d` (`nfqws2: fix UAF`), whose direct parent is the exact v1.0.6 release commit `221d7dff24bfec0cd5ac0a5070b8acef2008af3d`.

NetPilot hardening is maintained as the ordered patch queue under `netpilot/patches/`. A trusted build must verify every recorded SHA-256 and apply patches strictly in numeric order. Automatic sync from upstream `master` is forbidden for release/admission purposes.

## Security state

This fork is a source/provenance boundary only. It does **not** authorize native execution, WinDivert driver loading, product integration, or production release. Those remain blocked until the separate Windows/WinDivert and runtime lifecycle gates pass.

The original MIT license and copyright notice remain in `docs/LICENSE.txt`.
