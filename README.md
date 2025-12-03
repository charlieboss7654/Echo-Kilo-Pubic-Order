# EKS Public Order

A clean, modern, and fully configurable flame-protection system for FiveM - built for immersive roleplay, operational realism, and seamless UI integration using the EKS visual style.

## Features

### **True Flame Protection System**

Players wearing any configured uniform piece become flame-retardant:

* They visually catch fire
* They take **zero** heat damage
* A custom integrity bar drains over time
* A burn-out prompt appears:
  **Press [Key] to extinguish yourself**

### **Full Uniform Configuration**

Define full uniforms per kit, including:

* Tops
* Pants
* Shoes
* Props
* Custom textures

Only **one** configured piece (e.g., shirt OR pants) is required to activate protection.

### **Vehicle-Based Uniform Replacement**

Players may replenish (restore) kit integrity by interacting with configured emergency vehicles, using:

* Third-eye selection
* A sleek EKS-style uniform picker menu

### **Realistic Damage Handling**

While protected:

* Fire damage is completely blocked
* Bullet & impact damage is reduced (configurable)

When integrity reaches 0%:

* Player loses immunity
* Burning deals real damage again

### Customizable UI

Includes custom EKS-themed UIs:

* Uniform Integrity Bar
* Flame Extinguish Prompt
* Uniform Selection Menu
* Moveable UI bar (`/movekitbar`)

All styles match the modern EKS visual theme.

### Fully Configurable

Modify everything from:

* Uniforms
* Damage scaling
* Drain speed
* Keybinds
* Vehicles that supply uniforms
* UI placement

No framework dependencies, lightweight and clean.


## Installation

1. Drop the resource into your `resources/` folder:

resources/EKS_PO

2. Add to your `server.cfg`:

ensure EKS_PO


3. Configure your uniforms, vehicles, and behaviour inside:

   shared/config.lua

4. Restart your server.

## Support

For help, issues, or suggestions, please join our Discord and open a support ticket:

https://discord.gg/busQ9w6dqa

