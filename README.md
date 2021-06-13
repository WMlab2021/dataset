# Data description
  This data set is a human gait data set, which is collected by image processing mode and sensor mode. According to the three age groups of youth, middle age and old age and the two genders of male and female, the data sets are divided into six categories: young male, young female, middle-aged male, middle-aged female, old male and old female, corresponding to the data sets of young (m), young (f), mid age (m), mid age (f), elder (m) and elder (f).
Each data set contains the original data of multiple testers, corresponding to P1,P2,…

| | | | | | | | | | | | | | | | | | | | | | |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--:
|  p1  |  p2  |  p3  |  p4  |  p5  |  p6  |  p7  |  p8  |  p9  |  p10 |  p11 |  p12 |  p13 |  p14 |  p15 |  p16 |  p17 |  p18 |  p19 |  p20 |  p21 | p22

  Each tester's data includes the angular velocity (deg / s) of the hip and knee joints of the left and right legs collected by image processing mode and sensor mode. The data format is as follows: from left to right, the angular velocity of the right hip (collected by image processing), the angular velocity of the right hip (collected by sensor), the angular velocity of the right knee (collected by image processing), the angular velocity of the right knee (collected by sensor), the angular velocity of the left hip (collected by image processing), the angular velocity of the left hip joint (collected by sensors), the angular velocity of the left knee joint (collected by image processing), and the angular velocity of the left knee joint (collected by sensors). Because the frame rate of RGB camera is not high enough, the data acquisition frequency of image processing mode is lower than that of sensor mode, that is, the data acquisition frequency of each joint image processing mode is less than that of sensor mode.

|    |right hip             |    |right knee       |    |left hip        |    |left knee      |
|:--:|        :--:          |:--:|       :--:      |:--:|      :--:      |:--:|      :--:     | 
|image processing mode|     sensor mode    |image processing mode|   sensor mode   |image processing mode|   sensor mode    |image processing mode|   sensor mode
|1.3428|1.3428|24.1699|24.1699|-8.4839|-8.4839|-3.1128|-3.1128|


Among them:
1. Young (m) contains 22 subjects with 5500 sets of gait data;
2. Young (f) contains 5000 sets of gait data of 21 subjects;
3. Mid age (m) contains 3000 sets of gait data of 13 subjects;
4. Mid age (f) contains 3500 gait data of 15 subjects;
5. The elder (m) contains 3500 gait data of 15 subjects;
6. Elder (f) consists of 18 subjects with 4000 sets of gait data.

  Gait_ QoE data set is classified gait model and corresponding QoE (quality of experience), which is obtained by subjective test. The data format is as follows:

|time|gait（hip）|gait（knee）|QoE|test1|test2|test3|test4|test5|test6|test7|test8|test9|test10|test11|test12|test13|test14|test15|
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|0.02|4.3945|2.2583|2.93333|3|4|3|3|3|2|3|3|3|2|4|3|3|3|3|

  Among them, QoE is the average of 15 test1-test15. The data set is used to realize the personalized gait prediction model.
