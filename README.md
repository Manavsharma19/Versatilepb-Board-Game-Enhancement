# Versatilepb-Board-Game-Enhancement

This project modifies a basic game for the versatilepb board to add user-controlled defender movement, collision detection, and sprite updates. It demonstrates advanced C programming skills and embedded systems expertise.

Technologies and Tools Used:

**Programming Language**: C  
**Platform**: ARM-based versatilepb board  
**Emulator**: QEMU  
**Concepts**: Interrupt-driven programming, sprite management, and collision detection  


Key Features:

**User-Controlled Defender:**
Use s, d, e, w keys to move the defender while respecting screen boundaries.
Defender sprite dynamically changes direction (left/right) based on movement.  
**Collision Detection:**
Implemented logic to detect projectile-land collisions.
Landers are disabled upon a successful hit.  
**Real-Time Updates:**
Utilized interrupts for keyboard input and rendering updates.
Ensured smooth gameplay with real-time sprite rendering and state transitions.


