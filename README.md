<h1 align="center">Chronos Ion</h1>
<p align="center">
An open-hardware desk clock with alarm. Time and current, on a single board.
</p>
<p align="center">
    <img src="https://img.shields.io/badge/Status-In%20development-green" alt="Status">
    <img src="https://img.shields.io/badge/Software-KiCad-blue" alt="KiCad">
    <img src="https://img.shields.io/badge/Firmware-C%2FC%2B%2B%20(Arduino)-orange" alt="Firmware">
    <br>
    <img src="https://img.shields.io/badge/Firmware%20licence-MIT-green" alt="MIT">
    <img src="https://img.shields.io/badge/Hardware%20licence-CERN--OHL--P-blue" alt="CERN-OHL-P">
</p>

---

### Overview

Chronos Ion is a fully open-hardware desk clock built as a from-scratch PCB exercise: every block — power, microcontroller, timekeeping, display and alarm — is designed and routed by hand in KiCad rather than assembled from dev boards.

The timekeeping is handled by a dedicated, temperature-compensated RTC, so the clock stays accurate to a few seconds per month and keeps the time on a coin-cell backup even when unplugged. The microcontroller takes care of the user interface and the alarm logic, talking to both the RTC and the display over a single shared I²C bus.

The board is designed to be:

- Accurate and stable over long periods.
- Easy to read, with a crisp OLED display.
- Simple to build, on a single USB-C-powered 5 V rail.
- Hackable and well-documented, as a learning reference for open hardware.

---

<h3 align="center">Contributing</h3>
<p align="center">
    ·
    <a href="./CODE_OF_CONDUCT.md">Code of Conduct</a>
    ·
    <a href="./CONTRIBUTING.md">Contributing Guide</a>
    ·
</p>
<p align="center">Collaboration from the open-hardware and embedded community is welcome. For major changes, please open an issue first to discuss what you'd like to change.</p>

<h3 align="center">License</h3>
<pre align="center">Copyright © 2026 Carmen &lt;your name or username&gt;<br><br>This is an open-hardware project released under two permissive licences:<br><br>Firmware &amp; documentation — MIT License<br>Hardware design files (KiCad) — CERN-OHL-P v2<br><br>See <a href="./LICENSE.md">LICENSE.md</a> for the full details.</pre>

<h3 align="center">Credits &amp; Team</h3>
<p align="center">Built and maintained by Carmen :)</p>
<p align="center">
    <a href="https://github.com/carmoruda/Chronos-Ion/graphs/contributors">
        <img src="https://contrib.rocks/image?repo=carmoruda/Chronos-Ion" width="50"/>
    </a>
</p>
