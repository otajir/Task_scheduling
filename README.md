Task Scheduling with Genetic Algorithms
📌 Overview

This project implements a task scheduling system using genetic algorithms to optimize resource allocation, execution order, and completion time.
The project is built as a web application with a backend scheduling engine and a frontend interface for visualization.

📂 Project Structure
├── .gitignore              # Git ignore rules  
├── app                     # Main application entry point (web server, API)  
├── genetic_algorithm       # Core scheduling logic using GA  
├── LICENSE                 # License file  
├── Procfile                # Deployment file for platforms like Heroku  
├── README.md               # Documentation  
├── requirements.txt        # Python dependencies  
├── runtime.txt             # Runtime configuration (Python version)  
├── static/                 # Static files (CSS, JS, images)  
└── templates/              # HTML templates for frontend  

⚙️ Installation

Clone the repository

git clone https://github.com/<username>/task_scheduling.git
cd task_scheduling


Create a virtual environment

python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows


Install dependencies

pip install -r requirements.txt

🚀 Usage

Run the application

python app.py


Open in browser
Navigate to http://127.0.0.1:5000 (or the port specified in app.py).

🔬 Features

Genetic Algorithm Scheduler

Optimizes task assignment across available resources.

Balances workload, minimizes total execution time.

Supports mutation and crossover strategies for solution improvement.

Web Interface

Upload task/job configurations.

Visualize scheduling results and task allocations.

Track algorithm convergence and performance.

Deployable

Ready for deployment on Heroku or similar platforms with Procfile and runtime.txt.

📊 Example Workflow

Define a set of tasks with durations and dependencies.

The genetic algorithm generates initial random schedules.

Iteratively improves schedules using selection, crossover, mutation.

Outputs the optimized task schedule through the web interface.
