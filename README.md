Software Engineer specializing in **Embedded Systems, Automated Release Engineering & Configuration Management**.

---

### Key Achievements
- **increased testing throughput by 5x** through robotic integration, 
- product variant **deployment time reduced by 60%** by implementing feature-based code generation, 
- **automated 90% of release documentation**.

---

### Technical Expertise

| Category | Skills & Technologies |
| :--- | :--- |
| **Languages** | C, Python, SQL |
| **Embedded Systems** | Bare-metal, HAL/LL, FreeRTOS, Embedded Linux |
| **Systems Engineering** | Product Line Engineering, Variant Management, Feature Modeling |
| **DSP** | Spectral Analysis (FFT, Spectrograms), FIR/IIR |
| **AI** | Classic ML (Scikit-learn), Neural Networks (PyTorch), Optimization Algorithms |
| **Tools** | CMake, Makefile, Git, Docker, Unit Testing (C), MISRA (C), LaTeX, Bash |

---

### Professional Background

* **NXP Semiconductors** | Embedded R&D Intern | *Automated Release Engineering & Configuration Management*
* **Bender Robotics** | Embedded Intern | *Firmware Development & Mechatronic Control*

---

### Education

* **MSc in Applied Informatics and Automation** | Brno University of Technology (2024 – 2027)
* **BSc in Mechatronics** | Brno University of Technology (2020 – 2024)

---

### Projects

### DSP | Audio Identification | Music Information Retrieval (MIR) System

- **Core Technology:** Signal Processing, Spectral Analysis, Python.
- **Feature Extraction:** Developed a system to identify 5-second noisy audio clips in a 700+ track database by converting raw WAV signals into **Spectrograms**.
- **Algorithm Design:** Implemented spectral normalization and noise reduction techniques to handle environmental interference.
- **Pattern Matching:** Designed a similarity engine using **cross-correlation** and **similarity matrices**, achieving high Top-1 and Top-5 recognition accuracy.

---

### Embedded Systems | System Architecture | Automated Tests

- **System Architecture:** Developed a **PC-driven** robotic system using a modular, layered C firmware for **STM32G491RE**.
- **Firmware Quality:** Adhered to **MISRA C** coding standards for safety and reliability; implemented **Unit Testing in C** to validate core motion and logic modules.
- **Communication Stack:** Engineered a robust PC-to-MCU interface via **USB (Virtual COM)** using **HDLC framing** and **Protobuf (Nanopb)** with **DMA** for zero-copy data handling.
- **Mechatronics & Control:** Implemented 3-axis stepper control and force-sensing via ADC; automated statistical profiling using **NumPy**, improving positioning precision by **85%**.

## [Traveling Salesman Problem Solver](https://github.com/dmazilkin/TSP-Solver)

A C++23 Traveling Salesman Problem solver built around a modular strategy-based architecture, allowing different optimization algorithms to run through a common interface. It parses TSPLIB-style coordinate data, builds a distance matrix, and applies configurable metaheuristics including a Genetic Algorithm with population-based crossover and elitism, and Simulated Annealing with temperature-driven neighborhood search using swap and 2-opt moves. The project is useful for studying heuristic optimization, benchmarking solver behavior, and experimenting with configurable search parameters in a clean command-line workflow.

### [Compression Huffman code](https://github.com/dmazilkin/Compression-Huffman-code)

A command-line file compression tool written in C that implements canonical Huffman coding from scratch for ASCII text. It builds frequency tables, generates Huffman and canonical codes, compresses data in chunks, and restores the original content through a matching decompression flow. The project is useful as both a practical example of lossless compression and a low-level study of core data compression techniques, including heap-based tree construction, bit-level encoding, and metadata-driven decoding. Built with gcc and make, it provides a lightweight, dependency-free implementation focused on demonstrating how canonical Huffman compression works end to end.

### [Maze Solver - Route Planning](https://github.com/dmazilkin/ML-MazeSolver-RoutePlanning)

Maze Solver is a Python project for finding paths through grid-based mazes using both uninformed and informed search algorithms, including DFS, BFS, A*, and Jump Point Search. It reads mazes from text files, computes a route from a start point to a goal, and generates visual outputs of the solution path along with optional explored nodes. The project also records performance metrics for each run, making it useful for comparing search strategies in pathfinding, robotics, navigation, or algorithm study. Built with Python and packaged with Poetry, it combines custom data structures with image and data-processing libraries to turn maze solving into a clear, testable workflow.

### [WebApp - Gym](https://github.com/dmazilkin/gym-webapp)

WebApp Gym is a lightweight gym management application built with FastAPI, SQLAlchemy, Jinja2, and PostgreSQL. It provides core workflows for member registration, login, membership purchasing, and class enrollment, alongside an admin area for managing clients, discounts, membership plans, and gym locations. The project is useful as a practical example of a full-stack CRUD system with authentication, server-rendered views, and database-backed business logic. It solves the day-to-day operational needs of a small fitness business while keeping the architecture simple and approachable for learning or extension.


### [NN Regression WebApp](https://github.com/dmazilkin/NN-Regression-WebApp)

NN Regression WebApp is a Python project that trains and serves a neural network for a nonlinear regression task through a simple web API. It uses TensorFlow/Keras for model training, scikit-learn for preprocessing and feature engineering, and FastAPI/Uvicorn to expose prediction endpoints for both single inputs and batches. The project also includes a Jupyter notebook for dataset analysis and training visualization, making it useful as an end-to-end example of moving a regression model from experimentation to deployment. It helps demonstrate how to package preprocessing, inference, and API access into a lightweight machine learning service.

---

### Contact
[LinkedIn](https://www.linkedin.com/in/dmitrii-mazilkin-866807337/) • [Email](mailto:dim.mazilkin@gmail.com) • Brno, Czech Republic | Brno, Czech Republic
