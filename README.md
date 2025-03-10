# Arma 3 Mission Files for Exile Mod

This repository contains custom mission files for the Arma 3 Exile Mod using **Defent's Mission System (DMS)** and **Zupa's Capture Points (ZCP)** frameworks.

## 📂 Repository Structure

```plaintext
Exile.YourMap/
│
├── a3_dms/
│   ├── x/addons/DMS/
│   │   ├── Missions/
│   │   │   ├── static/
│   │   │   │   ├── example_static_mission.sqf
│   │   │   │   └── ...
│   │   │   └── dynamic/
│   │   │       ├── example_dynamic_mission.sqf
│   │   │       └── ...
│   │   └── Scripts/
│   │       ├── custom_script.sqf
│   │       └── ...
│   └── Configs/
│       ├── dms_config.sqf
│       └── ...
│
├── a3_zcp_exile/
│   ├── x/addons/ZCP/
│   │   ├── CapturePoints/
│   │   │   ├── example_capture_point.sqf
│   │   │   └── ...
│   │   └── Configs/
│   │       ├── zcp_config.sqf
│   │       └── ...
│   └── Scripts/
│       ├── zcp_custom_script.sqf
│       └── ...
│
└── Documentation/
    ├── HowToIntegrate.md
    ├── MissionEditingGuidelines.md
    └── README.md

Getting Started

    Clone the Repository:
    git clone https://github.com/Spacebar-DevTeam/arma3-mission-files.git

Setup on Server:

    Place the Exile.YourMap folder into your Arma 3 server's mission directory.
    Configure DMS and ZCP settings as needed.

Testing & Debugging:

    Launch the server and monitor logs for errors.
    Test missions through server tools or manually spawn them.

Development Guidelines

    Do Not Edit core DMS or ZCP files directly.
    Use the provided Missions and CapturePoints directories for custom missions.
    Follow the guidelines in MissionEditingGuidelines.md for scripting standards.

Support & Contribution

    Open an issue for bugs or feature requests.
    See CONTRIBUTING.md for how to contribute.
