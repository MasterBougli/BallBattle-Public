# BallBattle Bans Repository

This repository stores the official ban list for the BallBattle game.

## ⚠️ Warning
This file is updated automatically by the game administration tools. Do not modify this file manually unless you are an authorized administrator.

## Configuration
The game client fetches the `Bans.json` file from the `main` branch via the raw URL:
`https://raw.githubusercontent.com/MasterBougli/BallBattle-Public/refs/heads/main/Bans.json`

## Usage
- **Ban Entry Format**:
  ```json
  {
    "steamId": "STEAM_ID_64",
    "reason": "Reason for ban",
    "timestamp": "YYYY-MM-DD",
    "expire": 0
  }
  ```
- **Expire**: Set to `0` for permanent bans.
