# StockBubbles

## Introduction
This project is a comprehensive application for visualizing stock market data. It uses a stack that includes React, Flask, Node.js, WebSocket, Redis, and PostgreSQL to deliver real-time data updates and interactive visualizations. Initial project idea began with Sultan.

## Getting Started

### Prerequisites
- Docker
- Node.js
- Python 3.x
- PostgreSQL
- Redis

### Installation
Clone the repository to your local machine:
git clone https://github.com/davidismolina/stockbubbles.git

#### Setting Up the Backend
**Node.js Setup:**
```bash
cd backend/node_app
npm install
```

**Flask Setup:**
```bash
cd backend/flask_app
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
```

#### Setting Up the Frontend
**React Setup:**
```bash
cd frontend
npm install
```

**Environment Configuration**
Ensure that you create a .env file in both the Node.js and Flask directories to manage environment variables such as database configurations and Redis connections.

## Running the Application
**Start the Node.js server:**

```bash
cd backend/node_app
npm start
```

**Run the Flask server:**

```bash
cd backend/flask_app
flask run
```

**Launch the React frontend:**

```bash
cd frontend
npm start
```


## Features
- Real-time Data Visualization: Utilizing WebSocket for live data updates directly reflected in Highcharts.
- Interactive Charts: Enhanced user experience with interactive chart elements.
- Data Caching: Implementing Redis for efficient data caching to speed up response times.
- Robust Backend: Combining Flask and Node.js for handling different aspects of backend processing.

## Contributing
We welcome contributions. If you have suggestions or improvements, please fork the repository and create a pull request. For substantial changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
Sultan Jacobs - sultan@stockbubbles.org
David Molina - david@stockbubbles.org
Project Link: https://github.com/davidismolina/stockbubbles.git
