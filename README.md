# Hi, I'm Dmitrii 👋

## About me

👨‍🎓 **Education**:
  - Bachelor's degree: **Mechatronics**, Brno University of Technology, 2021-2024.
  - Master's degree: **Applied Informatics**, Brno University of Technology, 2024-2026.

🦾 **Specializations**:
  - Embedded systems,
  - Machine Learning, Deep Learning, Data Science.

## Tech stack

### Embedded systems:
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
<img src="https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white" /> <img src="https://img.shields.io/badge/Makefile-000000?style=for-the-badge&logo=gnu&logoColor=white" /> <img src="https://img.shields.io/badge/FreeRTOS-2C9AB7?style=for-the-badge&logo=freertos&logoColor=white" />
<img src="https://img.shields.io/badge/Embedded%20Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/Protobuf-3362AF?style=for-the-badge&logo=google&logoColor=white" />
<img src="https://img.shields.io/badge/HDLC-8B0000?style=for-the-badge&logo=protocols&logoColor=white" />


<img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white" /> <img src="https://img.shields.io/badge/Raspberry%20Pi-C51A4A?style=for-the-badge&logo=raspberrypi&logoColor=white" /> <img src="https://img.shields.io/badge/BeagleBone%20Black-000000?style=for-the-badge&logo=beaglebone&logoColor=white" />

### Machine Learning, Deep Learning, Data Science:
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
<a href="https://numpy.org" target="_blank"><img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white" /></a> <a href="https://pandas.pydata.org" target="_blank"><img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" /></a> <a href="https://matplotlib.org/" target="_blank"><img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white" /></a>
<a href="https://scikit-learn.org" target="_blank"><img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" /></a>
<a href="https://keras.io" target="_blank"><img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" /></a> <a href="https://tensorflow.org" target="_blank"><img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" /></a>  

  <a href="https://fastapi.tiangolo.com" target="_blank"><img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" /></a> <a href="https://flask.palletsprojects.com" target="_blank"><img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" /></a> <img src="https://img.shields.io/badge/asyncio-3776AB?style=for-the-badge&logo=python&logoColor=white" /> <a href="https://www.uvicorn.org/" target="_blank"><img src="https://img.shields.io/badge/Uvicorn-121212?style=for-the-badge&logo=uvicorn&logoColor=white" /></a> <img src="https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white" />

## 💼 Work Experience

**Embedded Software Engineer**  
📍 Bender Robotics.
🇨🇿 Brno, Czech Republic. 
🗓️ May 2023 — December 2024.

- Firmware development for STM32 Cortex M in compliance with **MISRA C**.
- Development under **FreeRTOS**, **HAL** and **Bare Metal**.
- Build system setup using **CMake**, **Makefile**.
- Peripheral integration: **ADC**, **DAC**, **UART**, **USB**, **I2C** and **SPI**.
- Communication systems using **HDLC** and **Protocol Buffers**.
- Unit testing using **Unity Test Framework**.
- Code versioning and collaboration via **GitLab**.
- Maintained a **CI/CD pipeline** with **linters** and static analysis tools.

**Key Achievement:**
- Fully designed and implemented from scratch a **modular firmware** and Python **PC API** for the company's **Touchscreen Tester** device.  
- Automated touchscreen testing on the production line, reducing manual effort and improving test consistency.

---

**Variant Management Tool Developer**  
📍 NXP Semiconductors.
🇨🇿 Brno, Czech Republic.
🗓️ February 2025 — Present.

- R&D in **Product Line Engineering** following the **V-model** development process.  
- Development of **Feature Models** and **Variants** using **pure::variants** and **Eclipse**.
- Integration of **IBM DOORS Next** and **IBM ELM RM** to automate the flow of requirements into variant models.  
- Automation of configurations via **pure::variants JavaScript API**, **Eclipse console**, **CMake**, **Makefile** and **Python**.  
- Task and code management using **Jira** and **Bitbucket**.

---

### 👨‍💻 Personal Projects

#### Function Approximation and Deployment with Neural Network – Regression
Trained a neural network to approximate a mathematical function using synthetic data.  
Saved the model and preprocessing parameters in **JSON** for loading model.
Deployed the model with **FastAPI** and **Uvicorn**, exposing a REST API for predictions. 
Evaluated the model's performance using **MSE**, **MAE** and **R²** metrics.

[🔗 NN-Regression-WebApp](https://github.com/dmazilkin/NN-Regression-WebApp)

#### Medical Data Classification with Neural Network - Binary Classification
Built and trained a binary classifier using **Keras** on a medical dataset.  
Saved the model and preprocessing parameters to **JSON** for loading and using pretrained model for inference.
Evaluated the model's performance using **Accuracy**, **Precision**, **Recall**, **F2Score** and **Precision-Recall Curve** metrics.

[🔗 NN-Binary-Classification](https://github.com/dmazilkin/NN-Binary-Classification)

#### Maze Pathfinding with Search Algorithms – Graph Search and Route Planning

Implemented classic pathfinding algorithms (**BFS**, **DFS**, **A*** and **Jump Point Search**) to solve mazes represented as grids.
Implemented and Used efficient data structures: **Double-Linked List** for stacks/queues and **Binary Heap** for priority queues.
Visualized results and stored paths and performance metrics using Pandas and image exports using Pillow.

[🔗 ML-MazeSolver-RoutePlanning](https://github.com/dmazilkin/ML-MazeSolver-RoutePlanning)

#### File Compression with Canonical Huffman Code – Data Compression Algorithm
Implemented **Canonical Huffman coding** in **C** for compressing and decompressing ASCII files. Built frequency table and Huffman tree using a min-heap implemented from scratch, generated Canonical Huffman codes, and saved metadata for decompression. Developed a **command-line argument parser** to handle compression and decompression options with input/output file paths. Compiled the project using **Makefile** and processed files in chunks to handle large data efficiently.

[🔗 Compression-Huffman-code](https://github.com/dmazilkin/Compression-Huffman-code)

---

## 📫 Contacts

- [Linkedin](https://www.linkedin.com/in/dmitrii-mazilkin-866807337/)
