# Cycle Cast Spells (CC) for Aardwolf MUD

Create and manage custom combat rotations. Perfect for cycling through different elemental damage types, maintaining debuffs, or automating complex spell sequences with a single keypress.

## 🌟 Key Features
- **Grouped Rotations:** Create as many rotation groups as you want (e.g., `f` for fire, `d` for debuffs, `s` for stuns).
- **Targeting Support:** Use `ccx` to cast your next rotation spell on a specific mob, or use `cc` to fire at your current target.
- **Visual Feedback:** The `cc list` command shows your full rotation path and highlights the spell that is "up next" in brackets.
- **Smart Logic:** The plugin automatically handles spell names with spaces and remembers your position in every rotation even after a disconnect.

## ⌨️ Common Commands

| Command | Description |
| :--- | :--- |
| `cc add <spell> <group>` | Add a spell to a specific rotation list. |
| `cc <group>` | Cast the next spell in that group's cycle. |
| `ccx <group> <target>` | Cast the next spell on a specific mob/player. |
| `cc list` | View all your saved rotations and current positions. |
| `cc rem <spell> <group>` | Remove a specific spell from a rotation. |
| `cc clear <group>` | Wipe an entire rotation group clean. |

## 💡 Examples
1. **Elemental Rotation:**
   `cc add fireball f` -> `cc add 'ice blast' f` -> `cc add 'lightning bolt' f`
   Now, just spam `cc f` to cycle through all three elements.
   
2. **Boss Opener:**
   `cc add 'blind' debuff` -> `cc add 'curse' debuff` -> `cc add 'faerie fire' debuff`
   Start the fight with: `ccx debuff dragon`

---
*Developed by Khrysis for Aardwolf MUD.*
