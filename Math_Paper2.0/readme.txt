试卷生成控制台程序v2.0

作者：尹宗文、汪庆祥

语言：java

开发环境：Window10 + ecplise

联系方式：qq：425623934 || 3254511772

时间：2018年10月7日

用途：用于生成小学，初中，高中难度的数学试卷

注意事项：尽量不要在一套卷子中生成大量题目

更新内容：	实现了UI界面，实现了注册账户的功能
			增强了用户信息储存
			新增做题页面，可以选择正确答案提交
			新增打分功能，做题后显示分数

存在bug：	1.计算量过大导致程序崩溃（初步推测是进行后缀表达式计算时产生的问题，由于时间关系未来得及进行合理化处理）
			2.答案选项显示时过长导致显示不全（处理完两位小数后频繁产生崩溃现象，未找到合理解决方案）

未实现功能：由于时间紧张，以下功能还未实现
			0.管理员用户登录可以管理所有用户
			1.忘记密码
			2.做题记录显示
			3.试卷回顾
			4.整体做题情况分析