#仅用于学习日记，不可用于任何商业用途
#用slim接口 用训练好的nasnet
#1、先把slim加入sys
#2、导入需要识别的图片的地址
#3、获得模型中图片的size
#4、根据3定义输入的placeholder
#5、根据4将其归一化
#6、定义空间命名和获得endpoint得到分类输出结果
#7、设定模型定制 导入模型
#8、定义图片占位array
#9、将2中的图片进行的转换
#10、将放入session中  按5输入 按6输出
#11、打印图片 获得结果
