# Container Load Optimization Tool

## Overview
The **Container Load Optimization Tool** is a web-based application built using **Vue.js**. It helps logistics managers and shippers determine how many cargo units can fit inside a given container size. The tool calculates **container utilization percentage**, ensuring efficient space utilization in shipping.

## Features
- **Dynamic Input Fields** for container and cargo dimensions
- **Real-time Load Calculation**
- **Volume Utilization Progress Bar**
- **Supports Standard and Custom Container Sizes**
- **Simple 2D Visualization of Container Fill Level**

## Technologies Used
- **HTML, CSS** for layout and styling
- **Vue.js** for interactivity and state management
- **Canvas API** for visualizing the container load

## Installation & Usage
1. Download or clone the repository.
2. Open `index.html` in a web browser.
3. Enter container dimensions (length, width, height in feet).
4. Input cargo dimensions (length, width, height in inches), weight, and number of units.
5. Click **"Calculate Optimization"** to get results.

## Calculation Logic
 Computes **maximum number of cargo units** that can fit inside the container.
 Displays **utilization percentage** as a progress bar.
 Renders a **2D visualization** of container load.

## Example Usage
- A **40ft container** with a cargo of **10x10x10 inches** would return:
  - `You can fit X out of Y requested units in the container.`
  - Utilization progress bar updates dynamically.

## Screenshot
![Container Load Optimization Screenshot](./img.png)

## Future Improvements
- Support for **multiple container types** (e.g., 20ft, 45ft containers)


