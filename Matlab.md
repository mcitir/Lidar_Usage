
Object Detection and Tracking with Lidar Data: [link](https://www.mathworks.com/support/search.html/videos/object-detection-and-tracking-using-lidar-data-1588873040454.html?fq[]=asset_type_name:video&page=1)
- Ground Plane and Obstacle Detection Using Lidar Data Segmentation [link](https://www.mathworks.com/help/driving/ug/ground-plane-and-obstacle-detection-using-lidar.html)
  - Visulization of streaming data (Velodyne .pcap data) 
- Track Vehicles Using Lidar: From Point CLoud to Track List [link](https://www.mathworks.com/help/driving/ug/track-vehicles-using-lidar.html)
  - Joint Probabilistic Data Association Tracker (JPDA) [example](https://arc.aiaa.org/doi/full/10.2514/1.G004249) +  Interaction Multiple Model Algorithm (IMM) [example](https://www.jhuapl.edu/Content/techdigest/pdf/V22-N04/22-04-Genovese.pdf)
  - **NOTE:** Is this a usecase for research area of connected vehicle?
    
    ![image](https://www.mathworks.com/help/examples/shared_driving_fusion_lidar/win64/xxjpda.gif)
            
    > This animation shows that using a joint probabilistic data association tracker helps in maintaining tracks during ambiguous situations. 
    > Here, vehicles tracked by T43 and T73, have a **low probability of detection due to their large distance from the sensor**. 
    > Notice that the tracker is able to maintain tracks during events when one of the vehicles is not detected. 
    > During the event, the tracks first coalesce, which is a **known phenomenon in JPDA**, and then separate as soon as the vehicle was detected again.
- Fuse lidar point cloud with radar detections
  - Design extended object tracker:  Gaussian mixture probability hypothesis density filter (GM-PHD Filter) [example](https://arxiv.org/abs/1812.09636)
  - Assesment of fusion via GOSPA: [Generalized optimal sub-pattern assignment metric](https://arxiv.org/abs/1601.05585)

  
