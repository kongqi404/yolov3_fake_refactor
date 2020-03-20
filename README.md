# yolov3_fake_refactor
 将qqwweee大佬的yolov3的keras实现做了一丢丢改动来适应tf2.0
# 生成.weight文件
 在当前目录输入python convert.py yolov3.cfg yolov3.weights model_data/yolo.h5
# 预测
 python yolo_video.py [-image] [--input "路径"] [--output "路径"]
# 训练
 python train.py