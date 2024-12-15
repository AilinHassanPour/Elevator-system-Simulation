# Elevator Simulation Project
This project implements an elevator algorithm for a 15-floor building, managing elevator traffic with optimal movement and fair response times.
## Table of Contents
1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Features](#features)
5. [Technologies Used](#technologies-used)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)
## Introduction
This project simulates the operation of an elevator system in a 15-floor building. It manages both internal and external requests from users (inside or outside the elevator) and optimizes the elevator's movement to ensure: 1. **Optimal Movement**: The elevator avoids unnecessary changes in direction to reduce wear and tear, ensuring efficient operation. 2. **Avoiding Starvation**: No user request should be ignored, and every request is prioritized so that no one waits indefinitely. 3. **Acceptable Response Time**: The algorithm balances fairness in response times, ensuring that users do not wait excessively for the elevator. The elevator’s behavior is modeled using a multi-threaded approach, where each elevator operates independently while being synchronized with external and internal requests.
## Installation
To run the project locally, follow these steps: 1. Clone the repository: `git clone https://github.com/yourusername/elevator-simulation.git` 2. Navigate to the project directory: `cd elevator-simulation` 3. Install dependencies: This project uses **PyQt5** for the GUI. Install the required Python packages using pip: `pip install -r requirements.txt` 4. Run the project: Start the application: `python Main.py`
## Usage
Once the application is running, you will see a graphical interface with controls for both internal and external elevator requests. External requests are made by pressing the buttons outside the elevator, while internal requests are made by passengers inside the elevator. - **External Requests**: Users can request the elevator to go to a specific floor (up or down). - **Internal Requests**: Once inside, users can press buttons to go to a desired floor. The elevator will handle requests efficiently, ensuring minimal delays and optimal movement between floors.
## Features
- **Multi-Elevator Simulation**: The system can simulate multiple elevators at once. - **Optimized Movement**: Avoids unnecessary direction changes to minimize wear. - **Priority Management**: Balances fairness in response times for all users. - **Real-Time Simulation**: The movement and request processing are visualized in real time using PyQt5.
## Technologies Used
- **Python**: The main programming language. - **PyQt5**: For creating the graphical user interface. - **Enums**: To define elevator states and movement directions.
## Contributing
We welcome contributions to improve the elevator simulation. To contribute: 1. Fork the repository. 2. Clone your fork: `git clone https://github.com/yourusername/elevator-simulation.git` 3. Create a new branch for your feature or fix: `git checkout -b feature-name` 4. Make your changes and commit them: `git commit -m "Describe your changes"` 5. Push your changes: `git push origin feature-name` 6. Create a pull request to merge your changes.
## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
## Contact
If you have any questions or suggestions, feel free to contact us: - Email: your.email@example.com - GitHub: [Your GitHub Profile](https://github.com/yourusername)
