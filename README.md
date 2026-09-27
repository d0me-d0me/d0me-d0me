<div align="center">

<img src="./banner.svg" width="900" alt="d0me — offensive & defensive security">

</div>

Field notes from both sides of security — offensive and defensive. Originally
a notebook for myself, published in case someone stuck on the same problem
finds a shortcut.

攻撃・防御両面の実務ノート。ラボ・CTF・公開 CVE の再現を通じた記録。

---

### Site — two surfaces

- **Notes** (blog) — longer articles on why a technique matters, where it works,
  its limits, and how the two sides read the same event. Lab / CTF writeups and
  disclosed-CVE reproductions land here too.
- **Refs** — terminal-style cheat sheets built for quick lookup during practice.

Both split across the same three domains: `Offensive` · `Defensive` · `Other`.

Start here → https://d0me-d0me.github.io

### Coverage

- **Offensive** — enumeration, Active Directory, privilege escalation, lateral
  movement, web, evasion / C2, file transfer.
- **Defensive** — Linux hardening, forensics & IR.
- **Other** — reporting.

Every offensive technique carries its detection and mitigation side; every
defensive one is read back from the operator's view.

The offensive sheets track the ground OffSec (`OSCP` · `OSEP`) and Hack The Box
(`CPTS`) exams and lab paths cover — from enumeration through Active Directory
compromise to evasion and C2 — so they double as prep references for those.

列挙・AD・権限昇格・横展開・web・回避 / C2、そして Linux 強化・フォレンジック / IR。
各手法に攻撃と防御、双方の観点を併記している。
攻撃側のシートは OffSec (OSCP · OSEP)・Hack The Box (CPTS) の試験・ラボが扱う範囲を
意識して整理しており、これらの対策リファレンスとしても使える。

### Focus

`AD exploitation` · `AV/EDR evasion` · `process injection`
`AMSI / CLM bypass` · `lateral movement` · `C2 ops` · `custom C#/.NET tradecraft`
— with the defender's view (detection, artefacts, hardening) kept alongside.

### Certifications

- `OSCP` — OffSec
- `OSEP` — OffSec
- `CPTS` — Hack The Box
- `SAL1` — TryHackMe
- `CySA+` — CompTIA
- `CCNA` — Cisco

### Repositories

- [`d0me-d0me.github.io`](https://github.com/d0me-d0me/d0me-d0me.github.io) — source for the field notes + references site

---

<sub>我以外皆我師 — everyone I meet has something to teach me.</sub>
