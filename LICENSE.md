# Licensing — Chronos Ion

**Chronos Ion** is an _open-hardware_ project, so it isn't a single thing: it
combines **code** (the firmware) with **design files** (the PCB). Each part is
released under the licence that fits it best.

## Quick summary

| Part                       | What it covers                                                | Licence           |
| -------------------------- | ------------------------------------------------------------- | ----------------- |
| Firmware and documentation | Source code (`.c` / `.cpp` / `.h` / `.ino`), `README`, guides | **MIT**           |
| Hardware design            | Schematics, PCB layout, Gerbers, BOM (KiCad files)            | **CERN-OHL-P v2** |

Both are **permissive**: anyone may use modify and redistribute the project, including in commercial or closed products, as long as they keep the copyright
and licence notices. The only thing asked in return is attribution.

The full text of each licence lives in:

- [`LICENSE-MIT`](./docs/licenses/LICENSE-MIT.md) — for the firmware and documentation.
- [`LICENSE-CERN-OHL-P.txt`](./docs/licenses/LICENSE-CERN-OHL-Pv2.txt) — for the design files.

---

## 1. Firmware and documentation — MIT

The MIT licence is one of the simplest and most permissive in existence: it
allows using, copying, modifying and distributing the software with a single
requirement, keeping the copyright notice, and with no warranty.

The full text is in [`LICENSE-MIT`](./docs/licenses/LICENSE-MIT.md).

## 2. Hardware design — CERN-OHL-P v2

The **CERN Open Hardware Licence v2 — Permissive** is the equivalent of MIT but
designed for hardware: it is written in terms of _Source_ (design materials) and
_Product_ (the physical object made from them), concepts a software licence does
not cover. It is permissive, so it allows making products, even for sale,
without any obligation to keep them open; it only requires keeping the notices.

The full text is in [`LICENSE-CERN-OHL-P.txt`](./docs/licenses/LICENSE-CERN-OHL-Pv2.txt).

### How to mark the design files

CERN-OHL-P has no mandatory header, but CERN recommends including this notice in
each design file (or in a `README` inside the hardware folder):

```
Copyright Carmoruda 2026.

This source describes Open Hardware and is licensed under the CERN-OHL-P v2.

You may redistribute and modify this source and make products using it under
the terms of the CERN-OHL-P v2 (https://ohwr.org/cern_ohl_p_v2.txt).

This source is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF
MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE.
Please see the CERN-OHL-P v2 for applicable conditions.
```

For automated tools, a single SPDX line at the top of each file is enough:

```
SPDX-License-Identifier: CERN-OHL-P-2.0
```

## SPDX identifiers

| Part                     | SPDX             |
| ------------------------ | ---------------- |
| Firmware / documentation | `MIT`            |
| Hardware design          | `CERN-OHL-P-2.0` |
