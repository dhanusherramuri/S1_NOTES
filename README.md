# SEMESTER 1 NOTES


This repository contains a collection of notes, presentations, and detailed lab materials from a first-semester engineering curriculum. The primary focus is on Advanced Machine Learning, Data Structures, and Real-Time Operating Systems.

## Subjects Covered

*   **Advanced Machine Learning (AML)**
*   **Data Structures and Algorithms (DSA)**
*   **Real-Time Operating Systems (RTOS)**
*   Advanced Linear Algebra (ALA) *(directory present)*
*   CAWJ *(directory present)*

## Repository Contents

### Advanced Machine Learning (AML)

This directory contains a series of PowerPoint presentations covering fundamental machine learning concepts, including:
*   Introduction to Machine Learning
*   Decision Trees
*   Feature Selection
*   Linear Regression
*   Overfitting and Regularization
*   Logistic Regression
*   K-Nearest Neighbors (KNN)
*   Model Evaluation Metrics
*   Lab 1 materials

### Data Structures and Algorithms (DSA)

This section includes presentations on the foundational principles of data structures and algorithm analysis:
*   Introduction to Algorithms
*   Performance Analysis
*   Abstract Data Types (ADTs): Linked Lists, Stacks, and Queues

### Real-Time Operating Systems (RTOS)

This directory features lecture materials on scheduling and a series of exceptionally detailed, self-contained technical documents for lab assignments. The lab documents in `RTOS/LAB/` are rendered HTML files providing deep dives into practical RTOS concepts on an STM32F103 microcontroller with FreeRTOS.

Key lab topics include:

*   **STM32F103 Build System Explained (`03_stm32f103-buildsystem.html`)**: A comprehensive walkthrough of a bare-metal and FreeRTOS build system, covering `make`, linker scripts (`.ld`), startup assembly (`.s`), and the interaction between shared common files and individual projects.

*   **Multi-threading with HSE Clock & Idle Sleep (`03_p_three-thread-blink-hse.html`)**: An analysis of a three-task FreeRTOS application. This document details the step-by-step process of configuring the STM32's clock system to run at 72MHz from the High-Speed External (HSE) crystal and PLL. It also explains how to implement a power-saving idle task using the `wfi` (Wait For Interrupt) instruction.

*   **Priority Inversion Demonstration (`21_Lab_priority-inversion.html`)**: A clear and practical demonstration of the classic priority inversion problem. The document uses three tasks with different priorities and a shared binary semaphore to trigger the inversion, illustrates the system behavior with Gantt charts, and then shows how replacing the semaphore with a mutex (which supports priority inheritance) resolves the issue.
