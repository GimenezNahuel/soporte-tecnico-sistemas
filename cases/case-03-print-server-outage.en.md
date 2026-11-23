# Case #SYS-03: Office-Wide Printing Service Outage (`INC0012870`)

* **Category:** Server Infrastructure / Incident Management[cite: 20, 21, 22, 24]
* **Priority:** High[cite: 24]

## Context & Issue
Legal user `Dorothy Martinez` (Floor 2) reported that no office printers worked and all printers appeared offline across floors, blocking contract and presentation printouts[cite: 24].

## Troubleshooting & Resolution
1. Messaged the user via **Company Chat** to confirm investigation of ticket `INC0012870`[cite: 19].
2. Checked **Server Room** nodes (`DC01`, `DC02`, `FILESERV01`, and `EXCH01` *Online*), finding Print Server **`PRINT01`** *Degraded* with high utilization (95% CPU, 90% memory)[cite: 20].
3. Triggered a **Restart** on `PRINT01`[cite: 21].
4. Verified `PRINT01` returned to *Online* and confirmed via chat with the user that printing worked again[cite: 22].

## Outcome
Printing service recovered and verified by the user to close ticket `INC0012870`[cite: 22, 24].
