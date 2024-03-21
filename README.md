<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UAV Path Planning for Cellular Traffic Handling</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>🚁 UAV Path Planning for Cellular Traffic Handling 📡</h1>
        <p>This repository contains code for optimizing Unmanned Aerial Vehicle (UAV) path planning to efficiently handle cellular traffic. The goal is to find an optimized path for UAV deployment, considering obstacles (such as cell towers) and the source-destination points.</p>
        
        <h2>🔧 Features:</h2>
        <ul>
            <li>Particle Swarm Optimization (PSO): Utilizes PSO algorithm to iteratively optimize the UAV path.</li>
            <li>Obstacle Avoidance: Incorporates obstacle avoidance strategy to navigate around obstacles.</li>
            <li>Visualization: Provides visualization tools to plot the optimized path and obstacles.</li>
        </ul>
        
        <h2>📈 How it Works:</h2>
        <ol>
            <li>Initialization: Initialize PSO parameters and particle positions.</li>
            <li>Optimization Loop: Iteratively update particle positions and velocities using PSO equations.</li>
            <li>Cost Evaluation: Evaluate the fitness (cost) of each particle's solution considering obstacle avoidance.</li>
            <li>Visualization: Plot the best path found by the PSO algorithm.</li>
        </ol>
    </div>
</body>
</html>
