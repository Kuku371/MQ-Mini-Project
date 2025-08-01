---
layout: single
author_profile: false
classes: wide
---

<h2>Project Idea</h2>

This project examines how quantum computing can be utilized to optimize biking routes by minimizing distance and time while enhancing safety. It uses quantum algorithms, including the Quantum Approximate Optimization Algorithm(QAOA).

<h2>Background and Motivation</h2>

In today's world, biking has been increasingly promoted as a sustainable and healthy method of transportation. However, cyclists face many challenges when planning their routes. The shortest routes may not be the most efficient, and even the fastest routes may not be the safest for bikers. [According to Kartik Dixit of D-Wave Systems,](https://dwave.medium.com/optimizing-the-connected-world-with-quantum-897bbf452968) traditional algorithms for modeling this, such as Dijkstra's, take too much computation for large cities and countries, and therefore fail to adapt quickly to changes. The purpose of this project is to investigate whether or not quantum algorithms can help identify optimal routes more effectively than classical computation.

The motivation for this project comes from the fact that in the modern world, there is a growing need for smart cities with real-time route planning and other optimization problems. As quantum computers mature, we can use their capabilities to improve our transportation networks. [Quantum Zeitgeist has stated that](https://quantumzeitgeist.com/quantum-computing-in-transportation-quantum-route-optimization/) early simulations have shown promise in being able to identify high-risk areas better than classical algorithms.

This video from Quantum Tech for AI explains how quantum technology can be applied to common logistical optimization problems, including routing.
<iframe width="560" height="315" src="https://www.youtube.com/embed/-1M5nJ7qSrM?si=S9zaDBoW9RG8QGpM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<h2>Tools and Techniques</h2>

This project would require the use of graph theory to model different edges as common biking paths, which would be associated numerically with several costs and advantages. It would also need the mathematical knowledge of how qubits work to understand quantum states and gates.

One possible algorithm for constructing this project would be the Quantum Approximate Optimization Algorithm(QAOA). This starts by translating the problem into a form that computers can process. Then, the algorithm uses layers of cost and mixer Hamiltonians which encode and explore possible solutions through quantum gates. Finally, the quantum algorithm allows you to sample the best solutions.

Using these techniques, we would be able to first mathematically combine the different costs allocated to different routes on a bike path and use quantum algorithms to efficiently decide which paths are optimal. The project would likely also require Python and qiskit for quantum circuit design, as well as either OpenStreetMap(OSM) or Google Maps API for real-world biking and route data.

<h2>Goals</h2>

This project deeply connects to my long-term interest in both mathematics and quantum computing. My future goal is to tackle more challenging real-world problems, most of which are modelled mathematically, such as this one, using graphs. Quantum algorithms then allow for these problems to be efficiently solved, connecting them to my future aspirations. I find quantum algorithms especially interesting and hope to research them later in my life.

<h2>Reference</h2>

* D-Wave. “Optimizing the Connected World with Quantum.” Medium, Medium, 15 Mar. 2024, dwave.medium.com/optimizing-the-connected-world-with-quantum-897bbf452968. 
* Quantum Computing in Transportation: Quantum Route Optimization.” Quantum Zeitgeist, 18 Sept. 2024, quantumzeitgeist.com/quantum-computing-in-transportation-quantum-route-optimization/.
* Q-CTRL. “How Quantum Computers Can Improve Logistics Problems | Australian Army.” YouTube, 21 Feb. 2024, www.youtube.com/watch?v=-1M5nJ7qSrM. Accessed 25 July 2025.
‌
