# -js-AJAX-
1. 数据交互 

		后台地址数据接口地址 https://route.showapi.com/181-1
		请求的参数
			请求账号 showapi_appid: 30603
			请求密码 showapi_sign:98960666afeb4992ae91971d13494090
			请求多少条数据 num :8
			是否随机拉取数据:rand:1
			从多少页开始请求:pag:1
		
	https://route.showapi.com/181-1?showapi_appid=30603&showapi_sign=98960666afeb4992ae91971d13494090&num=8&rand=1&page=1

	2. 解析数据并且动态dom生成
		for循环解析数组 
		
		querySelector
		innerHMTL
				
		
	前端发起数据请求

	后台验证请求(前后端数据通信 建立数据通道 验证请求状态)
	后台根据请求的参数 发送数据
	数据通过回调函数回馈到前端

	xml base64 

	number 单条数据 数字
	string 字符串
	function 函数
	json json
	array 数组
	
	json数据格式
		json.属性名称

		json['属性名称']
		数组 [1,2,3,54,5];
		json:{  
			apple:'苹果',
			pk:[1,2,3,4],
			fn:function(){
		
				}
			}
			键值对 key:value
				json.apple
		
		//请求的地址

		res:{
			showapi_res_body:{
				 code:200, //链接完成
				 msg:'success',
				 newsList:[
						{
							url:"http://mp.weixin.qq.com/s/NS1IgclC-bc7eTKUh6r-pA"
						},
						{},
						{},
						{}
					]
				}
		}
		javascript
				第一层:[事件,dom方法,bom方法,变量,数据类型,函数,控制流程,判断,数组]
				第二层:[作用域,函数表达式,call,apply,this 对象 面向对象 递归 迭代
				原型,原型链,闭包,arguments,工具的高级用法,二次穿参,回调函数,ajax,正则表达式,前端路由];
				第三层:[设计原理 ,设计模式 ,算法与数据结构, 框架分析]

				碰撞检测模块开发

				事件监听模块开发

				动态遍历模块开发 迭代器

				图片等比例缩放

				拖拽模块开发
		ajax 
			XMLHTTPRequest
			open设置数据
			同步	
				一个收银台 排队
			异步
				给一个号牌
					有人出收集号牌
					分配号牌给多个收银台进行结账
			windows
				多线程处理
					同时处理多个进程
					光速在各个进程之间来回切换
