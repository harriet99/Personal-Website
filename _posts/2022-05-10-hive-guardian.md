---
title: "Hive Guardian"
layout: post
date: 2022-05-10 22:44
image: /assets/images/markdown.jpg
headerImage: false
star: true
projects: true
---

<div style="text-align: center;">
  <a href="https://github.com/harriet99/Tower-Jackets">GitHub</a>
</div>

## Introduction

I decided to create a **Power Defense Game**—a tower defense style mobile game developed in **Java** using **Android Studio**. This project served as a comprehensive exploration of game design principles, programming techniques, and user experience testing.

## Why a Tower Defense Game?

I think tower defense games offer a unique blend of strategy, resource management, and spatial reasoning. By choosing this project, I aimed to:

* Learn how to structure a larger-scale Android application beyond simple layouts.
* Explore game development frameworks and the Android lifecycle for rendering and updates.
* Enhance my understanding of object-oriented programming principles by implementing various game entities.
* Develop a fun, interactive project that I could share with others and iterate on.

## Core Skill Sets Utilized

Throughout the development process, I relied heavily on:

1. **Java Programming**:  
   Implementing game logic, object-oriented design patterns, and managing data structures for enemies, towers, and game states.
   
2. **Android Studio & Android Framework**:  
   Designing interactive UI screens, handling user input, managing the activity lifecycle, and rendering game elements.
   
3. **Game Loop and Rendering**:  
   Creating a consistent and efficient update-render loop, ensuring smooth game performance on mobile devices.
   
4. **Resource Management**:  
   Handling assets such as images, sound effects, and screen configurations for different devices.
   
5. **Testing and Debugging**:  
   Using Android emulators and real devices for testing gameplay, debugging performance issues, and refining the user experience.

## How the Game Works

At a high level, this tower defense game tasks the player with defending a hive (the "monument") from incoming enemies that travel along a predefined path. Players start with a certain amount of currency (coins) and must strategically place towers to prevent enemies from reaching the hive. If too many enemies reach the end and the hive’s health drops to zero, the player loses.

### Game Flow

1. **Welcome & Configuration Screen**:  
   On startup, the player is greeted with a welcome screen that allows them to:
   - Start the game.
   - Quit the application.
   
   After starting, the player must enter their name (no empty names allowed) and choose a difficulty level. Difficulty affects:
   - Starting money.
   - Hive (monument) health.
   - Tower costs.

2. **Game Screen Setup**:
   Once configured, the player is shown the initial map:
   - Displays the path enemies will follow.
   - Shows the hive’s health and starting money.
   
3. **Buying & Placing Towers**:
   Players can buy three types of towers, each with a unique benefit:
   - **Bee Tower**: Attacks enemies within range, decreasing their health.
   - **Heart Tower**: Boosts the hive's health, increasing survivability.
   - **Coin Tower**: Generates additional coins over time, increasing the player’s available resources.
   
   The player must ensure towers are placed off the path. Towers cannot be placed without sufficient funds, and tower costs vary by difficulty.

4. **Starting Combat**:
   After placement, the player can start combat. Enemies appear at the start of the path and move towards the hive. When an enemy reaches the hive, the hive’s health decreases.

5. **Combat & Enemy Interactions**:
   - **Attacking**: Bee Towers automatically attack enemies within range. As enemies lose health, they eventually disappear when their health reaches zero.
   - **Resource Gain**: Coin Towers periodically grant more coins, allowing further expansion of defenses.
   - **Upgrades**: Towers can be upgraded to improve their stats (e.g., Bee Tower can get increased range or damage).
   
6. **Victory & Defeat**:
   - Over time, a **final boss** enemy appears, tougher than all previous ones. Defeating this boss leads to a victory screen, showing game statistics and allowing a restart.
   - If the hive’s health reaches zero, the player is shown a game over screen with statistics and the option to restart.

## Demonstration

### Video Demo

Check out the gameplay demo here:
<iframe width="560" height="315"
src="https://www.youtube.com/embed/qmmNwiEN9Uo"
title="YouTube video player"
frameborder="0"
allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
allowfullscreen>
</iframe>

## Challenges & Lessons Learned

**Challenges**:
* Balancing enemy health, tower damage, and coin generation to ensure the game is fun and not too easy or too hard.
* Handling device compatibility and performance optimizations, ensuring smooth rendering and animations.
* Creating a user-friendly interface that clearly communicates game state, health, money, and other resources.

**Lessons Learned**:
* **Modularity & OOP Practices**: Maintaining clean code with modular classes for enemies, towers, and UI screens made it easier to extend the game.
* **User Experience Importance**: Simple interfaces and clear visual feedback significantly improve player engagement.
* **Iterative Design**: Repeated testing and feedback helped refine difficulty settings, improve tower placement UX, and enhance the upgrade system.

## Conclusion

This tower defense project was a rewarding experience that combined programming, design, and user experience considerations. I learned a great deal about structuring a game loop, managing resources, and providing meaningful visual feedback to the player. The final result is a playable and (I hope) enjoyable tower defense game that I can continue to refine and build upon in the future.

If you’re interested, give the demo a watch, or try it out if it becomes available. Thanks for reading!