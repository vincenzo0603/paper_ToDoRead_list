# paper_ToDoRead_list

## localization（带有全局位姿信息的）

- DMLL: Differential-Map-Aided LiDAR-Based Localization:基于差分地图辅助 LiDAR 的定位

- Tightly Coupled Range Inertial Localization on a 3D Prior Map Based on Sliding Window Factor Graph Optimization (闭源)

- 1-Day Learning, 1-Year Localization: Long-Term LiDAR Localization Using Scan Context Image

- LIGO: Tightly Coupled LiDAR-Inertial-GNSS Odometry based on a Hierarchy Fusion Framework for Global Localization with Real-time Mapping（待开源）

## life long

- SLAM-RAMU: 3D LiDAR-IMU lifelong SLAM with relocalization and autonomous map updating for accurate and reliable navigation

## LO or LIO

### Map-Aided Lidar Odometry
- DMLL:...
- LiDAR Inertial Odometry Aided Robust LiDAR Localization System in Changing City Scenes
- LOL: Lidar-only Odometry and Localization in 3D point cloud maps(open code)
- LiDAR localization at 100 FPS: A map-aided and template descriptor-based global method（open code） **


### Lidar Intensity

- COIN-LIO: Complementary Intensity-Augmented LiDAR Inertial Odometry (Intensity-Augmented + fast-lio)(开源)

### 退化环境

未开源：
- X-ICP: Localizability-Aware LiDAR Registration for Robust Localization in Extreme Environments
- Direct LiDAR-Inertial Odometry:Lightweight LIO with Continuous-Time Motion Correction
- COIN-LIO: Complementary Intensity-Augmented LiDAR Inertial Odometry (Intensity-Augmented + fast-lio)(开源)

开源：

## 偏向于建图
- DMSA - Dense Multi Scan Adjustment for LiDAR Inertial Odometry and Global Optimization（Multi Scan Adjustment，离线建图，不能实时，开源）
- NV-LIO: LiDAR-Inertial Odometry using Normal Vectors Towards Robust SLAM in Multifloor Environments （Normal Vector、Multifloor）

## just lidar odometry
- Kiss-icp: In defense of point-to-point icp–simple, accurate, and robust registration if done the right way
- Traj-LO: In Defense of LiDAR-Only Odometry Using an Effective Continuous-Time Trajectory （利用数百万点的时间信息和连续轨迹的内在平滑性，实现了时空一致的配准）

## 位置识别

SC Family
- Scan context: Egocentric spatial descriptor for place recognition within 3d point cloud map, IROS 2018.
- Scan Context++: Structural Place Recognition Robust to Rotation and Lateral Variations in Urban Environments, TRO 2021.
- Intensity scan context: Coding intensity and geometry relations for loop closure detection, ICRA 2020.
- Weighted scan context: Global descriptor with sparse height feature for loop closure detection, ICCCR 2021.
- Fresco: Frequency-domain scan context for lidar-based place recognition with translation and rotation invariance, ICARCV 2022.
- Global place recognition using an improved scan context for lidar-based localization system, AIM 2021.

Other
- STD: A Stable Triangle Descriptor for 3D place recognition

## 想法：只保留描述子，不保留点云定位