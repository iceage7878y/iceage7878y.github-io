---
title: Configuration
parent: Ice_jobgarage
---

# Configuration

All configuration is done inside `config.lua`.

## Example
```lua
Config.Garages = {
    police = {
        coords = vector3(450.1, -975.5, 30.6),
        vehicles = { "police", "police2" }
    }
}
```

You can configure:
- Jobs
- Vehicles per job
- Garage locations
