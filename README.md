# Case Study: Flexible and Scalable Network Structures for Data Centers 🌐

This repository contains a comprehensive case study on **SDCCP (Scalable Data-Center Network based on Cartesian Product)**, a proposed network topology designed to address the limitations of traditional Data Center Networks (DCNs) like Fat-Tree.

## 📄 Abstract

Modern data centers require network architectures that can handle exponential traffic growth from Cloud Computing, Big Data, and AI workloads. Traditional structures often face challenges regarding:
-   **High Cost**: Expensive core switches and extensive cabling.
-   **Scalability Limits**: Difficulty in incrementally adding servers without major restructuring.
-   **Power Consumption**: Inefficient energy usage at scale.

This case study analyzes **SDCCP**, a structure constructed using the Cartesian Product of graphs. It offers a more flexible, scalable, and cost-effective alternative by utilizing commodity switches and allowing modular expansion.

## 🔍 Key Findings

### 1. Incremental Scalability
Unlike Fat-Tree, which requires defined sizes (k-values), SDCCP allows for step-by-step expansion. New server units can be added modularly without redesigning the entire network.

### 2. Cost Efficiency
By leveraging standard commodity switches and reducing the number of required high-end core ports, SDCCP significantly lowers both Capital Expenditure (CAPEX) and Operational Expenditure (OPEX).

### 3. Performance & Fault Tolerance
The topology maintains:
-   **Short Path Lengths**: Ensuring low latency.
-   **High Bisection Width**: supporting high-bandwidth traffic.
-   **Robustness**: Multiple alternative paths prevent single points of failure.

## 📂 Deliverables

This repository includes the full research analysis and presentation materials:

-   **📜 [Case Study Report (PDF)](./Group-7%20Case%20Study%20Report.pdf)**: Detailed technical analysis, mathematical graph theory foundations, and performance comparisons.
-   **📊 [Presentation Slides (PPT)](./Group-7%20Case%20Study%20PPT.pptx)**: Summary deck covering the problem statement, proposed solution, and conclusion.


---
*This case study explores the future of green and efficient data center networking.*
