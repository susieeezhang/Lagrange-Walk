# Lagrange Walk — Balance Points as Level Design
*(IMDM 327 — Fall 2025 Final Project Proposal)*

## Elevator Pitch
Lagrange Walk is a calm, dream like VR exploration inspired by the balance of gravity in space.  
You move through a cluster of floating planets, each with its own pull, so “down” is never the same twice.  
Between those worlds are strange pockets of stillness, the Lagrange points, where gravity from different bodies perfectly cancels out.  
Drifting into one feels weightless and quiet, like standing inside the pause between two heartbeats.  

These balance zones become stepping-stones through the world.  
Shift a nearby moon, and the forces rebalance, opening a new route.  
Soft ribbons of light and drifting particles reveal how gravity flows around you, while gentle ambient sounds rise and fade with the field’s strength.  
It’s both science and poetry — a space about motion, equilibrium, and learning to trust instability.  

Technically, the project simulates multi-source gravity by summing forces from each planet, detects near-zero-force zones for Lagrange regions, and visualizes them with GPU driven particles in real time.  
Comfort features gradually realign the camera’s up vector and ease transitions so the player can enjoy the shifting orientation without discomfort.  
In short, Lagrange Walk invites you to lose and rediscover your sense of “down.”  


## Seminar Proposal
**Title:** Simulating Multi-Source Gravity & Equilibrium Points in Unity VR  

This seminar explores how to simulate and visualize custom gravity in Unity for immersive worlds. I’ll demonstrate summing vector forces from multiple bodies, detecting equilibrium regions where net acceleration ≈ 0, and rendering these fields with GPU particles or VFX Graph for clarity. The session also covers comfort strategies for changing up vectors in VR and provides a reusable GravitySource component so classmates can integrate multi body physics into their own XR projects.

