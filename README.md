# KalmanFilter
本人模拟了一次卡尔曼滤波算法的实践

'''
    卡尔曼滤波的模拟,称重模拟，每一次称重，仪器测量都会不一样，测量值形成一个均值真实值，方差为0.01的
    正态分布，
    根据经验预测值=真实值相等+偏差
    然后进行卡尔曼滤波进行更为精准的预测
    假设预测值到真实值的状态转移矩阵为 1 ，记预测的值与实际值完全一样
'''