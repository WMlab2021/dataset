# dataset
human gait data set
## Data description
This data set is a human gait data set, which is collected by image processing mode and sensor mode. According to the three age groups of youth, middle age and old age and the two genders of male and female, the data sets are divided into six categories: young male, young female, middle-aged male, middle-aged female, old male and old female, corresponding to the data sets of young (m), young (f), mid age (m), mid age (f), elder (m) and elder (f).
Each data set contains the original data of multiple testers, corresponding to P1,P2,…
| Parameters           | Default s | Description                                                     |
| :-----------------: | :----: | :----------------------------------------------------------: |

Each tester's data includes the angular velocity (deg / s) of the hip and knee joints of the left and right legs collected by image processing mode and sensor mode. The data format is as follows: from left to right, the angular velocity of the right hip (collected by image processing), the angular velocity of the right hip (collected by sensor), the angular velocity of the right knee (collected by image processing), the angular velocity of the right knee (collected by sensor), the angular velocity of the left hip (collected by image processing), the angular velocity of the left hip joint (collected by sensors), the angular velocity of the left knee joint (collected by image processing), and the angular velocity of the left knee joint (collected by sensors). Because the frame rate of RGB camera is not high enough, the data acquisition frequency of image processing mode is lower than that of sensor mode, that is, the data acquisition frequency of each joint image processing mode is less than that of sensor mode.

//表格1

Among them:
1. Young (m) contains 22 subjects with 5500 sets of gait data;
2. Young (f) contains 5000 sets of gait data of 21 subjects;
3. Mid age (m) contains 3000 sets of gait data of 13 subjects;
4. Mid age (f) contains 3500 gait data of 15 subjects;
5. The elder (m) contains 3500 gait data of 15 subjects;
6. Elder (f) consists of 18 subjects with 4000 sets of gait data.

Gait_ QoE data set is classified gait model and corresponding QoE (quality of experience), which is obtained by subjective test. The data format is as follows:

//表格2

Among them, QoE is the average of 15 test1-test15. The data set is used to realize the personalized gait prediction model.
