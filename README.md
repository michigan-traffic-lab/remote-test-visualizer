# **Foxglove Studio Visualizer for remote testing:**

To open Foxglove Studio with data visualizer, there are two potions:

- In Chrome, go to [https://studio.foxglove.dev/](https://studio.foxglove.dev/)
- Alternatively, Visit [https://foxglove.dev/download](https://foxglove.dev/download) to download Foxglove Studio for your desktop

You can find more information about Foxglove Studio at: [https://foxglove.dev/docs/studio](https://foxglove.dev/docs/studio)

When you open Foxglove, you will be greeted by the screen shown below:

![image](https://github.com/michigan-traffic-lab/remote-test-visualizer/assets/54770426/c2528144-5d91-4361-b714-8c6ee038da68)


Click on the "Open connection" option. You will see the following screen:

![image](https://github.com/michigan-traffic-lab/remote-test-visualizer/assets/54770426/9c92dd8b-fe3e-4688-b0b5-bff4937408b6)


Replace the default Websocket URL with one of the following:

| **Sr No** | **Testing Type** | **Visualization URL** |
| --- | --- | --- |
| 1 | Simulation | wss://foxglove-simulation-server.um.city |
| 2 | Physical Resting | wss://foxglove-server.um.city |

Once you enter the URL and click Open, go to profile and click on Settings:

![image](https://github.com/michigan-traffic-lab/remote-test-visualizer/assets/54770426/9f8c9207-be3e-4969-a202-b19298418683)


On the Settings wizard, please select Color scheme: Dark and click Done.

![image](https://github.com/michigan-traffic-lab/remote-test-visualizer/assets/54770426/6dab3099-3e64-4cd5-8213-b5f56c97d229)

---

---

---

# **To load the Mcity OS default layout, follow these next steps:**

There will be two Foxglove studio sessions (each) for both simulation & real vehicle (AV) remote testing. Here is the file you need to download locally and import as described below:

| **Sr No** | **Objective** | **Visualization URL** | **File URL** |
| --- | --- | --- | --- |
| 1 | Simulation Screen - 1 | wss://foxglove-simulation-server.um.city | [Mcity-Remote-Visualizer-Simulation.json](https://github.com/michigan-traffic-lab/remote-test-visualizer/blob/main/Mcity-Remote-Visualizer-Simulation.json) |
| 2 | Simulation Screen - 2 | wss://foxglove-simulation-server.um.city | [Mcity-Remote-Visualizer-Plots-v1.json](https://github.com/michigan-traffic-lab/remote-test-visualizer/blob/main/Mcity-Remote-Visualizer-Plots-v1.json) |
| 3 | Vehicle Screen - 1 | wss://foxglove-server.um.city | [Mcity-Remote-Visualizer-v3.json](https://github.com/michigan-traffic-lab/remote-test-visualizer/blob/main/Mcity-Remote-Visualizer-v3.json) |
| 4 | Vehicle Screen - 2 | wss://foxglove-server.um.city | [Mcity-Remote-Visualizer-Plots-v1.json](https://github.com/michigan-traffic-lab/remote-test-visualizer/blob/main/Mcity-Remote-Visualizer-Plots-v1.json) |

Back in the Foxglove Studio browser application, as shown below, click on the menu icon, then "View" , then click on "Import layout from file…".

![image](https://github.com/michigan-traffic-lab/remote-test-visualizer/assets/54770426/762f92f4-32f9-4fbe-b4b5-364ccca7397c)

---

**When prompted, browse to the file you downloaded earlier. This will load the Mcity default layout for remove observation of testing at Mcity.**

---

---

---

# **Sample Visualization screens for** **simulation & real vehicle (AV) remote testing**

1. **Sample Visualization - Simulation Screen – 1**

![image](https://github.com/michigan-traffic-lab/remote-test-visualizer/assets/54770426/d9374dc8-4568-4708-8ca7-a952b06d33fc)


1. **Sample Visualization - Simulation Screen – 2**

![image](https://github.com/michigan-traffic-lab/remote-test-visualizer/assets/54770426/cd5ddebc-1b86-425d-aa12-240a3da28af8)


1. **Sample Visualization - Vehicle Screen – 1**

![image](https://github.com/michigan-traffic-lab/remote-test-visualizer/assets/54770426/666ebbf2-148f-4866-bfcd-bafd72acb1d7)


1. **Sample Visualization - Vehicle Screen – 2**

![image](https://github.com/michigan-traffic-lab/remote-test-visualizer/assets/54770426/2489ab5e-4790-413e-8fe8-03f8f7f72e69)

