# TODO-List
设计一个TODO List，页面结构如下图所示，要求：

使用HTML与CSS完成界面开发

实现添加功能：输入框中可输入任意字符，按回车后将输入字符串添加到下方列表的最后，并清空输入框

实现删除功能：点击列表项后面的“X”号，可以删除该项

实现模糊匹配：在输入框中输入字符后，将当前输入字符串与已添加的列表项进行模糊匹配，将匹配到的结果显示在输入框下方。如匹配不到任何列表项，列表显示空

注：以上代码实现需要能在浏览器中正常显示与执行。

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200501161504176.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM3MTYxNzQx,size_16,color_FFFFFF,t_70)

# upload-img
请按要求书写一个图片上传的弹窗组件，弹窗的样式要求如下：
1、样式要求
（1）宽： 668px,  高： 608px, 圆角5px， 边框1px solid #ccc

（2）弹窗垂直居中， 左右居中

（3）标题栏高 ：50px ,   右边的x不能使用图片，请使用css3画出, 标题文字颜色：红色

（4）列表元素的高：110px ， 宽:110px， 边框 1px solid #ccc

（5）中间“添加”按钮的图片地址：https://p1.pstatp.com/large/3ecd0004b6bdeff4c48d

    整体样式效果如下图所示：

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200501214609413.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM3MTYxNzQx,size_16,color_FFFFFF,t_70)
# money
设计一个红包生成的模拟器，要求实现如下功能设计：
设计需求

1. 页面上支持自定义红包输入的个数和金额，数值类型不能为空且必须大于1，效果如图一所示

2. 点击发送红包按钮，可以进入红包生成的loading页面，效果如图二所示，模态框的宽高为300*450px，垂直居中页面，包含必要的头像和文案，拆红包按钮可以围绕中轴线做旋转动画

3. 点击拆红包按钮后，会有一个向上的开红包的动画，根据前面输入的个数和金额生成红包获取列表，红包生成规则见附注。

4. 金额最高的作为“手气最佳”进行标注，见图三中的领取榜单所示

5. 从生成的红包列表中随机取出一个值作为你抢到的红包值，见图三中头像下的数字所示

6. 点击右上角的关闭按钮，可以关闭弹框，同时清空领取榜单里的记录，方便下次重新生成

红包生成规则

1. 红包的数值是随机的，并且数值的分布近似于正态分布。

2. 所有人都能分到红包，不会出现红包数值为0的情况，额度在0.01和(剩余平均值*2)之间。

3. 所有人的红包数值加起来等于支付的金额

4. 整体效果参考动态图，可以根据自身能力的情况侧重完成所擅长的环节(css页面，js交互，生成逻辑等)

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200502170454995.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM3MTYxNzQx,size_16,color_FFFFFF,t_70)

![在这里插入图片描述](https://img-blog.csdnimg.cn/2020050217042871.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM3MTYxNzQx,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200502170442750.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM3MTYxNzQx,size_16,color_FFFFFF,t_70)

