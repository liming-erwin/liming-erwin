## Liming Erwin Saputra

iOS engineer — Swift and SwiftUI, from SwiftData and CoreBluetooth down to the firmware on the other end of the wire.

Three team projects, built between April and August 2026. The share-of-code figures come from `git blame -w -M` against each shipping branch, counting lines that survived into the final build.

| Project | What it is | Commits | Share of code |
|---|---|---|---|
| **[Oren](https://github.com/liming-erwin/Oren)** | Fruit-grading QC — iPad + ESP32 over BLE | 3 / 5 | **89%** · 4,307 / 4,851 |
| **[Hijauin](https://github.com/liming-erwin/Hijauin)** | Volunteering program discovery | 71 / 104 | **66%** · 3,105 / 4,709 |
| **[REFRM](https://github.com/liming-erwin/refrm)** | Padel stroke-form coach | 14 / 26 | **47%** · 642 / 1,367 |

**Oren** — I built the data-source abstraction that lets the whole app run without the hardware rig attached: one protocol, a CoreBluetooth implementation and a mock one, with a sync engine as the only consumer. Also the SwiftData schema, the iPad interface, and the architecture documentation. *In progress.*

**Hijauin** — Owned Profile, My Events, the join/cancel flow, and the data layer. Ran a SwiftUI modernization pass across 23 files (`@Observable`, value-based navigation, accessibility). Merged 21 of the project's 23 pull requests.

**REFRM** — Owned the training interface and its state layer, 100% of the home and session-configuration screens. A teammate built the Vision 3D pose-detection layer; I integrated against it.

### Working with

`Swift` `SwiftUI` `SwiftData` `CoreBluetooth` `Vision` `AVFoundation` `Swift Charts` `XcodeGen` `ESP32 / Arduino C++`

### Contact

- **GitHub** — [@liming-erwin](https://github.com/liming-erwin)
- **Email** — limingerwin@gmail.com
- **LinkedIn** — [liming-erwin-saputra](https://www.linkedin.com/in/liming-erwin-saputra/)
- **Portfolio** — [Project breakdown](https://claude.ai/code/artifact/524fc61a-7cee-4e12-95e3-e47553b16820)
