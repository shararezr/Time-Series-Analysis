# Triangle Counting in Spark

![Python](https://img.shields.io/badge/language-python-blue.svg)
![PySpark](https://img.shields.io/badge/framework-PySpark-orange.svg)

## Overview

This project implements two algorithms for approximating triangle counting in a distributed computing environment using Apache Spark. The goal is to compute the number of triangles in a graph using different approximation techniques, leveraging the power of distributed computing.

### Algorithms Implemented:
1. **MR_ApproxTCwithNodeColors**: A map-reduce approach with node coloring to approximate the number of triangles.
2. **MR_ApproxTCwithSparkPartitions**: Utilizes Spark partitions to perform the approximation.

### Main Functionality:
The main function reads command-line parameters including:
- Number of colors (C)
- Number of repetitions (R)
- File containing the graph data

It then performs triangle counting using both algorithms, printing results such as:
- Number of triangles
- Running time for each approach

This project demonstrates the use of Spark for distributed triangle counting, providing two approximation methods based on node coloring and Spark partitions.

## Getting Started

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/triangle-counting-spark.git
    cd triangle-counting-spark
    ```

2. **Set up the Spark environment:**
    - Install the required dependencies using `pip` or your preferred package manager.

3. **Run the program:**
    - Run the following command to execute the triangle counting algorithms:

    ```bash
    spark-submit triangle-counting.py --colors C --reps R --graph-file <path_to_graph_file>
    ```

4. **Output:**
    - The results will be displayed in the terminal with the number of triangles and the corresponding execution time for both algorithms.

## Requirements

- Apache Spark
- Python 3.x
- PySpark

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Special thanks to the contributors to Apache Spark for their distributed computing framework.

---

### **Project 2: Spark-based Triangle Counting with MapReduce**

```markdown
# Spark-based Triangle Counting with MapReduce

![Python](https://img.shields.io/badge/language-python-blue.svg)
![PySpark](https://img.shields.io/badge/framework-PySpark-orange.svg)

## Overview

This project provides a Spark application implementing two algorithms for counting triangles in a graph using the MapReduce paradigm. The algorithms are designed to handle large-scale graphs distributed across a cluster of machines.

### Algorithms Implemented:
1. **Counting Triangles Algorithm**: Calculates the total number of triangles in the graph by iterating over each vertex and its neighbors.
2. **MapReduce Approximation Algorithm**: Uses the Count Sketch data structure for approximate triangle counting by hashing edges and reducing them based on hash codes.

### Main Functionality:
The main function sets up the Spark environment and reads input data from a file. Based on the specified flag, it either runs the exact triangle counting algorithm or the approximation algorithm, printing execution times and results.

## Getting Started

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/spark-triangle-counting.git
    cd spark-triangle-counting
    ```

2. **Set up the Spark environment:**
    - Install the required dependencies.

3. **Run the program:**
    - Use the following command to execute the triangle counting algorithm:

    ```bash
    spark-submit triangle-counting.py --algorithm <exact|approx> --graph-file <path_to_graph_file>
    ```

4. **Output:**
    - Results will include the number of triangles and the execution time for the chosen algorithm.

## Requirements

- Apache Spark
- Python 3.x
- PySpark

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to the Spark community for making distributed computing easy and scalable.

---

### **Project 3: Spark Streaming - Count Sketch for Frequency Estimation**

```markdown
# Spark Streaming - Count Sketch for Frequency Estimation

![Python](https://img.shields.io/badge/language-python-blue.svg)
![PySpark](https://img.shields.io/badge/framework-PySpark-orange.svg)

## Overview

This project implements a Spark Streaming application that uses the Count Sketch algorithm to estimate the frequency of items in a data stream. The program processes data in real-time, updating the Count Sketch data structure to compute frequency estimates and other statistics.

### Main Functionality:
- **Count Sketch Algorithm**: Used to estimate the frequency of items in the data stream efficiently using hash functions and hash tables.
- **Real-time Data Processing**: The program receives a stream of data from a specified port and processes each batch of data in real-time.
- **Final Statistics**: Computes the total number of items, the number of distinct items, and the average relative error in frequency estimates.

## Getting Started

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/spark-streaming-count-sketch.git
    cd spark-streaming-count-sketch
    ```

2. **Set up the Spark environment:**
    - Install the required dependencies.

3. **Run the program:**
    - Start the streaming application using:

    ```bash
    spark-submit count-sketch-streaming.py --port <data-port> --hash-functions <num-functions> --hash-tables <num-tables>
    ```

4. **Output:**
    - The program will print statistics like the total number of items, number of distinct items, and frequency estimates with the error margins.

## Requirements

- Apache Spark
- Python 3.x
- PySpark

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to the Spark Streaming framework for enabling real-time data processing in distributed environments.

---

### **Project 4: Renewable Energy Analysis in the EU**

```markdown
# Renewable Energy Analysis in the EU

![R](https://img.shields.io/badge/language-R-blue.svg)

## Overview

This project focuses on analyzing the adoption of renewable energy sources, electricity price forecasting, and the reduction of carbon emissions in the European Union. It investigates how renewable energy consumption and production evolve over time and how they influence energy prices and CO2 emissions.

The analysis is conducted using R-Studio, and results will be presented in a markdown format.

### Key Questions:
- **Renewable Energy Adoption**: How does renewable energy adoption evolve over time in the EU? What factors influence the growth?
- **Electricity Price Forecasting**: Can electricity prices be predicted based on renewable energy availability? How does integration affect price volatility?
- **Carbon Emission Reduction**: How does renewable energy growth contribute to reducing carbon emissions, and what is its future impact?

## Data Sources

- **Energy Consumption**: Annual and monthly data for each country and energy production type.
- **Electricity Prices**: Historical data for electricity prices in EU countries.
- **CO2 Emissions**: CO2 emissions data for EU countries correlated with energy production.

### Data Breakdown:
- **Electricity Generation**: By fuel type (Bioenergy, Coal, Gas, Hydro, Nuclear, Solar, Wind).
- **Electricity Net Imports** and **Demand**.
- **Installed Power Generation Capacity**.
- **Emissions from Electricity Generation**.

## Getting Started

1. **Clone the repository:**

    ```bash
    git clone https://github.com/SkurativskaKateryna/BEFD_2023.git
    cd BEFD_2023
    ```

2. **Set up the R environment:**
    - Install the required packages listed in `DESCRIPTION`.

3. **Run the analysis:**
    - Open the R project file (`.Rproj`) and run the provided R scripts.

4. **Output:**
    - The results will be available in markdown format, including visualizations and data analysis interpretations.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Data is sourced from Ember, covering energy production, consumption, and carbon emissions across the EU.

