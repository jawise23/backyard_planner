# Backyard 3D Planner

A simple backyard design tool built with Rust and Bevy, inspired by early versions of The Sims. The planner allows you to place and arrange backyard elements like sheds, decks, retractable batting cages, and privacy fences in a grid-based 3D environment.

## License
This project is licensed under the GNU Affero General Public License v3.0 (AGPL-3.0).
You are free to use, modify, and distribute this project, provided that any derivative works or services built upon it are also released under the AGPL-3.0 license.

## Features (MVP)
- Grid-based backyard layout
- Place and move objects (Shed, Deck, Batting Cage, Fence)
- Rotate objects
- Basic UI for object selection
- Save and load designs

## Future Features
- Fence auto-layout tool
- Animated retractable batting cage
- Simple material textures
- Collision detection for overlapping objects
- Export design as an image

## Tech Stack
- Rust
- Bevy (Game Engine)
- bevy_mod_picking (Object Interaction)
- bevy_egui (UI)

## Getting Started
### Prerequisites
- Rust (https://rustup.rs/)

### Run the Project
```bash
cargo run
