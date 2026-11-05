# SDK — INSTRUMENT.SMU

Every SMU model this library drives, and how to drive it. Each model answers the same five verbs over HTTP (its own port), WebSocket, a Unix socket and the bus; one page per model below lists its routes and every command.

← [Manual and Artifacts](INDEX.md)

| Verb | What it does |
|---|---|
| `get` | reads one value |
| `set` | writes one value |
| `nab` | reads more than one thing (observation, telemetry) |
| `rig` | configures several arguments at once |
| `do` | executes an action; takes no value |

| Model | Maker | get | set | nab | rig | do | Port |
|---|---|---:|---:|---:|---:|---:|---:|
| [2400](SDK/2400.md) | Keithley | 8 | 9 | 8 | 2 | 6 | 16100 |
| [2410](SDK/2410.md) | Keithley | 8 | 9 | 8 | 2 | 6 | 16101 |
| [2420](SDK/2420.md) | Keithley | 8 | 9 | 8 | 2 | 6 | 16102 |
| [2425](SDK/2425.md) | Keithley | 8 | 9 | 8 | 2 | 6 | 16103 |
| [2430](SDK/2430.md) | Keithley | 8 | 9 | 8 | 2 | 6 | 16104 |
| [2450](SDK/2450.md) | Keithley | 8 | 9 | 8 | 2 | 6 | 16105 |
| [2460](SDK/2460.md) | Keithley | 8 | 9 | 8 | 2 | 6 | 16106 |
| [2461](SDK/2461.md) | Keithley | 8 | 9 | 8 | 2 | 6 | 16107 |
| [2601B](SDK/2601B.md) | Keithley | 8 | 9 | 8 | 2 | 6 | 16108 |
| [2602B](SDK/2602B.md) | Keithley | 8 | 9 | 8 | 2 | 6 | 16109 |
| [2611B](SDK/2611B.md) | Keithley | 8 | 9 | 8 | 2 | 6 | 16110 |
| [2612B](SDK/2612B.md) | Keithley | 8 | 9 | 8 | 2 | 6 | 16111 |
| [2635B](SDK/2635B.md) | Keithley | 8 | 9 | 8 | 2 | 6 | 16112 |
| [2636B](SDK/2636B.md) | Keithley | 8 | 9 | 8 | 2 | 6 | 16113 |
| [B2901A](SDK/B2901A.md) | HP / Agilent / Keysight | 8 | 9 | 8 | 2 | 6 | 16114 |
| [B2902A](SDK/B2902A.md) | HP / Agilent / Keysight | 8 | 9 | 8 | 2 | 6 | 16115 |
| [B2912A](SDK/B2912A.md) | HP / Agilent / Keysight | 8 | 9 | 8 | 2 | 6 | 16116 |
| [E5270B](SDK/E5270B.md) | HP / Agilent / Keysight | 8 | 9 | 8 | 2 | 6 | 16117 |
