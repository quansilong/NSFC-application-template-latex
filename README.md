# NSFC application template latex (unofficial)

### 国家自然科学基金申请书正文（面上项目）LaTeX 模板 （自制非官方）

由个人根据官方MsWord模版制作。本模版的作者尽力使本模版和官方模版生成的PDF文件视觉效果大致一样，然而，并不保证本模版有用，也不对使用本模版造成的任何直接或间接后果负责。 不得将本模版用于商用或获取经济利益。本模版可以自由修改以满足用户自己的需要。但是如果要传播本模版，则只能传播未经修改的版本。使用本模版意味着同意上述声明。

如有问题，请发送邮件到 ryanzz@foxmail.com 中了基金的也欢迎反馈。
***
### 2023.1.3：
突然多了很多下载，看来又到了写基金申请书的季节了~~注意：申请书模板每年可能会略有微小的文字上的改动。因此强烈建议提交之前找官网上下载的MSword模板自己对照一下，尤其注意蓝字部分是否完全一样。等2023年的面上项目开放申请之后我会根据最新的官方MSword模板更新最新的tex文件（其实完全可以自己修改，并没有多少技术含量）。
***
### 2023.1.20: 
2023年度国家自然科学基金申报已经开始。根据基金委最新发布的面上项目正文MsWord模板做了更新。如果发现错误请及时告诉我。改动如下：
1. 根据官方模板蓝字部分的微小改动做了更正；
2. 更正四号字大小为14pt （上个版本不知道为何改成了15pt）；
3. 增加了一点文字说明，缩小了一下插图尺寸（不重要）。
***
### 2023.1.29: 
非常感谢几位老师的建议和指出的问题！做了几处小改动，为了和官方模板的格式更加接近：
1. section标题按照官方模板的样式缩进两个字符；
2. 缩小了“请勿删除或改动下述提纲标题及括号中的文字。”与“（一）立项依据与研究内容（建议8000字以下）：” 这两行的间距；
3. “参考文献”四个字的字号调整为四号，居左，楷体。（可以根据喜好自行调整）。
***
### 2023.2.1:
按照官方模板的格式，蓝字部分中的阿拉伯数字不再加粗。谢谢指正。
***
### 2023-02-06： 
根据@Readon的commits，做了如下修改：
1. 更正了一处蓝字部分：“（三）其他需要说明的问题”应为“（三）其他需要说明的情况”。这个非常重要！
2. 设置 AutoFakeBold=3，这样楷体粗体稍微细一点，和官方模板更加接近。
3. 稍稍调整了页面边框空白的宽度，大家可以自行微调。

作为LaTeX 菜鸟，非常感谢Readon的专业建议！更多专业的修改请见
https://github.com/Readon/NSFC-application-template-latex
***
### 2023-12-04：
一转眼2024年的申请又要开始了。主要做了两点修改：1. 把图的caption字体调整为楷体。2. 设置AutoFakeBold=2，个人感觉这样和MsWord模板中的粗体更接近一点。等官方模板更新之后我再做相应更新。
***
### 2023-12-30：
改用 `GB/T 7714` (numerical) 样式以支持中文文献。 这样做的另外一个优点是该包兼容natbib，修改参考文献的行距也比较方便，这里也缩短了一些。如有需要，也可以切换回ieeetrNSFC。
GB/T 7714 - 2015 主页：https://github.com/zepinglee/gbt7714-bibtex-style
***
### 2024-12-25：
使用 setspace 可以调整参考文献列表的行距，使其稍微紧凑一些。如果要调大行距就把 \setstretch 后面括号里的数改大看看效果。