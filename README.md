# Phone Company Simulator

A Python simulation of a telecommunications company with billing, contracts, call history, and real-time visualization.

## Overview
This project models the backend of a phone company, simulating customer behavior, billing systems, contracts, and call activity. It integrates **object-oriented programming**, **data parsing**, **test-driven development**, and **Pygame-based visualization** to provide a full simulation environment.

## Features
- **Billing System**: Handles minute rates, free minutes, and contract-specific billing strategies (`bill.py`).
- **Customer Management**: Tracks customer IDs, phone lines, call histories, and billing (`customer.py`).
- **Call Modeling**: Represents call metadata and supports textual/visual representations (`call.py`).
- **Contracts**: Implements multiple contract types with polymorphism:
  - TermContract
  - MTMContract
  - PrepaidContract (`contract.py`)
- **Call History**: Logs and filters incoming/outgoing calls with monthly support (`callhistory.py`).
- **Application Driver**: Orchestrates data loading, simulation, and visualization (`application.py`).
- **Data Handling**: Parses structured JSON datasets into usable Python data (`data.py`).
- **Filters**: Provides pluggable filters for call data (duration, customer, reset, etc.) (`filter.py`).
- **Testing**: Unit tests covering billing, contracts, filters, and customer logic (`sample_tests.py`).
- **Phone Line Model**: Associates phone lines with contracts and call histories (`phoneline.py`).
- **Visualization**: Displays call activity on a map using Pygame sprites and paths (`visualizer.py`).
- **Dataset**: JSON file containing customer, contract, and call event data (`dataset.json`).

## Tech Stack
- **Python 3**
- **Pygame** for visualization
- **JSON** for data input
- **Unit Testing** for validation

## What I Learned
- Designing modular **object-oriented systems** with clean abstractions.
- Implementing **polymorphism** with contracts and billing strategies.
- Building **data pipelines** with JSON parsing and preprocessing.
- Writing **robust unit tests** for edge-case coverage.
- Creating **visualizations** for system activity using Pygame.
- Managing **inter-module interactions** in a full-stack simulation.

## Getting Started

### Prerequisites
- Python 3.x
- Pygame (`pip install pygame`)

### Run the Application
python application.py

### Run Tests
pytest sample_tests.py

### Project Structure
.

├── application.py

├── bill.py

├── call.py

├── callhistory.py

├── contract.py

├── customer.py

├── data.py

├── dataset.json

├── filter.py

├── phoneline.py

├── sample_tests.py

├── visualizer.py


