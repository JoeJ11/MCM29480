2014美国数学建模竞赛
选择题目：B

题目概述：
	决定“best all time coach” male or female for the previous century.
	建立数学模型，决定best college coach or coaches(past or present) from among either male or female coaches 
in such sports as college hockey or field hockey, football, baseball or softball, basketball, or soccer.
	注意不同时间段对于模型的影响
	
	问题：
	1.阐述采用的标准
	2.阐述模型如何能够被用于其他的体育项目和全部性别
	3.展示3个不同体育项目中的Top5的教练
	4.写一个1-2页的说明，用非技术的语言向体育迷解释模型
	

	目前暂定模型框架：
	整体来看是y = Af(\vec{x})
	Part 1
		根据原始数据计算参数
		目前暂定的参数有：
			a. 提升度。根据历史成绩计算期望，然后通过概率的方法得到/或者通过关于队伍实力的数据得到
			b. 稳定度。根据执教期间的成绩得到
	Part 2
		神经网络学习，通过学习的方式确定A
	Part 3
		通过胜率等硬性指标筛选教练，再用模型对筛选出的教练进行排序
		

	目前还存在的问题：
	1. 参数如何选择？
	2. 训练集如何得到？
	3. 是否采取概率方法？
	4. 如何体现性别差异？（只考虑男子比赛？）
	5. 如何体现外部条件？包括：联赛级别，赛制差异，年代差异（同年代教练进行横向比较？）


目前的任务：
找数据