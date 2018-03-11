##### Eclipse快捷键

工欲善其事必先利其器，更加了解我们的开发工具有利于提高开发效率，而合理使用快捷键可以使我们事半功倍，这里收集了eclipse中的几种常见设置，eclipse的优化以及非常全面的快捷键介绍，大家有用到的时候可以方便查看。

这篇文章介绍了什么？

1、对eclipse进行优化，去掉不必要的自动检验更新，提高打开eclipse的速度和减少卡顿；

2、对eclipse工具栏进行调整，去掉用不到的小图标，看起来比较清爽，而且可以扩大我们可编辑的区域；

3、对eclipse进行一些常用的设置，比如字体，代码自动提示，方法自动生成（get,set等方法）等等；

4、eclipse非常全面的快捷键介绍。

对eclipse进行优化

eclipse会对文件进行检查，语法格式，代码等，检查往往会很耗性能，而且有些我们根本用不到，再好的工具也有80%的功能是用不到的。我们可以根据实际情况关闭部分自动检验，Window ——> Preferences ——>Validation

￼

我是只保留了一个自动检验，大家可以根据实际情况自行设置，关闭自动检验，当需要检验时可以手动进行，检验需要的文件，方法是右击文件，点击 validate进行手动检验。

eclipse界面进行调整

eclipse工具栏上有很多小图标，使用笔记本的童鞋，屏幕小，小图标可能占满三行，你的可编辑区域就会小了，很不方便，然而工具栏上的这些图标，有的可能你三五年都没用过一次，更何况我们还有快捷键调出它来不是？怎么把小图标选择性的隐藏调一些呢？

window——>Perspective——>Customize Perspective...

￼

￼

清爽了很多有木有？

更改Eclipse的字体更改默认字体Window->Preferences->General->Appearance->Colorsand Fonts ->Basics->Text Font更改编辑器字体Window->Preferences->General->Appearance->Colorsand Fonts->Java->Java Editor Text Font（不更改则使用默认字体）更改控制台字体Window->Preferences->General->Appearance->Colorsand Fonts->Debug->Console Font（不更改则使用默认字体）

自定义快捷键Window->Preferences->General->Keys选中要指定快捷键的项目，在Binding里输入快捷键

更改拼写检查设置（类似于word的拼写检查）Window->Preferences->General->Editors->Text Editors->Spelling可选择是否Enable spell checking

自定义代码模板Window->Preferences->Java->Editor->Templates选择New按钮添加新的代码模板自定义格式化参考模板Window->Preferences->Java->CodeStyle->FormatterEclipse自带了3个模板文件，这些都是不可更改的，我们可以点New按钮，新建一个模板文件，这样就可以更改了。

让Eclipse自动生成一些方法（例如成员变量的get和set方法）在编辑器面板点右键 选择Source菜单项，以Generate 开头的菜单项就是系统自动生成代码的选项，例如Generate Getters and Setters…就是自动生成成员变量的get和set方法配置eclipse的代码自动提示功能

Window ——> Preferences ——> Java ——> Editor ——> Content Assist

￼

把箭头指向的输入框内容改为.abcdefghijklmnopqrstuvwxyz。原因是eclipse只有在你打出'.'（点字符）的时候，才会弹出自动补全窗口给你选择，这是默认设置，现在你打出点和所有字母他都会给你代码提示，缺点是电脑性能不好的可能让你怀疑人生.......

eclipse快捷键大全

