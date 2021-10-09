![kalila-cc's GitHub stats](https://github-readme-stats.vercel.app/api?username=kalila-cc&theme=vue&show_icons=true&hide=prs,issues,contribs&line_height=40)
[![Most Used Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=kalila-cc&layout=compact)](https://github.com/kalila-cc/)

**HOME**

This is my home page in GitHub, and I will keep updating my code works here.<br/>
这里是我的 GitHub 个人主页，我会在此持续更新我的代码项目，欢迎 **Star**。<br/>
有任何问题可以联系作者 (WeChat ID: ChrisTang2021)<br/>

- [仓库](#仓库)
  - [SZU-resources](#szu-resources)
- [软件](#软件)
  - [采昔便签 (CaixiNote)](#采昔便签-caixinote)
  - [易写文件批处理工具 (YixieFileBatchProcessor)](#易写文件批处理工具-yixiefilebatchprocessor)
- [脚本](#脚本)
  - [广告阻拦 (AD Block)](#广告阻拦-ad-block)
  - [力扣助手 (LeetCode Assistant)](#力扣助手-leetcode-assistant)
  - [便捷深大 (Convenient SZU)](#便捷深大-convenient-szu)
  - [UOOC优课联盟助手 (UOOC assistant)](#uooc优课联盟助手-uooc-assistant)
  - [UOOC答案测试器 (UOOC Answer Tester)](#uooc答案测试器-uooc-answer-tester)
  - [气泡信息 (Bubble Message)](#气泡信息-bubble-message)
  - [手机浏览器控制台 (vConsole)](#手机浏览器控制台-vconsole)
- [扩展](#扩展)
  - [Video Enhancement Control](#video-enhancement-control)
- [教程](#教程)
  - [访问 GitHub 配置教程](#访问-github-配置教程)
  - [油猴插件安装教程](#油猴插件安装教程)
  - [傻瓜式配置 C/C++/VSCode (for Windows 10)](#傻瓜式配置-ccvscode-for-windows-10)
- [收藏](#收藏)
  - [编程](#编程)
  - [学习](#学习)
  - [设计](#设计)
  - [其他](#其他)
- [其他](#其他-1)

## 仓库

### [SZU-resources](https://github.com/kalila-cc/SZU-resources)

> 此仓库用于存放SZUer可能会用到的各类资源，希望各位在索取资源的同时能够为该仓库贡献自己的一部分资源，如此才能可持续发展。

## [软件](https://github.com/kalila-cc/electron-vue)

### [采昔便签 (CaixiNote)](https://github.com/kalila-cc/electron-vue/tree/master/CaixiNote)

一个简单而又不简单的桌面便签。

- 添加任务，编辑任务，标为完成，删除任务
- 切换分类（包括：综合，学习，工作，生活，其他）
- 折叠或展开不同时间线的任务
- 置顶顶层，固定顶部，最小化窗口，关闭窗口
- 导出任务长图
- 修改标签样式
- 查看任务月视图
- 底部任务进度条
- 设置关闭窗口个人偏好（前包括最小化到托盘和退出程序，默认为最小化到托盘）
- 切换显示模式（包括列表模式和表格模式，默认为列表模式）
- 切换开机自启动（默认为关闭状态）

### [易写文件批处理工具 (YixieFileBatchProcessor)](https://github.com/kalila-cc/electron-vue/tree/master/YixieFileBatchProcessor)

支持批量处理文件及其属性。

- 支持通过正则匹配过滤文件，并进行批量复制、移动或删除
- 支持通过正则匹配批量重命名文件
- 支持通过正则匹配批量修改 mp3 信息 (如歌手、标题、专辑名称、曲目编号等)
- 支持批量修改 mp3 专辑封面
- 支持提取专辑封面

## [脚本](https://greasyfork.org/zh-CN/users/688946-kalila-cc)

- **此处列举的脚本需要预先在浏览器安装 Tampermonkey 插件**
- 若有个性化定制脚本的需要，可以联系作者

### [广告阻拦 (AD Block)](https://greasyfork.org/zh-CN/scripts/425206-ad-block)

- 移除常见网站广告，优化百度系网站使用体验，优化程序员常用网站使用体验，增加快捷键开启辅助功能。

### [力扣助手 (LeetCode Assistant)](https://greasyfork.org/zh-CN/scripts/432207-leetcode-assistant)

为力扣页面增加辅助功能。

- 首页题库页面
  - 增加**简洁模式**功能，自动隐藏置顶的 "推荐" 和 "学习计划" ，以及右侧的 "精选题单" 和 "热门企业" ，导航栏添加隐藏开关，允许自定义是否隐藏
  - 增加**隐藏已解决**功能，一键隐藏已解决问题，支持取消隐藏
- 题目页面
  - 导航栏
    - 增加**自动调节视图**功能，浏览题目描述时自动调整左侧长度占比 `0.618`，浏览题解时自动调整右侧长度占比 `0.618` ，支持取消自动调整
  - 编辑窗口
    - 增加**复制结构**功能，能够直接复制官方提供的结构类代码[1]，如 `ListNode/TreeNode` 等，避免了手动清除注释的麻烦
  - 题目描述
    - 在每个示例末尾添加**复制示例输入**功能，支持直接复制示例输入为可被语言直接解析的声明语句[2]，避免了手动创建示例输入的麻烦
  - 提交记录
    - 增加**代码复制**功能，无需点击进入提交记录详情页即可实现复制提交代码，点击单条提交记录的 "语言" 项即可复制该条提交的代码，已通过蓝色高亮文字
    - 增加**复制测试输入**功能，提交出现错误时，点击测试输入文本，直接复制测试输入为可被语言直接解析的声明语句[3]
    - 增加**高亮最优提交**功能，自动高亮最优提交记录

### [便捷深大 (Convenient SZU)](https://greasyfork.org/zh-CN/scripts/414662-convenient-szu)

适配深圳大学内部网多个网页的辅助脚本。

- 内部网首页左上角增加 `宿舍用电查询/校园网络续费/登录Dr.com/体育场馆预订/百度文库/下载专区/师资队伍` 入口以及增加绑定个人信息窗口
- 免去进入 `Blackboard/学业完成查询/办事大厅卡片` 的繁琐步骤
- 自动登录 `统一身份认证/Dr.com/办事大厅/Blackboard/校园网络续费` 等页面
- 自动填写需要登陆的页面的账号密码
- 【办事大厅】页面增加【修读课程统计下载】
- 【网上评教】页面增加【一键五星+评价】
- 【成长记录】页面增加【学期专业排名】
- 【学业完成查询】页面增加【彩虹地毯】
- 【宿舍用电查询】页面可自动记忆填写的宿舍信息并可自动显示近 20 天用电记录
- 【公文通】页面可自动记忆选择和填写的信息并增加 `只看学院学部` 选项

### [UOOC优课联盟助手 (UOOC assistant)](https://greasyfork.org/zh-CN/scripts/413268-uooc-assistant)

- 可选是否倍速 (若取消勾选则一倍速播放)
- 可选是否静音 (若取消勾选则恢复原音量)
- 可选是否播放 (若取消勾选则暂停播放)
- 可选是否连播 (若取消勾选则循环播放)
- 离开页面保持视频状态
- 自动回答视频中途弹出问题
- 可复制已提交测验题目及答案
- 键盘左右方向键可以控制视频快进/快退，上下方向键可以控制音量增大/减小，空格键可以控制播放/暂停
- 停止连播支持提醒
- 如果视频标题下面出现 `倍速/静音/播放/连播` 选项说明脚本正常启动运行

### [UOOC答案测试器 (UOOC Answer Tester)](https://greasyfork.org/zh-CN/scripts/419427-uooc-answer-tester)

- 此脚本是通过试错得到 UOOC 测试题的单选题答案，请按照指示进行操作，请注意，此脚本并不能直接得到单选题的正确答案。
- 此方法可行的原因是，小测成功提交的正确率需要在 70% 以上，利用这一点，在单选题较多时可以较大概率保证在试错的时候不会误提交。
- 也就是说，在单选题题量很少的时候，并不适合使用该方法进行试错找答案。

### [气泡信息 (Bubble Message)](https://greasyfork.org/zh-CN/scripts/422854-bubble-message)

- 能够生成悬浮气泡通知，支持自定义：文字信息、默认文字/气泡/icon颜色、默认淡入/淡出/显示时间，默认气泡宽度。

### [手机浏览器控制台 (vConsole)](https://greasyfork.org/zh-CN/scripts/419098-vconsole)

- 在移动端手机浏览器中插入 vConsole 从而调用控制台，使用 via 浏览器进入该页面可添加脚本。

## [扩展](https://github.com/kalila-cc/chrome-extensions)

### [Video Enhancement Control](https://github.com/kalila-cc/chrome-extensions/tree/master/Video%20Enhancement%20Control#instruction)

- Add keyboard shortcut control for video.

## [教程](https://github.com/kalila-cc/tutorial)

### [访问 GitHub 配置教程](https://zhuanlan.zhihu.com/p/366436588)

- 请注意，该教程仅适用于 Windows 系统。

### [油猴插件安装教程](https://zhuanlan.zhihu.com/p/366441874)

- 由于 Greasy Fork 的脚本需要安装油猴（即 Tampermonkey ，一个用于脚本管理的插件）后才能使用，而正规的油猴安装方式因为大家都懂的原因而无法正常安装，因此写了一个简单的油猴插件安装教程。
- 另外，推荐尽可能使用 Chrome 浏览器，因为脚本通常都会适配 Chrome 浏览器，而其他浏览器则不一定能够正常运行脚本。

### [傻瓜式配置 C/C++/VSCode (for Windows 10)](https://github.com/kalila-cc/tutorial/tree/master/VSCode-configuraton-tuterial)

- 傻瓜式配置`VSCode`的`C/C++`环境 (for Windows 10)<br/>
- 由于配置`VSCode`的过程较为麻烦，为了快速配置`C/C++`环境，特地写了一个傻瓜式配置`VSCode`的`C/C++`编译运行环境的教程<br/>

## 收藏

### 编程

- 教程
  - `C/C++`: [C语言中文网](http://c.biancheng.net/)、[菜鸟教程](https://www.runoob.com/)
  - `Objective-C`: [Objective-C教程](https://www.yiibai.com/objective_c)
  - `HTML/CSS`：[W3school](https://www.w3school.com.cn/)、[菜鸟教程](https://www.runoob.com/)
  - `JavaScript`: [The Modern JavaScript Tutorial](https://javascript.info/)、[JavaScript|MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
  - `SQL`：[SQL教程](https://www.w3school.com.cn/sql/index.asp)、[SQLZOO](https://sqlzoo.net/)
  - `MATLAB`：[W3school](https://www.w3cschool.cn/matlab/)
  - `Android`：[Android开发者指南](https://developer.android.com/guide)、[Flutter](https://flutter.cn/)、[React Native](https://www.react-native.cn/)
  - `Git`: [Git教程](https://www.liaoxuefeng.com/wiki/896043488029600)、[Learn Git Branching](https://learngitbranching.js.org/?locale=zh_CN)
  - `Linux`：[Bash脚本教程](https://wangdoc.com/bash/index.html)、[Linux命令大全](https://www.runoob.com/linux/linux-command-manual.html)、[Linux命令大全(手册)](https://www.linuxcool.com/)
  - `WeChat Miniprogram`：[微信开放文档](https://developers.weixin.qq.com/miniprogram/dev/framework/)
  - `Front/Back End`：[React](https://react.docschina.org/docs/getting-started.html)、[Vue.js](https://cn.vuejs.org/v2/guide/)、[webpack](https://webpack.docschina.org/)、[Flask](https://dormousehole.readthedocs.io/en/latest/quickstart.html)、[GitHub Pages](https://docs.github.com/cn/pages)
  - `Chrome Extensions`: [Extensions - Chrome Developers](https://developer.chrome.com/docs/extensions/)
  - `Machine Learning`: [Dive into Deep Learning](http://d2l.ai/)、[动手学深度学习](https://zh-v2.d2l.ai/)
  - `UI`：[View UI](http://v1.iviewui.com/)、[Element UI](https://element.eleme.cn/#/zh-CN)
  - `Common`：[freeCodeCamp](https://www.freecodecamp.org/)、[廖雪峰的官方网站](https://www.liaoxuefeng.com/)、[菜鸟教程](https://www.runoob.com/)
- IDE
  - `C/C++`：[Dev-C++](https://sourceforge.net/projects/orwelldevcpp/files/latest/download)、[VSCode](https://code.visualstudio.com/)、[Clion](https://www.jetbrains.com/clion/download/)
  - `Python`：[Pycharm](https://www.jetbrains.com/pycharm/download/)
  - `Java/Kotlin`: [intelliJ IDEA](https://www.jetbrains.com/idea/download/)
  - `Web`：[WebStorm](https://www.jetbrains.com/webstorm/download/)
  - `Android`：[Android Studio](http://www.android-studio.org/)
  - 微信小程序：[微信开发者工具](https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html)
- 扩展
  - `VSCode`
    - `TabNine`：Advanced AI based autocomplete for all programming languages.
    - `Bracket Pair Colorizer`：This extension allows matching brackets to be identified with colours.
    - `Code Runner`：Run code snippet or code file for multiple languages.
    - `Panda Theme`：A Superminimal, dark Syntax Theme.
    - `VSCode Great Icons`：A big pack of icons (100+) for your files.
    - `Live Server`：Launch a local development server with live reload feature for static & dynamic pages.
    - `Auto Rename Tag`：Auto rename paired HTML/XML tag.
    - `Draw.io integration`: This unofficial extension integrates Draw.io into VS Code.
    - `Markdown All in One`: All you need for Markdown (keyboard shortcuts, table of contents, auto preview and more).
  - `Chrome`
    - `Tampermonkey`：The world's most popular userscript manager.
    - `Dark Reader`：Dark mode for every website. Take care of your eyes, use dark theme for night and daily browsing.
- 算法
  - 教程：[OI Wiki](https://oi-wiki.org/)
  - 可视化：[VisuAlgo](https://visualgo.net/zh)、[Data Structure Visualizations](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html)
- 问答：[CSDN](https://www.csdn.net/)、[简书](https://www.jianshu.com/)、[博客园](https://www.cnblogs.com/)、[Stack Overflow](https://stackoverflow.com/)
- 代码格式化：[C语言代码格式化](http://www.jsons.cn/clanformat/)、[HTML/CSS/JSON/JavaScript/Java/SQL格式化](https://tool.oschina.net/codeformat/json/)
- 代码转换：[ES6 Console](https://es6console.com/)、[Babel](https://babeljs.io/repl)
- 代码分享：[Ubuntu Pastebin](https://paste.ubuntu.com/)
- 代码截图：[Carbon](https://carbon.now.sh/)
- 在线开发环境：[C语言开发环境](https://clin.icourse163.org/)、[菜鸟工具](https://c.runoob.com/)、[Objective-C在线编辑器](http://www.dooccn.com/objective-c/)、[Data Science Workshop](https://dsw-dev.data.aliyun.com/#/)、[Colaboratory](https://colab.research.google.com/notebooks/intro.ipynb)
- 题库：[PAT](https://www.patest.cn/practice)、[洛谷](https://www.luogu.com.cn/problem/list)、[力扣](https://leetcode-cn.com/problemset/all/)、[牛客网](https://www.nowcoder.com/activity/oj)
- 工作：[腾讯文档](https://docs.qq.com/desktop/)、[腾讯工蜂](https://git.code.tencent.com/)、[飞书](https://www.feishu.cn/)、[超级简历WonderCV](https://www.wondercv.com/)
- 其他：[Unicode](https://www.compart.com/en/unicode/)、[站长工具](https://seo.chinaz.com/)、[编码查看转换工具](http://www.mytju.com/classcode/tools.asp)、[DNS查询](https://myssl.com/dns_check.html)

### 学习

- 问答：[百度](https://www.baidu.com/)、[知乎](https://www.zhihu.com/)、[哔哩哔哩](https://www.bilibili.com/)
- 翻译：[Google 翻译](https://translate.google.cn/)、[有道翻译](http://fanyi.youdao.com/)、[百度翻译](https://fanyi.baidu.com/)
- 绘图：[幕布](https://mubu.com/home)
- 数学：[Desmos](https://www.desmos.com/calculator?lang=zh-CN)、[WolframAlpha](https://www.wolframalpha.com/)、[LaTeX公式编辑器](https://www.latexlive.com/)

### 设计

- 图标：[iconfont](https://www.iconfont.cn/)
- 色彩：[520设计网](https://www.sj520.cn/)、[网页渐变色](https://www.sj520.cn/tools/jianbian3/)、[SpyColor](https://zh.spycolor.com/)、[Color Claim](https://vanschneider.com/colors)、[ColorHexa](https://www.colorhexa.com/)、[uiGradients](https://uigradients.com/)、[RGB配色表](http://www.wahart.com.hk/rgb.htm)、[RGB颜色查询](https://www.fontke.com/tool/rgb)
- 字体：[艺术字体转换器](http://www.akuziti.com/)、[Text to ASCII Generator](http://patorjk.com/software/taag/)
- 曲线：[cubic-bezier](https://cubic-bezier.com/)
- 软件：[CorelDRAW](https://www.coreldraw.com/cn/)、[Adobe Illustrator](https://www.adobe.com/cn/products/illustrator.html)、[墨刀](https://modao.cc/)

### 其他

- 文件
  - 文件解压缩：[360压缩](https://yasuo.360.cn/)
  - 文件格式转换：[格式工厂](http://www.pcgeshi.com/)
  - 文件类型查询：[延伸档名数据库](https://www.filedesc.com/zh/)
  - 磁盘空间嗅探：[SpaceSniffer](https://www.fosshub.com/SpaceSniffer.html)
- 图片
  - 图床：[路过图床](https://imgchr.com/)
  - 二维码：[草料二维码](https://cli.im/)
  - 图片彩色化：[Colorize](https://demos.algorithmia.com/colorize-photos)
  - 图片高清化：[Let's Enhance](https://letsenhance.io/)
- 软件
  - 浏览器：[Chrome](https://www.google.cn/chrome/)
  - 亮度调节：[Dimmer](https://github.com/danielng01/product-builds/tree/8498b28f9d5fade26a3263e5304072d3c877ed65/competitors/blue-light/Dimmer)
  - 截屏：[Snipaste](https://www.snipaste.com/)
  - 录屏：[Captura](https://github.com/MathewSachin/Captura)
  - Markdown：[Typora](https://typora.io/)
- 视频
  - 动漫：[樱花动漫](http://www.imomoe.la/)、[233动漫网](https://www.dm233.cc/)、[樱花风车动漫网](https://www.8666.tv/index.php)
  - 影视：[天狼影视](https://m.ttll.tv/)、[电影天堂](https://www.dytt8.net/index.htm)
  - 提取：[Twitter Video Downloader](https://twittervideodownloader.com/)
- 网络
  - 测速：[Speedtest](https://www.speedtest.net/)、[测速网](https://www.speedtest.cn/)
- 手机
  - 调节配置：[adb](https://developer.android.com/studio/releases/platform-tools)、[adb文档](https://developer.android.com/studio/command-line/adb)

## 其他

- **小爱同学课程表APP**已适配**深圳大学本科生**课程表，欢迎深圳大学本科生前往各大应用商店搜索下载使用（仅 Android 可正常导入课程表）
