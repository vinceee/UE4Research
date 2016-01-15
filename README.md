# UE4Research

程序底层维护:

	1.文件组织
		1.1 是否支持非seekfreecook（防止包体膨胀）
		1.2 是否支持patch以及大文件打包
		1.3 是否需要dxt5变成两张dxt1
	
	2.内存观察
		2.1 自带内存观察命令的准确性，以及检测粒度
		2.2 startuploading时间是否会随着美术效果明显变差（shader膨胀）

	3.帧速
		3.1 stat cpu,gpu是否准确，以及检测粒度
		3.2 gpu 在动态光，shadow加入后的效率能在低端机上的表现
		
	4.网络层
		4.1 http通讯的支持（跨平台）
		
程序玩法层:

	1.gameplay脚本
		1.1 是否可patch
		1.2 debug以及修改的维护成本
		1.3 uc去除以后actor的state如何实现
		1.4 游戏玩法层对于底层如（animation,particle）等动画资源的控制粒度
		1.5 excel导入层是否支持
	
	2.ui编辑器
		2.1 易用性，2dui动画的预览和效率
		2.2 种类丰富性，是否需要二次扩展
		2.3 分辨率适配
		2.4 是否支持3dpartile的应用在ui上？3dui的支持？
		2.5 ui精度，高精度贴图在pc和mobile上效果是否一致
		2.6 字体动态字是否支持
	
