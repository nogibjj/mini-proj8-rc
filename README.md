# Week8-miniProj- Data Processing Comparison: Python vs. Rust

## Introduction

This project aims to compare the performance and resource utilization of a data processing task implemented in both Python and Rust. We will take an existing Python script for data processing, rewrite it in Rust, and assess the improvements in terms of execution speed and resource usage. 

## Python Script

The original Python script (referred to as `data_processing_python.py`) is used as the baseline for our comparison. This script reads data from a CSV file, calculates the median, and reports CPU and memory usage during its execution.

## Rust Implementation

The equivalent data processing task is implemented in Rust (in the `data_processing_rust.rs` file). The Rust implementation replicates the functionality of the Python script, reading data from the same CSV file, calculating the median, and recording CPU and memory usage.

## Comparison

We will compare the Python and Rust implementations based on the following criteria:

### 1. Functionality in Rust

The Rust implementation should produce results that are consistent with the Python script. We will assess if the Rust version accurately computes the median and captures CPU and memory usage information.

### 2. Demonstrated Improvements 

We will evaluate the performance improvements achieved by the Rust implementation. This includes measuring execution time and assessing CPU and memory utilization. 

## Usage and Result Comparison

1. To run the Python script:

   ```bash
   python3 main.py
   ```
![Alt text](<Screen Shot 2023-10-23 at 12.22.39.png>)


2. To run the Rust implementation:

   ```bash
   cargo run
   ```

   ![Alt text](<Screen Shot 2023-10-23 at 12.23.07.png>)

   Ensure you have Rust and Cargo installed on your system.





## Conclusion

This project provides valuable insights into the performance and resource utilization differences between Python and Rust for data processing tasks. It highlights the strengths and limitations of each language and helps inform the choice of a programming language for specific use cases.

Enjoy exploring the world of data processing in Python and Rust!