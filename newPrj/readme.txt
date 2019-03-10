1、文件夹说明：
  (1)存放程序
    data/        :数据相关操作，包括数据预处理、dataset读取等
    models/      :模型定义。
    options/     :外接参数设置。
    utils/       :可能用到的工具函数
	
  (2)存放数据
    checkpoints/ :保存训练好的模型。
    datasets/    :存放训练集和测试集。
    results/     :存放最终测试结果(test.py 输出路径)
    trainresults/:存放训练时部分测试结果(train.py 训练的一定程度时测试一下结果)

python train.py --phase train --epoch 200  # 待修改
