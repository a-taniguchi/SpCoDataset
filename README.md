# SpCoDataset
Dataset for spatial concept formation

 - `/CC4F_turtlebot2/`: Creation-Core Building (4th floor) in Ritsumeikan University, using TurtleBot 2
   - `/map/`: Files on an environmental map (including formats supported by ROS)
   - Training data: position and words 
 - `/SIGVerseV2/`: Home enviornment (One room) on SIGVerse version 2
    - `/map/`: Files on an environmental map
    - `/stream_data/`: stream data of observation and latent variables for MCL
    - Training data: position and words 
 - `/albertB/`: [albert-B-laser-vision-dataset](https://dspace.mit.edu/handle/1721.1/62291) from [the Robotics Data Set Repository (Radish)](http://radish.sourceforge.net/)
    - `/map/`: Files on an environmental map (including formats supported by ROS)
    - Training data: position, words and image fetures
    - `/img_feature/`: Image features obtained using a pretrained CNN 
      - `/places205/`: Places205-AlexNet
      - `/places365/`: Places365-ResNet

Speech signal data is not included in the dataset.  

## References
These data sets are used in the following papers:
 - Akira Taniguchi, Tadahiro Taniguchi, and Tetsunari Inamura, "Spatial Concept Acquisition for a Mobile Robot that Integrates Self-Localization and Unsupervised Word Discovery from Spoken Sentences", IEEE Transactions on Cognitive and Developmental Systems, Vol. 8, No. 4, pp.285-297, 2016.
 - Akira Taniguchi, Tadahiro Taniguchi, and Tetsunari Inamura, "Unsupervised Spatial Lexical Acquisition by Updating a Language Model with Place Clues", Robotics and Autonomous Systems, Vol. 99, pp.166-180, 2018. 
 - Akira Taniguchi, Yoshinobu Hagiwara, Tadahiro Taniguchi, and Tetsunari Inamura, "Online Spatial Concept and Lexical Acquisition with Simultaneous Localization and Mapping", IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS2017), pp.811-818, Sep, 2017. in Vancouver, Canada.

## Other dateset links:

 - https://github.com/hirokoba/Datasets-EmergentSystemLab
 - https://github.com/hirokoba/Datasets-Experimental-room-10-
 - https://github.com/EmergentSystemLabStudent/Dataset_of_SpCoMapping
 - https://github.com/EmergentSystemLabStudent/SweetHome3D_rooms
