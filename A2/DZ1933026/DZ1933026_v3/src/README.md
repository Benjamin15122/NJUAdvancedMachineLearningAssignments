## 训练/复现模型

参考example_train(), example_review()，需要先执行完train才可以review。

- create_dataset(ratio): 创建数据集并保存，训练集比例为ratio
- create_vocab(limit): 创建词袋并保存，词频小于limit的不作统计
- predict_test(feature)训练长度为feature的模型，提取训练集/测试集特征，并在test.txt上作预测，保存所有中间文件