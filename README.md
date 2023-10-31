# **Foxglove Studio Visualizer for remote testing:**

## Introduction 
The remote test visualizer was built upon the Foxglove Studio, an open-source visualization and debugging tool designed for ROS. This visualizer offers a user interface enabling remote users to dynamically observe AV state, diverse safety and efficiency metrics, and more in real-time. The visualizer supports the visualization of the simulation-based testing using Mcity digital infrastructure and mixed-reality (MR) testing using both Mcity digital infrastructure and physical infrastructure. 

## Installation
To run Foxglove Studio for visualizing the remote test, there are two options:

- In the web browser (Chrome), go to [https://studio.foxglove.dev/](https://studio.foxglove.dev/)
- Alternatively, Visit [https://foxglove.dev/download](https://foxglove.dev/download) to download Foxglove Studio as a desktop app.

You can find more information about Foxglove Studio at: [https://foxglove.dev/docs/studio](https://foxglove.dev/docs/studio)

## Usage
Here is an example of visualization of simulation-based testing and MR based testing for an AV planning algorithm. 
### To connect to Mcity Foxglove Server
When you open Foxglove, you will be greeted by the screen shown below:

![image](https://github.com/michigan-traffic-lab/remote-test-visualizer/assets/54770426/c2528144-5d91-4361-b714-8c6ee038da68)


Click on the "Open connection" option. You will see the following screen:

![image](https://github.com/michigan-traffic-lab/remote-test-visualizer/assets/54770426/9c92dd8b-fe3e-4688-b0b5-bff4937408b6)


Replace the default WebSocket URL with one of the following:

| **Sr No** | **Remote Testing Type** | **Visualization URL** |
| --- | --- | --- |
| 1 | Simulation based | wss://foxglove-simulation-server.um.city |
| 2 | Mixed-reality based | wss://foxglove-server.um.city |

Once you enter the URL and click Open, go to profile and click on Settings:

![image](https://github.com/michigan-traffic-lab/remote-test-visualizer/assets/54770426/9f8c9207-be3e-4969-a202-b19298418683)


On the Settings wizard, please select Color scheme: Dark and click Done.

![image](https://github.com/michigan-traffic-lab/remote-test-visualizer/assets/54770426/6dab3099-3e64-4cd5-8213-b5f56c97d229)


### **To load the default layout, follow these next steps:**

There will be two Foxglove studio sessions (each) for both simulated-based & MR-based remote testing. Here is the file you need to download locally and import as described below:

| **Sr No** | **Remote Testing Type** |**Objective** | **Visualization URL** | **File URL** |
| --- | --- | --- | --- | --- |
| 1 | Simulation | Simulated AV and BV state | wss://foxglove-simulation-server.um.city | [Simulation Screen – 1](https://github.com/michigan-traffic-lab/remote-test-visualizer/blob/main/Mcity-Remote-Visualizer-Simulation.json) |
| 2 | Simulation | Evaluation metrics | wss://foxglove-simulation-server.um.city | [Simulation Screen – 2](https://github.com/michigan-traffic-lab/remote-test-visualizer/blob/main/Mcity-Remote-Visualizer-Plots-Simulation-v1.json) |
| 3 | Mixed-reality | Real AV and simulated BV state | wss://foxglove-server.um.city | [Mixed-reality Screen – 1](https://github.com/michigan-traffic-lab/remote-test-visualizer/blob/main/Mcity-Remote-Visualizer-v3.json) |
| 4 | Mixed-reality | Evaluation metrics | wss://foxglove-server.um.city | [Mixed-reality Screen – 2](https://github.com/michigan-traffic-lab/remote-test-visualizer/blob/main/Mcity-Remote-Visualizer-Plots-v1.json) |

Back in the Foxglove Studio browser application, as shown below, click on the menu icon, then "View", then click on "Import layout from file…".

![image](https://github.com/michigan-traffic-lab/remote-test-visualizer/assets/54770426/762f92f4-32f9-4fbe-b4b5-364ccca7397c)

When prompted, browse to the file you downloaded earlier. This will load the Mcity default layout for remote observation of testing at Mcity.


## **Sample Visualization screens for** **simulated based & MR based remote testing**

**Sample Visualization - Simulation Screen – 1**

![image](https://github.com/michigan-traffic-lab/remote-test-visualizer/assets/54770426/d9374dc8-4568-4708-8ca7-a952b06d33fc)


**Sample Visualization - Simulation Screen – 2**

![image](https://github.com/michigan-traffic-lab/remote-test-visualizer/assets/54770426/cd5ddebc-1b86-425d-aa12-240a3da28af8)


**Sample Visualization - Mixed-reality Screen – 1**

![image](https://github.com/michigan-traffic-lab/remote-test-visualizer/assets/54770426/666ebbf2-148f-4866-bfcd-bafd72acb1d7)


**Sample Visualization - Mixed-reality Screen – 2**

![image](https://github.com/michigan-traffic-lab/remote-test-visualizer/assets/54770426/2489ab5e-4790-413e-8fe8-03f8f7f72e69)

## Developers
* Rajanikant Patnaik Ananta (rpatnaik@umich.edu)

## Contact
* Henry X. Liu (henryliu@umich.edu)
