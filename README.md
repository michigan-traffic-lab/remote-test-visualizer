# Remote test visualizer

# **Foxglove Studio Visualizer for remote testing:**

To open Foxglove Studio with data visualizer, there are two potions:

- In Chrome, go to [https://studio.foxglove.dev/](https://studio.foxglove.dev/)
- Alternatively, Visit [https://foxglove.dev/download](https://foxglove.dev/download) to download Foxglove Studio for your desktop

You can find more information about Foxglove Studio at: [https://foxglove.dev/docs/studio](https://foxglove.dev/docs/studio)

When you open Foxglove, you will be greeted by the screen shown below:

![](RackMultipart20231027-1-yeyub_html_8b53d19b74e2e449.png)

Click on the "Open connection" option. You will see the following screen:

![](RackMultipart20231027-1-yeyub_html_296edeb62e7d8c2c.png)

Replace the default Websocket URL with one of the following:

| **Sr No** | **Testing Type** | **Visualization URL** |
| --- | --- | --- |
| 1 | Simulation | wss://foxglove-simulation-server.um.city |
| 2 | Physical Resting | wss://foxglove-server.um.city |

Once you enter the URL and click Open, go to profile and click on Settings:

![](RackMultipart20231027-1-yeyub_html_fe15e4e06c1a1fee.png)

On the Settings wizard, please select Color scheme: Dark and click Done.

![](RackMultipart20231027-1-yeyub_html_7f33ac65c2a0c8e7.png)

**To load the Mcity OS default layout, follow these next steps:**

There will be two Foxglove studio sessions (each) for both simulation & real vehicle (AV) remote testing. Here is the file you need to download locally and import as described below:

| **Sr No** | **Objective** | **Visualization URL** | **File URL** |
| --- | --- | --- | --- |
| 1 | Simulation Screen - 1 | wss://foxglove-simulation-server.um.city | https://github.com/michigan-traffic-lab/remote-test-visualizer/blob/main/Mcity-Remote-Visualizer-Simulation.json |
| 2 | Simulation Screen - 2 | wss://foxglove-simulation-server.um.city | https://github.com/michigan-traffic-lab/remote-test-visualizer/blob/main/Mcity-Remote-Visualizer-Plots-v1.json |
| 3 | Vehicle Screen - 1 | wss://foxglove-server.um.city | https://github.com/michigan-traffic-lab/remote-test-visualizer/blob/main/Mcity-Remote-Visualizer-v3.json |
| 4 | Vehicle Screen - 2 | wss://foxglove-server.um.city | https://github.com/michigan-traffic-lab/remote-test-visualizer/blob/main/Mcity-Remote-Visualizer-Plots-v1.json |

Back in the Foxglove Studio browser application, as shown below, click on the menu icon, then "View" , then click on "Import layout from file…".

![](RackMultipart20231027-1-yeyub_html_f0cbe7c1093a858c.png)

**When prompted, browse to the file you downloaded earlier. This will load the Mcity default layout for remove observation of testing at Mcity.**

**Sample Visualization screens for** **simulation & real vehicle (AV) remote testing**

1. **Sample Visualization - Simulation Screen – 1**

![](RackMultipart20231027-1-yeyub_html_1fd7c377e790f71e.png)

1. **Sample Visualization - Simulation Screen – 2**

![](RackMultipart20231027-1-yeyub_html_1c488e8f4bf50f71.png)

1. **Sample Visualization - Vehicle Screen – 1**

![](RackMultipart20231027-1-yeyub_html_d69eaa2a31189c6b.png)

1. **Sample Visualization - Vehicle Screen – 2**

![](RackMultipart20231027-1-yeyub_html_1c488e8f4bf50f71.png)
