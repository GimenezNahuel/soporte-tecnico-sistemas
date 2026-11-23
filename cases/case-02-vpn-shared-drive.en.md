# Case #SYS-02: Shared Drive Access Failure During Remote Work (`INC0012847`)

* **Category:** Remote Connectivity / Network Resource Access[cite: 8, 11, 12]
* **Priority:** High[cite: 8]

## Context & Issue
Remote Marketing user `Sarah Mitchell` reported *"Network path not found"* when accessing the Marketing shared drive, while internet access and email worked normally[cite: 8].

## Troubleshooting & Resolution
1. Connected via **Remote Desktop** to workstation `SD1066`[cite: 10].
2. Checked the corporate **VPN Client** (`vpn.corp.local:443`, `IKEv2/IPSec`), finding it *Disconnected* / tunnel *Inactive*[cite: 11].
3. Connected the VPN client until the corporate tunnel status became *Connected*[cite: 12].

## Outcome
VPN connectivity to the corporate network restored and ticket `INC0012847` ready for closure with resolution notes[cite: 7, 8, 12].
