# Synchronization Methods Comparison in Java

This project aims to evaluate and compare the efficiency of various synchronization methods in Java. It employs a simulation of water tanks as shared resources, managed by multiple producer and consumer threads running in parallel. Each tank utilizes a different synchronization method, offering a practical approach to assess performance and applicability in multithreaded applications.

## Features

- **Parallel Processing:** Leverages MPJ Express for managing threads and inter-process communication.
- **Diverse Synchronization Techniques:** Implements multiple synchronization methods to compare their efficiency.
- **Simulation of Shared Resources:** Uses water tanks as an analogy for shared resources accessed by threads.
- **Performance Evaluation:** Provides insights into the advantages and drawbacks of each synchronization method.

## Technologies Used

- **Programming Language:** Java
- **Parallel Processing Library:** MPJ Express
- **Development Environment:** NetBeans
- **Execution Platform:** Windows

## Project Structure

```
├── src
│   ├── producers
│   ├── consumers
│   ├── synchronization_methods
│   ├── tanks
├── lib
│   ├── mpi.jar
├── README.md
```

- **src:** Contains the source code for producers, consumers, synchronization methods, and tank simulation.
- **lib:** Includes external dependencies such as `mpi.jar` for MPJ Express.

## Getting Started

### Prerequisites

1. Java Development Kit (JDK) installed.
2. MPJ Express library set up in your project.
3. NetBeans IDE for development (optional but recommended).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sync-methods-comparison.git
   ```
2. Import the project into your IDE.
3. Add `mpi.jar` to your project dependencies.

### Running the Project

1. Compile the project:
   ```bash
   javac -cp lib/mpi.jar src/**/*.java
   ```
2. Execute the program:
   ```bash
   java -cp lib/mpi.jar:. main.Main
   ```

## How It Works

- **Producers and Consumers:** Threads representing producers and consumers interact with the water tanks.
- **Synchronization Methods:** Each tank employs a unique synchronization method, such as locks, semaphores, or synchronized blocks, to regulate thread access.
- **Performance Metrics:** The program measures execution time, throughput, and other key metrics for comparison.

## Results and Insights

This section will be updated with detailed performance results and observations once the experiments are conducted.
