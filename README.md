# Optimized Delivery Route Planning with Fuel Management

## Project Overview
This project optimizes the delivery route of a van while considering fuel constraints and minimizing refueling stops. It calculates the shortest path between delivery locations, selects the best starting warehouse, and ensures efficient fuel management.

## Features
- **Optimal Warehouse Selection:** Determines the best warehouse to start the deliveries.
- **Shortest Path Calculation:** Finds the most efficient route between delivery locations.
- **Fuel Management:** Tracks fuel levels and identifies the nearest refueling stations when needed.
- **Route Printing:** Displays the final route, including refueling points, total distance traveled, and the number of refills.

## How It Works
1. **Input:** A set of warehouses, delivery locations, and gas stations with distances between them.
2. **Processing:**
   - Computes the shortest path between locations.
   - Selects the most optimal warehouse for starting the delivery.
   - Monitors fuel levels and plans refueling stops dynamically.
3. **Output:** An optimized route that minimizes distance and fuel stops.

## Technologies Used
- **Programming Language:** Python
- **Algorithms:** Dijkstra’s Algorithm, Graph-based Shortest Path Computation
- **Data Structures:** Graphs, Priority Queues

## Use Cases
- Logistics and supply chain management
- Last-mile delivery route optimization
- Fuel-efficient transportation planning

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/optimized-delivery-route.git
   ```
2. Navigate to the project directory:
   ```bash
   cd optimized-delivery-route
   ```
3. Install dependencies (if required):
   ```bash
   pip install -r requirements.txt
   ```
4. Run the main script:
   ```bash
   python main.py
   ```

## Future Enhancements
- Integration with real-time traffic data
- Advanced fuel consumption models
- User-friendly UI for route visualization

## Contributors
- **Anvesha Churi** - Project Developer
- **Pratyush Dubey** - Project Developer

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
