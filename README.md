#FeatureSelector

Some methods of feature selection

##Permutation

根据原始标签训练出每个特征的importance

随机打乱原始标签训练出每个特征的importance

观察每个特征的importance差异度，差别较大的应当较好



##RemoveTest

先所有特征进行cv得到分数，记为原始分数

每次移除一个特征，计算移除后得分和原始分数, 提升则移除，否则保留

循环测试每一个特征