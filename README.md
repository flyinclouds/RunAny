# 【RunAny】一劳永逸的快速启动工具 [v3.3 树节点上下移动](#ver)

只需配置一个自定义程序菜单，结合Everything神器仅需软件名，无路径就可以快速运行exe程序、lnk快捷方式！

不用考虑在哪台电脑、哪个路径的程序，家里和公司电脑都用同一套配置，云端同步更是如虎添翼😎

---

## RunAny启动软件就跟打字一样高效方便（如<kbd>\`</kbd>为热键）：

- \`ww就是work工作分类下的Word
- \`aw就是app常用分类下的Wiz
- \`fw就是file文件分类下的WinRAR

---

## RunAny让你告别繁琐的右键打开文件！
只要先选中文件，然后再启动RunAny中的软件，即可用该软件打开选中文件，**就是这么方便！**

---

## RunAny除了运行还能搜索！
在菜单配置添加搜索网址，先选中任意文字，然后用RunAny运行网址即可搜索，更有一次批量搜索功能，**就是这么高效！**

---

RunAny追求就是：<u>**一劳永逸**</u>
---

[首次使用请阅读：【自定义树形菜单配置方法】](#tree)

[【RunAny版本更新历史】](#ver)

---

RunAny演示：

<img src="https://raw.githubusercontent.com/hui-Zz/RunAny/master/RunAny%E6%BC%94%E7%A4%BA.gif" alt="RunAny演示" style="max-width:50%;">

RunAny演示打开文件：

<img src="https://raw.githubusercontent.com/hui-Zz/RunAny/master/RunAny%E6%BC%94%E7%A4%BA%E6%89%93%E5%BC%80%E6%96%87%E4%BB%B6.gif" alt="RunAny演示打开文件">

RunAny演示批量搜索：

<img src="https://raw.githubusercontent.com/hui-Zz/RunAny/master/RunAny%E6%BC%94%E7%A4%BA%E6%89%B9%E9%87%8F%E6%90%9C%E7%B4%A2.gif" alt="RunAny演示批量搜索">

---

建议：hui0.0713@gmail.com

讨论QQ群：[246308937【RunAny快速启动一劳永逸】](https://jq.qq.com/?_wv=1027&k=445Ug7u)、[3222783【AutoHotkey高级群】](https://jq.qq.com/?_wv=1027&k=43uBHer)、[493194474【软客】](https://jq.qq.com/?_wv=1027&k=43trxF5)

支持RunAny：![支付宝](https://raw.githubusercontent.com/hui-Zz/RunAny/master/支持RunAny.jpg)

**在此特别感谢 AHK-工兵、Balance、☆☆天甜 等对RunAny的大力支持，欢迎大家多多提出建议！**

> 这里是隐藏功能：

> 按住Ctrl打开软件会打开软件所在的目录
> 按住Shift打开软件会以管理员身份来运行

> (PS:输入\`可以<kbd>Win</kbd>+<kbd>\`</kbd>输入)

---

## <a name="tree">【自定义树形菜单配置方法】</a>

* 以-开头+名称为1级目录名,--名称为2级以此类推，如：`-app`、`--img`
* 单独一个-是1级分隔符，--2级亦是如此，如：`-`、`--`
* 每个菜单名首字母(或用&指定任意)便是启动快捷键，如：`IE(&E)`快捷键是e
* 可用竖|添加别名前缀,菜单便会显示别名，如：`TC|Totalcmd.exe`会显示TC
* 前加;可以注释暂时不需要用的，如：`;cmd.exe`
* 末尾;识别为短语可以直接输出，如：`hui0.0713@gmail.com;`

* 如果电脑上有多个同名程序，加上全路径指定运行其中一个
* 运行除exe、lnk后缀之外的，可以创建快捷方式变为lnk或者加上全路径来放入RunAny菜单
* 搜索网址的关键字，如果在中间而不是在末尾，用%s表示，默认不加就是加在末尾来搜索
---

## <a name="ver">【RunAny版本更新历史】</a>

### 【RunAny】 v3.3 树节点上下移动

### 【RunAny】 v3.2 双重菜单➿
+ 1个菜单东西多了，就需要第2个菜单

### 【RunAny】 v3.1
* 修复单个搜索关键词没与%s替代而在末尾的问题

### 【RunAny】v3.0 批量搜索🔍
+ 选中文本只弹出网址菜单搜索(也可在配置中取消)
+ **增加批量打开网址和选中文字批量搜索功能！**
+ 菜单配置中添加/修改/移动后通过Everything显示应用图标

### 【RunAny】v2.9
* 修复选中某些情况下选中文字文件RunAny未提取到的问题
* 批量网址下载失败情况，可单选某个网址修改下载地址再重新下载

### 【RunAny】v2.8
* 显示"多选导入"和"批量导入"的应用图标
+ 可以多选下载指定网址的图标

### 【RunAny】v2.7 极速🚀
+ 初始打开即可用，后台渐步加载应用图标，重启RunAny毫秒级加载

### 【RunAny】v2.6 图标优化🖼
+ 现在菜单配置中程序将显示自己的图标！
+ 在菜单配置加入"网站图标"功能，点击即可下载菜单中所有网站图标
  + 下载完成后网站无论是快捷启动还是菜单配置都将显示自己的图标
+ ZzIcon.dll中加入树节点、移动、上、下4个图标，更好的支持xp系统

### 【RunAny】v2.5 组合功能🔩
+ **先选中文件，然后RunAny中运行程序将打开选中的文件**
  + 如在资源管理器先选中1.txt，再按启动RunAny中notepad.exe就打开了1.txt
+ **先选中文字，然后RunAny运行网址将文件作为搜索条件**
  + 如先选中"关键字"，再启动RunAny中的百度(&B)|https://www.baidu.com/s?wd=，就变成了搜索"关键字"
+ **菜单配置增加有复选框**
  + TreeView的全选全不选功能
  + 批量移动项目到指定的节点下，并自动匹配级别
  + 批量勾选项目删除

### 【RunAny】v2.4 便利
+ 新增一键搜索选中文字
+ 记录最近运行程序
* 独立导入桌面程序功能

### 【RunAny】v2.3
+ 支持Ctrl键用TC打开应用目录
* 修复不能正确打开带空格路径
* 重置功能取消开机自动启动

### 【RunAny】v2.2 快捷🎈
+ **增加快捷方式lnk全盘路径和图标识别**
+ **增加开机自动选项**
+ **增加一键Everything[搜索选中文字][激活][隐藏]**
+ *增加输出简单短语的功能*
+ *新增屏蔽RunAny热键的程序列表*
+ *支持TotalCommander打开文件夹*
+ ~~现在可以隐藏失效的项目~~
+ 菜单编辑添加树时自动为其增加子项目
+ 初次运行的菜单配置增加了通用分类和流行软件
+ 初次运行自动添加桌面快捷方式
* 修复菜单删除项目时Del与删文字冲突
* 修复了批量导入问题且现在可以导入快捷方式
* 修正了网址的正则

### 【RunAny】v2.1 酷炫😉
+ 批量导入程序名称
+ 图标自定义化(包括托盘图标)
+ 优化搜索条件，排除C:\Windows及其他升级文件夹
* 现在会自动检查Everything.dll的可用性，需要用Everything64.dll时提示

### v2.0 正式更名为RunAny，易用性大幅提升，兼容菜单文件编辑和GUI界面编辑

### v1.9 自定义配置优化

+ 添加Everything路径配置选项
+ 添加显示热键自定义配置选项
+ 菜单配置现在单独保存在RunMenuZz.ini
+ 只有在用户设置与默认不同才将配置保存在注册表HKEY_CURRENT_USER\Software\RunAny
+ 添加重置按钮，清除注册表配置，不留痕迹

### v1.8 集成Everything自动检索程序，从此程序随便放目录都能用RunMenu运行了😀
