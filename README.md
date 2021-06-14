<p align="center">Human Gait Data Set</p>  

This data set is first utilized in the following research work:  
QARE：QoE-Driven Intelligent Balance Enhancement for Lower-limb Exoskeleton Rehabilitation Robots, submitted to ACM MM’21.  
Please cite this article when using the data set.   

This human gait data set contains two subsets: (1) the angular velocity traces of human walking gaits; (2) the Mean Opinion Scores (MOS) collected from 15 subjects when wearing the lower-limb exoskeleton robot (i.e. Fourier X2 from Fourier Intelligence).   

For the first part, subjects are divided into six categories: young male, young female, middle-aged male, middle-aged female, elder male and elder female, corresponding to data sets of Young (M), Young (F), Mid-age (M), Mid-age (F), Elder (M) and Elder (F). The angular velocity traces are obtained via two modalities, i.e. the visual modality (VM) and the sensor modality (SM). Please refer to the above article for technical details about the data acquisition. In summary, we establish a data set with a total of 23398 sets of human gaits data, as shown below  
1. Young(M) contains 4848 sets of gait data of 21 subjects;  
2. Young(F) contains 3982 sets of gait data of 21 subjects;  
3. Mid-age(M) contains 3068 sets of gait data of 13 subjects;  
4. Mid-age(F) contains 3032 sets of gait data of 15 subjects;  
5. Elder(M) contains 3660 sets of gait data of 15 subjects;  
6. Elder(F) contains 4808 sets of gait data of 18 subjects.  

For each file, the data format is (from left to right): Angular velocities of the right hip in VM, the right hip in SM, the right knee in VM, the right knee in SM, the left hip in VM, the left hip in SM, the left knee in VM, and the left knee in SM. Subjects are denoted as p1, p2, ….  

This dataset also contains a QoE-related subset, with MOSs collected from 4 people when wearing the lower-limb exoskeleton robot. Each subject performs 15 test trails, and provide a total of 4800 QoE traces. The subset is denoted as gait_QoE, with a data format of (from left to right) Time, angular velocity of the hip, angular velocity of the knee, average QoE score, QoE score of 1st trail, 2nd trail, …, 15th trail.     

This QoE subset is utilized in the personalized gait prediction module (for LSTM training process) in the above-mentioned article. 