Ctrl+1  快速修复(最经典的快捷键) Ctrl+D 删除当前行 Ctrl+Alt+↓ 复制当前行到下一行(复制增加) Ctrl+Alt+↑ 复制当前行到上一行(复制增加) Alt+↓ 当前行和下面一行交互位置(特别实用,可以省去先剪切,再粘贴了) Alt+↑ 当前行和上面一行交互位置(同上) Alt+← 前一个编辑的页面 Alt+→ 下一个编辑的页面(当然是针对上面那条来说了) Alt+Enter 显示当前选择资源(工程,or 文件 or文件)的属性 Shift+Enter 在当前行的下一行插入空行(这时鼠标可以在当前行的任一位置,不一定是最后) Shift+Ctrl+Enter 在当前行插入空行(原理同上条) Ctrl+Q 定位到最后编辑的地方 Ctrl+L 定位在某行 (对于程序超过100的人就有福音了) Ctrl+M 最大化当前的Edit或View (再按则反之) Ctrl+/ 注释当前行,再按则取消注释 Ctrl+O 快速显示 OutLine Ctrl+T 快速显示当前类的继承结构 Ctrl+W 关闭当前Editer Ctrl+K 参照选中的Word快速定位到下一个 Ctrl+E 快速显示当前Editer的下拉列表(如果当前页面没有显示的用黑体表示) Ctrl+/ (小键盘) 折叠当前类中的所有代码 Ctrl+× (小键盘) 展开当前类中的所有代码 Ctrl+Space 代码助手完成一些代码的插入(但一般和输入法有冲突,可以修改输入法的热键,也可以暂用Alt+/来代替) Ctrl+Shift+E 显示管理当前打开的所有的View的管理器(可以选择关闭,激活等操作) Ctrl+J 正向增量查找(按下Ctrl+J后,你所输入的每个字母编辑器都提供快速匹配定位到某个单词,如果没有,则在stutes line中显示没有找到了,查一个单词时,特别实用,这 个功能Idea两年前就有了) Ctrl+Shift+J 反向增量查找(和上条相同,只不过是从后往前查) Ctrl+Shift+F4 关闭所有打开的Editer Ctrl+Shift+X 把当前选中的文本全部变味大写 Ctrl+Shift+Y 把当前选中的文本全部变为小写 Ctrl+Shift+F 格式化当前代码 Ctrl+Shift+P 定位到对于的匹配符(譬如{}) (从前面定位后面时,光标要在匹配符里面,后面到前面,则反之) 下面的快捷键是重构里面常用的,本人就自己喜欢且常用的整理一下(注:一般重构的快捷键都是Alt+Shift开头的了) Alt+Shift+R 重命名 (是我自己最爱用的一个了,尤其是变量和类的Rename,比手工方法能节省很多劳动力) Alt+Shift+M 抽取方法 (这是重构里面最常用的方法之一了,尤其是对一大堆泥团代码有用) Alt+Shift+C 修改函数结构(比较实用,有N个函数调用了这个方法,修改一次搞定) Alt+Shift+L 抽取本地变量( 可以直接把一些魔法数字和字符串抽取成一个变量,尤其是多处调用的时候) Alt+Shift+F 把Class中的local变量变为field 变量 (比较实用的功能) Alt+Shift+I 合并变量(可能这样说有点不妥Inline) Alt+Shift+V 移动函数和变量(Alt+Shift+Z 重构的后悔药(Undo) 

编辑作用域功能快捷键 

全局查找并替换 Ctrl+F 

文本编辑器 查找上一个 Ctrl+Shift+K 

文本编辑器 查找下一个  Ctrl+K 全局撤销  Ctrl+Z 全局复制  Ctrl+C 全局恢复上一个选择  Alt+Shift+↓ 全局剪切  Ctrl+X 全局快速修正  Ctrl1+1 全局内容辅助  Alt+/ 全局全部选中  Ctrl+A 全局删除  Delete 全局上下文信息  Alt+？ Alt+Shift+?  Ctrl+Shift+Space Java编辑器 显示工具提示描述  F2 Java编辑器 选择封装元素  Alt+Shift+↑ Java编辑器 选择上一个元素  Alt+Shift+← Java编辑器 选择下一个元素  Alt+Shift+→ 文本编辑器 增量查找  Ctrl+J 文本编辑器 增量逆向查找  Ctrl+Shift+J 全局粘贴  Ctrl+V 全局重做  Ctrl+Y

查看作用域功能快捷键 

全局放大 Ctrl+= 

全局缩小  Ctrl+-窗口作用域功能快捷键 全局 激活编辑器  F12 全局 切换编辑器  Ctrl+Shift+W 全局上一个编辑器  Ctrl+Shift+F6 全局上一个视图  Ctrl+Shift+F7 全局上一个透视图  Ctrl+Shift+F8 全局下一个编辑器  Ctrl+F6 全局下一个视图  Ctrl+F7 

全局下一个透视图  Ctrl+F8 

文本编辑器显示标尺上下文菜单  Ctrl+W 全局显示视图菜单  Ctrl+F10 全局显示系统菜单  Alt+-导航作用域功能快捷键 Java编辑器打开结构  Ctrl+F3 全局打开类型  Ctrl+Shift+T 全局打开类型层次结构  F4 全局打开声明  F3 全局打开外部 javadoc Shift+F2 全局打开资源 Ctrl+Shift+R 全局后退历史记录  Alt+← 全局前进历史记录  Alt+→ 全局上一个  Ctrl+, 全局下一个  Ctrl+. Java编辑器显示大纲  Ctrl+O 全局在层次结构中打开类型  Ctrl+Shift+H 全局转至匹配的括号  Ctrl+Shift+P 全局转至上一个编辑位置  Ctrl+Q Java编辑器转至上一个成员  Ctrl+Shift+↑ Java编辑器转至下一个成员  Ctrl+Shift+↓ 文本编辑器转至行  Ctrl+L搜索作用域功能快捷键 全局出现在文件中  Ctrl+Shift+U 全局打开搜索对话框  Ctrl+H 全局工作区中的声明  Ctrl+G 全局工作区中的引用  Ctrl+Shift+G文本编辑作用域功能快捷键 文本编辑器改写切换  Insert 文本编辑器上滚行  Ctrl+↑ 文本编辑器下滚行  Ctrl+↓文件作用域功能快捷键 全局保存  Ctrl+X Ctrl+S 全局打印  Ctrl+P 全局关闭  Ctrl+F4 全局全部保存  Ctrl+Shift+S 全局全部关闭  Ctrl+Shift+F4 全局属性  Alt+Enter 全局新建  Ctrl+N项目作用域功能快捷键 全局全部构建  Ctrl+B源代码作用域功能快捷键 Java编辑器格式化  Ctrl+Shift+F Java编辑器取消注释  Ctrl+/ Java编辑器注释  Ctrl+/ Java编辑器添加导入  Ctrl+Shift+M Java编辑器组织导入  Ctrl+Shift+O Java编辑器 运行作用域功能快捷键 全局单步返回  F7 全局单步跳过  F6 全局单步跳入  F5 全局单步跳入选择  Ctrl+F5 全局调试上次启动  F11 全局继续  F8 全局使用过滤器单步执行  Shift+F5 全局添加/去除断点  Ctrl+Shift+B 全局显示  Ctrl+D 全局运行上次启动  Ctrl+F11 全局运行至行  Ctrl+R 全局执行  Ctrl+U重构作用域功能快捷键 全局撤销重构  Alt+Shift+Z 全局抽取方法  Alt+Shift+M 全局抽取局部变量  Alt+Shift+L 全局内联  Alt+Shift+I 全局移动  Alt+Shift+V 全局重命名  Alt+Shift+R 全局重做  Alt+Shift+Y