# hand_eye_calibrate为主函数，可直接运行~

该项目用于对“眼在手上”的机械臂进行手眼矩阵计算。

mydata文件夹为示例数据以及对应的机械臂位姿信息（poses.txt）

hand_eye_calibrate.py：主函数，手眼标定函数，计算得到手眼转换关系矩阵

forwardkinematics.py: 将位姿正运动学解算，然后转换为旋转、平移向量并保存，注意请在宇树文件夹下运行

test.py：在手眼矩阵误差大的情况下用Matlab工具箱进行相机标定，然后转换为旋转、平移向量

R_da.json,T_da.json,Tr1.json,Tt1.json均为示例数据