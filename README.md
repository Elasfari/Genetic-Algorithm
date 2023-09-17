![images](https://github.com/3mrology/Genetic_Algorithm_AIS201/assets/96602046/44b1b66b-d507-4ef8-85f8-7d64072df336)

*Nile University | AIS201: Artificial Intelligence-2023SPRG*

*Team Members: Amr Shaarawy, Yassin Elasfar, Abdallah Emam , Omar Hazzaa, Youssef Abdelmaksoud*

**Introduction:**
The "Car Racing Using Genetic Algorithm" project, undertaken as part of the AIS201: Artificial Intelligence-2023SPRG course at Nile University, showcases the practical application of genetic algorithms in the field of artificial intelligence. Genetic algorithms, inspired by the process of natural selection, are employed to optimize the performance of AI-controlled cars in a racing game scenario.

**Genetic Algorithm Overview:**
A genetic algorithm, a metaheuristic optimization technique, constitutes the foundation of this project. Key components such as selection, crossover, and mutation are harnessed to drive the evolution of car populations. The algorithm seeks to enhance the capabilities of AI cars in navigating a challenging track, marked by walls and checkpoints, while making intelligent decisions to efficiently reach designated points.

**Problem Statement:**
The primary objective of this project is to implement an AI-controlled car racing game that demonstrates the potential of genetic algorithms in enhancing decision-making and performance. The problem entails designing AI cars that autonomously maneuver through a track featuring walls and checkpoints. These AI cars are tasked with identifying the nearest checkpoint, computing optimal angle and velocity for reaching the checkpoint, and dynamically adjusting their position and orientation based on the calculated values. A visually immersive representation of the track, including walls and AI cars, is provided to enhance user engagement.

**Technical Components:**
The project's technical architecture encompasses various elements:

1. **Libraries:** The project employs essential libraries such as pygame, math, random, os, and the Image class from the PIL module, which provide the necessary tools for graphics rendering, mathematical calculations, and image manipulation.

2. **Variables:** Crucial variables define the game environment, including window dimensions, pixel size, tile specifications, frames per second, and color schemes. Variables such as track positions, tree density, and the number of AI-controlled cars are used to configure the game dynamics.

3. **Track and Checkpoint Design:** The code generates a structured track layout using a 2D list. Checkpoints, integral to the game's challenge, are identified by specific coordinates.

4. **Starting Position:** The algorithm locates the starting position for the cars by identifying appropriate tiles within the track layout. The initial orientation angle is set to 0 degrees.

5. **Image Loading:** The game loads diverse images, including ground and wall tiles, along with the car sprite, to create an immersive visual experience for players.

6. **Car Object:** The project defines a comprehensive car class encapsulating attributes and methods that dictate the car's behavior. The class handles acceleration, deceleration, turning, collision detection, checkpoint management, scoring, and visual representation.

7. **Biased Random Functions:** Biased random number generation introduces controlled randomness, influencing a specific range of values. This contributes to the diversity of car behaviors during the optimization process.

8. **Mutation Function:** The mutation function introduces random variations in the AI cars' decision-making brains, contributing to genetic diversity and aiding evolutionary progress.

9. **New Generation Transition:** The transition from one generation to another involves the sorting of cars based on their performance scores. Top-performing cars are selected, mutated, and replenished to form the next generation, driving continuous improvement.

10. **Main Loop:** The project's main loop orchestrates the simulation, updating car positions and scores, responding to user inputs, and maintaining a controlled frame rate for smooth gameplay.

**Conclusion:**
In conclusion, the "Car Racing Using Genetic Algorithm" project exemplifies the convergence of genetic algorithms, artificial intelligence, and gaming in a comprehensive application. By iteratively evolving AI-controlled cars through genetic operations and neural networks, the project not only demonstrates the optimization potential of genetic algorithms but also showcases the power of AI-driven decision-making in the context of autonomous racing. Through this endeavor, the team members at Nile University have underscored the synergy between theoretical concepts and practical implementations in the realm of artificial intelligence.
