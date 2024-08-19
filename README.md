# Optical-Tracking

In this project, we delved into the principles and practical applications of optical tracking systems, with a specific focus on the OptiTrack system. The exploration was divided into several key areas:

### 1. **Introduction to Optical Tracking Systems**

We began by understanding optical tracking systems, also known as motion capture systems, which utilize multiple cameras to monitor the position and orientation (pose) of objects within a designated area. These systems can capture complex movements by analyzing the trajectories of objects over time.

### 2. **Understanding Optical Tracking Systems**

**Advantages**: Optical tracking systems provide high spatial resolution, adaptable work areas, and can operate in various lighting conditions with infrared cameras. They are well-suited for applications in virtual production, virtual reality, human motion analysis, and robotics.

**Disadvantages**: Challenges include the necessity of attaching optical markers to objects, potential tracking failures due to overlapping objects, and reduced effectiveness in large or outdoor environments where markers may not be practical.

### 3. **Learning Goals**

The project aimed to:
- Grasp the fundamentals of optical tracking systems.
- Gain practical experience with the OptiTrack system.
- Evaluate the accuracy, limitations, and disturbances affecting optical tracking.

By the project's end, participants should be proficient in describing optical tracking systems, understanding the mathematical models involved, and effectively calibrating and using the OptiTrack system.

### 4. **Experimental Setup and Modeling**

**Minimum Setup**: Essential components of an optical tracking system include multiple cameras, optical markers, and tracking objects within overlapping camera areas.

**Simplified Modeling**: We focused on a two-dimensional model to understand object and camera interactions in a plane, using basic geometry to describe object and camera positions and orientations.

### 5. **Experimental Procedures**

**5.1 Calibrating the System**

- **Camera Calibration**: Using the OptiTrack software (Motive 2.2.0 Final), we performed camera calibration by recording 2D images of a moving calibration rod. The system calculates camera positions and orientations through a bundle adjustment procedure, requiring a quality level of "Very High" with around 1000 samples per camera.
- **Ground Plane Calibration**: We defined the origin and orientation of the coordinate system using a calibration triangle (CS-200), setting the ground plane in the software.

**5.2 Determination of the Position with One Marker and Two Cameras**

- **Preparing and Measuring**: Selected two cameras and attached a marker to the object. The marker's position was tracked and recorded, and data was exported to a CSV file for analysis.

**5.3 Determination of the Pose with Three Markers and Two Cameras**

- **Preparing and Measuring**: We determined the pose of an object using three markers. Data was recorded and analyzed to understand pose changes, including the impact of obscured markers.

**5.4 Investigation of the Influence of an External Light Source**

- **Measurements**: We assessed how reflective surfaces and external light sources affect marker tracking by observing marker visibility and measurement quality under various conditions.

**5.5 Investigation of Measurement Accuracy**

- **Measurements**: We moved an object with three markers to test measurement accuracy. Residual values were noted to evaluate the consistency of the system's measurements.

**5.6 Investigation of the Minimum Distance Between Two Markers**

- **Measurements**: The minimum distance at which two markers are clearly identified by the system was determined by varying distances and observing camera images.

**5.7 Investigation of the Influence of Masking**

- **Measurements**: We investigated how occlusions between markers affect tracking. The impact of marker overlap and obscuration on tracking accuracy was analyzed.

**5.8 Investigation of the Trajectory of a Mobile Robot**

- **Measurements**: A mobile robot with three markers followed a closed curve. The trajectory was recorded and analyzed in both Euler angles and quaternions.

### Summary

This project provided an extensive overview of optical tracking systems, covering both theoretical and practical aspects. We explored the principles of motion capture, conducted detailed experiments with the OptiTrack system, and addressed various challenges such as calibration, accuracy, and environmental influences. By engaging in these activities, we developed a thorough understanding of how optical tracking systems operate and how to effectively implement and utilize them in real-world scenarios.

--- 

This extended overview incorporates the detailed lab procedures and findings, offering a comprehensive summary of your project.
