# Plants vs Zombies - Java Implementation

Tower defense game featuring strategic plant placement and zombie wave management.

---

## Overview

A complete Java implementation of the Plants vs Zombies strategy game. Players defend against waves of zombies by strategically placing defensive plants on a grid-based battlefield. Features real-time collision detection, game state management, and turn-based mechanics.

---

## Technologies & Concepts

**Object-Oriented Design:** Inheritance hierarchies for plant/zombie entities, polymorphic behavior, encapsulation  
**Game Architecture:** Game loop, event handling, sprite management, state transitions  
**Graphics & UI:** Java Swing/AWT rendering, animation frames, resource management  
**Data Structures:** Grid-based collision system, entity management, wave queuing  
**Game Mechanics:** Turn-based planning, resource management (sunlight), pathfinding, win/lose conditions

---

## Project Structure

```
├── src/
│   ├── entities/          # Plant & Zombie classes
│   ├── game/             # Game engine & state management
│   ├── graphics/         # Rendering & UI components
│   └── Main.java         # Entry point
├── gfx/                  # Game sprites & assets
├── sfx/                  # Sound effects
└── resources/            # Configuration files
```

---

## Key Features

✓ Grid-based plant placement strategy  
✓ Dynamic zombie wave progression  
✓ Real-time collision & damage detection  
✓ Sunlight economy resource system  
✓ Multiple plant types with unique abilities  
✓ Audio & visual feedback system  

---

## Game Mechanics

**Strategic Plant Defense:**
Players place plants on a 5x9 grid lawn to defend against advancing zombies. Each plant has unique abilities: Peashooter attacks horizontally, Sunflower generates resources, Walnut blocks zombie passage, Squash eliminates single targets. Planning and positioning are critical to survival.

**Sunlight Economy:**
The core resource mechanic. Sunflowers produce sunlight passively; flowers from Sunflower plants provide additional resources. Players must balance spending on defensive plants versus investing in sunlight generation for sustained gameplay.

**Wave-Based Progression:**
Zombies spawn in waves with increasing difficulty. Early waves feature basic zombies; later waves introduce specialized types (Buckethead with armor, Pole Vaulter that jumps, Dolphin Rider on water lanes). Players must adapt strategy to each wave composition.

**Collision & Damage System:**
Real-time pathfinding for zombies moving horizontally down lanes. Plants detect proximity and attack automatically. Zombies damage plants on contact; plants deal area or single-target damage. Strategic plant placement determines survival.

**Victory Condition:**
Survive all zombie waves without breaching the house (right boundary). Prevent any zombie from reaching the home.

---

## Installation & Compilation

**Requirements:** Java 8+

```bash
# Compile
javac src/*.java

# Run
java -cp .:gson-2.8.6.jar:SoundPlayer.jar Main
```

---

## Skills Demonstrated

**Object-Oriented Programming:** Class hierarchies, inheritance, polymorphism, encapsulation  
**Game Development:** Game loops, event handling, collision detection, state management  
**Graphics Programming:** Sprite rendering, animation, UI components  
**Software Architecture:** Design patterns, separation of concerns, entity management  
**Java Programming:** Swing/AWT, threading, resource management, exception handling

---

## Author

**Aroutin Nazarian**