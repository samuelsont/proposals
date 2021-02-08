## FusedSLAM: Sensor Fusion Modalities for Colocalized Distributed Connected Autonomous Agents in a Global Coordinate System
*Ph.D. Proposal by: Samuelson T. Atiba*

### Summary
The domain of consensus planning for distributed connected autonomous agents with different sensing modalities within a complex dynamic environment has been severely limited by high latency in communication and lack of a framework to fuse heteroscedastic sensor data streams with the intent to colocalize such distributed agents within a global coordinate system. 5G mmWave technology which enables even faster connectivity with near-zero latency has brought about a new range of possibilities for massive ubiquitous computing and machine-to-machine communication. However, the exploration of the potential for applying the technology to connected autonomous agents is still nascent. Thus, the need arises to investigate sensor fusion modalities for obtaining real-time pose estimates of the agents in a global coordinate system using 5G-powered fog computing and set out a technique for consensus planning within the global coordinate system.


### Introduction
Distributed connected autonomous agents colocalized in a dynamic environment have hitherto been faced with several limitations in joint perception and planning which is required for task coordination among distributed agents. This is due, in no small part, to the problems associated with obtaining and aggregating real-time estimates of agents’ pose in a dynamic environment. While the lack of a centralised command hub in the distributed network guarantees unlimited scaling and increased resilience to failure in the network, a significant problem arises since there is no aggregation of the poses of all agents in a global coordinate system that is accessible by agent nodes [1]. The design of a distributed network necessitates such a crutch since agent nodes in the network can only be connected to a subset of agent nodes within the network. Further, the use of heterogeneous sensing modalities including lidar-, radar- and vision-based systems for obtaining point location estimates for simultaneous localization and mapping (SLAM) poses a unique challenge to colocating connected autonomous agents in a global coordinate system. A radar-based data stream is not readily combined with a vision-based data stream or a radar-based data stream due to inherent differences in characteristics of each sensing modality [2].

5G mmWave has brought about a new range of possibilities by enabling even faster connectivity with near-zero latency for massive ubiquitous computing and machine-to-machine communication [3]. Combined with massive cloud computing, 5G mmWave technology has the potential to bridge the divide between cloud computing and edge computing thus enabling the application of fog computing to the coordination of connected autonomous agents. However, the exploration of the potential for applying the technology to connected autonomous agents is still nascent. Albeit, a distributed network of connected autonomous agents stands to benefit the most from the advances in 5G mmWave connectivity since distributed autonomous agents operate in a world of massive data streams of high velocity and volume uniquely suited to the benefits of speed and low latency promised by the 5G mmWave technology.


### Aim
The aim of this research is to investigate 5G-powered fog computing for sensor fusion modalities to facilitate real-time localization of connected autonomous agents in a global coordinate system which provides a shared representation of the dynamic environment that enables consensus planning within the network of distributed agents.

 
### Objectives
The proposed research work has two tightly integrated objectives that form part of a robust framework for fusing different sensing modalities and coordinating distributed autonomous agents.

#### Objective 1: Distributed perception
This objective will investigate how to fuse different sensing modalities including radar-, lidar-, and vision-based systems from connected autonomous agents in dynamic and uncertain environments to extract intelligence and filter out unwanted data from the heteroscedastic sensor data stream.

#### Objective 2: Collaborative planning
The collaborative planning objective will develop consensus algorithms to make planning decisions for the distributed connected autonomous agents within the global coordinate system obtained from Objective 1 subject to specified mission goals and uncertainties in the global coordinate system.


### Review of Extant Methods
The prevailing methods of colocalizing autonomous agents include marker-based approaches [4] using tags such as QR codes, ArUco tags and AprilTags; vision-based approaches [5] using spatial anchors; and use of a common map for localizing multiple agents which employ different sensing modalities on the same map model of the environment. Marker-based approaches achieve very precise positioning with a low computational cost and have found widespread use in low-complexity environments that have to be instrumented. Vision-based systems using image features as spatial anchors are more complex and more computationally intensive, however, they are robust and suited to exploration of complex dynamic environments [6]. The common map approach involves anchoring multiple agents with differing sensing systems within a shared coordinate frame relative to an agent that is deterministically localized within the map model [Burri]. Vision-based systems have found wide acceptance in the autonomous vehicle industry due to the balance of cost, reliability, implementation complexity and robustness of the system [5].

### Proposed Method
The proposed research seeks to explore 5G-powered fog computing using vision-based spatial anchors and the fusion of several sensing modalities to create a shared representation of the environment and localize connected autonomous agents within such a global coordinate frame that facilitates consensus task planning.


### Conclusion
The research proposal has identified the need for a unified colocalization strategy that localizes multiple distributed and connected autonomous agents with heterogeneous sensor modalities in a dynamic environment using a shared representation of the environment i.e. a global coordinate system. The realization of such a colocalization strategy offers profound benefits through:
Contribution to existing body of knowledge in the area of robotic navigation and consensus planning.
Application to Intelligent transportation systems including smart logistics, human transportation and exploratory unmanned fleets of connected surface, underwater and aerial autonomous vehicles in dynamic, uncharted, GPS-denied hostile environments.

### References
1. L. E. Parker. (2009). Path planning and motion coordination in multiple mobile robot teams. Encyclopedia of complexity and system science.
2. De Silva, Demuni & Roche, Jamie & Kondoz, Ahmet. (2018). Robust Fusion of LiDAR and Wide-Angle Camera Data for Autonomous Mobile Robots. Sensors. 18. 2730. 10.3390/s18082730. 
3. GSMA Intelligence. (2014). Understanding 5G: Perspectives on future technological advancements in mobile. https://www.gsma.com/futurenetworks/wp-content/uploads/2015/01/2014-12-08-c88a32b3c59a11944a9c4e544fee7770.pdf
4. Krajník, Tomáš & Nitsche, Matias & Faigl, Jan & Vaněk, Petr & Saska, Martin & Duckett, Tom & Mejail, Marta. (2014). A Practical Multirobot Localization System. Journal of Intelligent and Robotic Systems. 76. 10.1007/s10846-014-0041-x. 
5. Aqel, M.O.A., Marhaban, M.H., Saripan, M.I. et al. Review of visual odometry: types, approaches, challenges, and applications. SpringerPlus 5, 1897 (2016). https://doi.org/10.1186/s40064-016-3573-7
6. M. Burri, H. Oleynikova, M. W. Achtelik, and R. Siegwart, “Real-time visual-inertial mapping, re-localization and planning onboard MAVs in unknown environments,” in IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2015.
