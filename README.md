# WorkTIps

## UE SceneCapture 
1. 保存到本地的图像比在UE编辑器中看到的RenderTarget暗
   如果用了后处理材质，可能试输出的颜色不在0-1的范围，使用saturate限定一下再输出
2. RenderTarget中没有动态阴影（物体没有接收自己的阴影）
   所有dynamic shadow相关的选项都勾上
   如果项目开启了使ray trace，必须勾选use ray trace if enable
