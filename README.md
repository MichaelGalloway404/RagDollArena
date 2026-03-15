# RagDollArena

**RagDollArena** is a 2D physics-driven combat game built in **Unity using C#**. The project explores procedural animation and physics-based character control by using ragdoll puppets instead of traditional keyframe animation.

In the game, characters are composed of physically simulated limbs connected through anchors. Animations are performed by applying rotational targets to these joints, allowing the environment and physics interactions to influence each movement dynamically. This creates combat encounters that are unpredictable, and reactive to the environment.

The objective is simple: **defeat as many enemies as possible before being defeated**.

**Play the game:**
https://michaelgalloway404.github.io/RagDollArena/

---

## Features

* **Physics-Driven Animation**

  * Characters are built as ragdoll puppets composed of physical limbs connected by anchors.
  * Movement and attacks are driven by rotational targets applied to joints rather than pre-made animations.
  * Environmental forces can influence or interrupt actions.
  * Limbs can also be broken and un usable making combat more difficult
  * Player can heal and can aquire healing tokens form defeated enemies

* **Directional Combat System**

  * Attacks are performed using directional input.
  * Different key combinations trigger different attack motions.
  * The physics-based animation system allows combat to feel dynamic and reactive.

* **Procedural Interaction**

  * Character motion adapts to collisions and environmental physics.
  * Limbs can be obstructed or redirected by terrain or enemy contact.

* **Arcade Survival Gameplay**

  * Fight waves of enemies.
  * Score is determined by how many opponents you defeat before falling.

* **Original Assets**

  * All art assets created from scratch.
  * Sound effects aslo from scratch.
  * Background music created by remixing public-domain compositions.

---

## Technologies Used

* **Unity Game Engine**
* **C#**
* **2D Physics System (Rigidbody2D, Joint Anchors)**
* **Custom Procedural Animation System**

---

## Controls

| Key                          | Action                      |
| ---------------------------- | --------------------------- |
| Arrow Keys                   | Move                        |
| Directional Inputs and Z Key | Perform directional attacks |
| X Key                        | Jumps                       |
| C Key                        | Throws Rocks                |
| I Key                        | Displays Gameplay Info      |

---

## Project Goals

This project was created to explore:

* Procedural animation techniques
* Physics-driven character systems
* Input-driven combat mechanics
* Unity's 2D physics engine

---

## Author

**Michael Galloway**

If you enjoy experimental physics-based gameplay or are interested in procedural animation techniques, feel free to try the game and explore the code.
