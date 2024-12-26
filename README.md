Here's a proposal for the README in English:

---

# CodePeak - Script for Hiding License Plates in FiveM

## Description

**CodePeak** is a script for the **FiveM** platform that allows players to temporarily hide the license plates of their vehicles. The script includes features such as NPC interaction and configurable timers for plate concealment. 

## Features

- **NPC Interaction**: Spawn an NPC that can be used to initiate plate-hiding actions.
- **Vehicle Selection Menu**: Choose a nearby vehicle from a user-friendly interface.
- **Plate Concealment**: Temporarily hide the license plate of a vehicle, with configurable duration.
- **Dynamic Notifications**: Inform the player of concealment status and cooldown times.
- **Optimized Performance**: Lightweight script with minimal impact on server and client performance.

## Requirements

This script requires the following dependencies:
- [`es_extended`](https://github.com/esx-framework/esx_core)
- [`ox_target`](https://github.com/overextended/ox_target)

## Installation

1. Download or clone this repository.
2. Add the `cp_fakeplates` folder to your FiveM server's `resources` directory.
3. Ensure the following dependencies are installed:
   - `es_extended`
   - `ox_target`
4. Add `start CodePeak` to your `server.cfg` file.
5. Configure the script (optional) by editing the `config.lua` file to customize NPC models, cooldowns, and concealment duration.

## Usage

1. Interact with the NPC spawned at a specific location to access the license plate hiding service.
2. Use the menu to select a nearby vehicle for plate concealment.
3. The plate will be hidden temporarily, with notifications informing the player of remaining time.

## Configuration

Key settings can be adjusted in the `config.lua` file:
- **NPC Model**: Change the model of the NPC.
- **Concealment Duration**: Adjust how long the license plate remains hidden.
- **Cooldown Time**: Set the cooldown duration for reusing the service.


## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
