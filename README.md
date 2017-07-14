# baxter_DMP_RL
this is a baxter DMP and RL package.
## 1. genarating a joint trajectroy

 * follow this tutoral and genarating a joint trajectory ([Baxter Joint Trajectory Playback Example ]:http://sdk.rethinkrobotics.com/wiki/Joint_Trajectory_Playback_Example).
 * or you can go to this repo dataset file, the baxter_joint_input_data.csv is the joint trajectory csv file.

## 2. genarating a DMP trajector

 * do it by yourself: 

```python
rosrun dmp dmp_server
rosrun dmp baxter_r_ram_dmp.py
```

 * in the dataset the data0 - data4 csv file is the DMP trajector.

## 3. RL learning

