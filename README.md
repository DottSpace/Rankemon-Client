# Rankemon Client

Rankemon is a comprehensive, feature-rich desktop client built with Python and PyQt6 designed specifically for Generation III Pokémon games. It bridges local gameplay with a global online ecosystem by seamlessly embedding an emulator, tracking game progress in real-time, and synchronizing trainer profiles to a backend leaderboard.

The project is in **constant development and continuous updating**, introducing new features, performance enhancements, and regular optimizations to ensure the best possible trainer experience.

## Key Features

* **Advanced Emulator Embedding:** Integrates `VBA.exe` directly into the PyQt6 dashboard layout, removing window borders, stripping standard menus, and dynamically resizing the game window inside the user interface.
* **Real-Time Save File Synchronization (`SaveWatcher`):** Utilizes a dedicated background thread to monitor `.sav` file modifications, automatically parsing trainer names, active teams, PC storage boxes, and exact playtimes to sync data instantly with the server.
* **Dynamic Game Selection & Locking:** Scans a local `Roms/` directory for `.gba` files, allows users to choose their game, and locks the selected game to their account upon confirmation.
* **Interactive Control & Settings Manager:** Provides quick access to configure emulator key bindings and custom inputs directly through built-in menu triggers and warning prompts.
* **Bilingual Localization:** Complete native support for both English and Italian languages, with dynamic runtime language switching and persistent session saving.
* **Custom Pokémon Dark Theme:** A polished, modern dark user interface styled with classic Pokémon color accents (dark charcoal `#0d1117`, vibrant red `#ee1515`, and signature yellow `#ffcb05`), drop shadows, smooth opacity animations, and custom progress bars.

## How to Download and Install

1. **Clone or Download the Repository:**
   Download the project files directly from GitHub or clone the repository using Git:
   ```bash
   git clone [https://github.com/your-username/rankemon-client.git](https://github.com/your-username/rankemon-client.git)
   cd rankemon-client
