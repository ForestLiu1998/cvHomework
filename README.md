# cvHomework
My cv Homework For Warp Img

# How to use?
`python main.py`

 `--ReferenceImg`你想要被拼接的图像，最好是左图，如果是将图像插入，比如把喜羊羊插入到广告牌中，这就是广告牌的图像
 
 `--TransferImg`你想要进行透视变换的图像，最好是右图
 
 `--HMatrixCheck`如果想要检查一下H计算的对不对请把这个设置成True
 
 `--WarpCheck`如果想要检查透视变换的结果，请把这个设置成True
 
 `--output` 最终拼接图像的输出路径
 
 `--Insert` 图像插入任务的话请把这个设置成True
 
 e.g. `python main.py --ReferenceImg roadScence.jpg --TransferImg xiyangyang.jpg --output insertImgOutput.JPG --Insert True`
 
 运行上面这行代码就会把喜羊羊插到广告牌里，让全世界都看喜羊羊。
 
 ## Notice
 选定点时从左上角顺时针选择，憋问为什么。
