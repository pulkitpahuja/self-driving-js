# Self Driving car in Vanilla JS using neural networks

This project simulates a self-driving car that learns to navigate roads autonomously using a custom-created neural network. By leveraging **vanilla JavaScript** and the **HTML5 Canvas**, the simulation offers an immersive environment where the car:

-   Automatically learns to steer on various roads.
-   Deals with dynamic obstacles such as other vehicles, traffic lights, and zebra crossings.
-   Chooses different destinations while calculating the shortest route.
-   Provides an option for manual control for comparison or testing.

Alongside the simulation, the webpage displays:

-   A real-time visualization of the autonomous car.
-   A live, graphical representation of the neural network in action.
-   A minimap that shows the car's current location and its surroundings.


## Features

-   **Custom Neural Network:** The car uses a custom-built neural network to learn optimal steering and decision-making processes by processing real-time sensor data. This adaptive learning allows the car to tackle complex road layouts and dynamic obstacles.
-   **Obstacle Awareness:** The simulation includes various obstacles such as other vehicles, traffic lights, and zebra crossings. The environment is procedurally generated, ensuring that each run presents a unique set of roads, obstacles, and landscape features, adding variety and replayability.
-   **Realistic Weather Simulation:** Weather conditions change dynamically based on the month of the year. These weather variations affect visibility and road conditions, offering additional challenges to the autonomous system and enhancing the realism of the simulation.
-   **Interactive Visualizations:**
    -   **Autonomous Car Display:** Watch the car navigate and adjust its path in real time.
    -   **Neural Network Visualization:** Understand how the neural network processes data and makes decisions.
    -   **Minimap:** Get a quick overview of the car's location relative to its environment.
-   **Autonomous Navigation:** Choose different destinations, and let the car calculate the shortest path and steer autonomously.
-   **Manual Control Option:** Switch to manual control to drive the car yourself for testing or fun.

![Screenshot 2025-02-13 at 5 25 47 PM](https://github.com/user-attachments/assets/dae83134-b207-4168-98a3-9141deda7e3c)

## Usage

Once the project is running, you'll see the simulation divided into three main sections:

1.  **Autonomous Car Display:**  
    Watch as the car navigates the road, avoiding obstacles and adjusting its trajectory based on inputs from the neural network.
    
2.  **Neural Network Visualization:**  
    Observe the inner workings of the neural network as it processes sensor data and makes real-time decisions.
    
3.  **Minimap:**  
    Monitor the car's position and path on a small map for better spatial context.
    

### Interaction

-   **Autonomous Mode:**  
    The car automatically steers, calculates the shortest route to selected destinations, and learns to avoid obstacles.
    
-   **Manual Mode:**  
    Switch to manual control to directly drive the car using keyboard inputs (or other supported control methods).
    
-   **Select Destination:**  
    Choose a location on the minimap or through the interface options to set a new destination for the car.


## Project Structure
```
self-driving-car-project/
├── CAR
│   ├── boat.png
│   ├── car.js
│   ├── car.png
│   ├── carInfo.js
│   ├── controls.js
│   ├── decisionBoundary.js
│   ├── helicopter.png
│   ├── imgs
│   │   ├── arbonaut.png
│   │   ├── blancco.png
│   │   ├── cgi.png
│   │   ├── floorplan.png
│   │   ├── karelia.png
│   │   ├── karelics.png
│   │   ├── karelics_2.png
│   │   ├── name.world
│   │   ├── nolwenture.png
│   │   ├── siili_2.png
│   │   ├── solenovo.png
│   │   ├── tiedepuisto.png
│   │   ├── tiedepuisto_2.png
│   │   ├── uef.png
│   │   └── uef_2.png
│   ├── index.html
│   ├── main.js
│   ├── miniMap.js
│   ├── multiDecisionBoundary.js
│   ├── network.js
│   ├── new_nn
│   │   ├── nn.js
│   │   └── nnEditor.js
│   ├── road.js
│   ├── sensor.js
│   ├── style.css
│   ├── utils.js
│   └── visualizer.js
├── README.md
├── WORLD
│   ├── js
│   │   ├── editors
│   │   │   ├── crossingEditor.js
│   │   │   ├── graphEditor.js
│   │   │   ├── lightEditor.js
│   │   │   ├── markingEditor.js
│   │   │   ├── parkingEditor.js
│   │   │   ├── startEditor.js
│   │   │   ├── stopEditor.js
│   │   │   ├── targetEditor.js
│   │   │   └── yieldEditor.js
│   │   ├── grid.js
│   │   ├── items
│   │   │   ├── building.js
│   │   │   ├── tree.js
│   │   │   └── water.js
│   │   ├── markings
│   │   │   ├── crossing.js
│   │   │   ├── light.js
│   │   │   ├── marking.js
│   │   │   ├── parking.js
│   │   │   ├── start.js
│   │   │   ├── stop.js
│   │   │   ├── target.js
│   │   │   └── yield.js
│   │   ├── math
│   │   │   ├── graph.js
│   │   │   ├── osm.js
│   │   │   └── utils.js
│   │   ├── primitives
│   │   │   ├── envelope.js
│   │   │   ├── point.js
│   │   │   ├── polygon.js
│   │   │   └── segment.js
│   │   ├── viewport.js
│   │   └── world.js
│   └── saves
│       └── many_targets_small.world
└── self-car.html
```
