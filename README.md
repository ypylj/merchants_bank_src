# merchants_bank_src

特征:信用卡消费数据+点击模块

问题一:用户操作日志只有一部分没有
解决方法:填充数据(根据已经知道的用户操作日志数据建立模型,用模型去预测预测没有日志的用户的操作日志)

问题二:样本不平均(0和1不平衡,0多)
解决方法:向下采样

问题三:特征过少
解决方法:特征交叉(几个特征结合)

问题四:特征增加后进行特征选择
方法:计算每个特征的信息熵