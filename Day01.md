# Day01 #
## 今日完成 ##
<ol>
	<li>基础HTML和HTML5</li>
	<li>基础CSS</li>
	<li>应用视觉设计</li>
	<li>CSS弹性盒子</li>
</ol>

## 收获 ##
这里只记录刷题过程中遇到的新的知识点、遗忘知识点及补充知识点<br>
### 基础HTML和HTML5 ###
新知识点get:
<ol>
	<li>a标签中href属性指向的值不确定时可用#做占位符<br>
<code html>
	<a href="#">这是一个链接占位符</a>
</code>
	</li>
	<li>div标签，块级元素<br>
<code html>
	<div>
		<p>This is a paragraph</p>
	</div>
</code>
	</li>
</ol>
遗忘知识点复习：
<ol>
	<li>页面基本布局<br>
<code html>
	<!DOCTYPE html><!-- 一种文档类型，告诉浏览器要使用什么样的规范 -->
	<html lang="en"><!-- 总标签 -->
	<head> <!-- 头标签，唯一的 -->
    <!-- meta描述性标签，表述网站的关键信息 -->
    <!--  一般用于制作SEO（搜索引擎优化）  -->
	    <meta charset="UTF-8">
	    <title>页面结构分析</title><!-- 网页标题 -->
	</head>
	<body>    <!-- 网页主题标签 -->
		<header></header> <!-- 头部内容 -->
		<section></section><!-- 主体内容 -->
		<footer></footer><!-- 脚部内容 -->
	</body>
	</html>
</code>
	</li>
	<li>placeholder属性，用做占位符<br>
<code html>
	<input type="text" placeholder="请输入账号">账号：
</code>
	<li>input type=text的多个属性<br>
<code html>
	<input type="text" name="username" value="admin" maxlength="8" size="20" required>账号：
	<!--      
	 name 组名
	 value 初始值
     maxlength 最大长度
     size 文本框的长度 
	 required 要求必须填写-->
</code>
	</li>
	<li>单选框与复选框<br>
<code html>
	<!--单选框 input type="radio"
		label用于标识
        value="" 初始化（必须）
        name="" 组名（关联的单选按钮必须一致）
        checked 默认选中
        -->
    <label>
    	<input type="radio" value="male" name="sex">男
    	<input type="radio" value="female" name="sex" checked>女
	</label>
	<br>
	<!--多选框 input type="checkbox"
	label 用于标识 for关联多选框
	value="" 初始化（必须有）
	name=""  组名（一致）
	checked 默认选中
	-->
	<!--写法1：-->
	<label for="first">
	    <input id="first" type="checkbox" value="football" name="hobby">足球
	</label>
	<label>
	    <input type="checkbox" value="basketball" name="hobby">篮球
	</label>
	<label>
	    <input type="checkbox" value="sleep" name="hobby" checked>睡觉
	</label>
	<label>
	    <input type="checkbox" value="chat" name="hobby">聊天
	</label>
	<br>
	<!-- 写法2：-->
	<input type="checkbox" id="number1" value=""/>
	<label for="number1">1</label>
	<input type="checkbox" id="number2" value=""/>
	<label for="number2">2</label>
	<input type="checkbox" id="number3" value=""/>
	<label for="number3">3</label>
</code>
</ol>
## 不足 ##




## 下一步目标及调整 ##
