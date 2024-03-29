# HeiFUN更新日志

```
记录 | 白隐Hakuin 

说明:
1. 版本号编排：主版本号.子版本号.修正版本号+APP阶段状态后缀+(内部版本号)+主要更新内容
2. 灰色更新条目为计划更新，暂未实施
3. 所有历史版本及启动图都会保存在[GitHub](https://github.com/Hakuin123/HeiFUN/releases)
```
# HeiFUN 2.0.0 船新版本！！！
### HeiFUN本体
- **对1.x版本全部功能使用FA2重写**
- 移除一些弃用的子页面并替换功能
- 界面部分图标翻新
- 应用图标优化显示（感谢@幽雅 进行图像处理）
- 完善大量官方文档及基于GitHub Pages的官网建设
- 新增Toiuh特供版（船新绘制logo）
- 项目提交至GitHub
- 实施工程文件3-2-1备份
- 累计代码行数破千qwq

### 主界面
- 船新启动欢迎页
- 离屏预加载1页
- 多浏览页用户滑动开启（与2048不冲突）
- 多浏览页丝滑的“纸片”切换动画
- 一键跳转签到页，打卡更方便啦
- 子标题100句随机变换！还有彩蛋～（已实装）
- 采用全新书签&历史记录功能（but卸载后清空数据，可导出）
- 侧滑栏新增由@Toiuh 绘制的船新logo
- 侧滑栏按照实际使用场景判定是否收回
- 新增启动APP自动检查更新～不用手动翻啦
- “官方Q群”改版为列表式，直接跳转QQ
- 新增夜晚休息提醒（22:14～次日6:00）
- 休息提醒界面翻新
- 新增咕咕助手，直观计算拖更日期
- [ ] 新增论坛维护提示，检测到论坛站点出现错误时给出提示
- 新增[HeiCaO彩蛋](https://heifun.hk256.top/docs/HeiCaOの诞生.png)诶嘿嘿
- 解决了SSL证书错误导致的闪退问题

### 关于页
- 重新设计排版
- “关于信息”直接显示为版本号，轻点三次跳转系统设置关于设备
- [ ] 新增“调试模式”，内置开发者选项
- 新增“导出应用数据”至sdcard/HeiFUN
- [ ] 新增“应用信息”，跳转系统设置应用信息
- 复刻“更新日志”
- 合并“历史版本”
- 新增“你知道吗”
- 新增“GitHub项目地址”
- “打小报告”翻新为“反馈与建议”
- 新增“常见问题”
- 新增“提交issue”
- 新增“联系我们”

---

# HeiFUN 1.x

## 1.4.1(221005) 修复链接
- 关闭页面滑动功能，因为玩不了2048🤔
- 修正“罗小黑2048”对应链接
- 关于页新增“检查更新”
- 侧滑栏新增“你知道吗”
- 侧滑栏新增“GitHub项目地址”
- 关于页官网地址更新，新增“旧版官方网站”
- 内部版本号更改编码方式（别担心，向后兼容）

## 1.4.0(202208) 功能完善
- 增加“自由复制”功能，跳转复制
- 全部子页面一键退出（除追番页面）
- 添加终止支持提醒
- “BETA公测”按键删除（已退出公测阶段）
>相应彩蛋藏到“关于”页的“关于信息”啦～
- “离线帖子编辑”（从未上线）功能弃坑  原因：做不出来
- “水帖”顶替“妖灵日报”移到主页～做任务更方便耶(=•ω＜=)
- “没事干”改成大佬@迷茫的嘉鸿 制作的罗小黑2048
- 深色模式的说明没那么危言耸听了XD
- ~~移除了Herobrine（不是~~
- 搜索功能的bug…由于论坛采用Discuz的动态搜索，所以修不了，求饶qaq
- HeiFUN 1.x系列源代码**开源啦**！

```
注意：1.x版本日后将不再受支持。出现重大bug和需要重量级功能的情况下才会更新。敬请早日更换到2.x版本，体验更多功能～长期支持～
另，咕了很长时间，抱歉。作者是学生，现在初三党，学业繁重。日后更新可能日渐缓慢，敬请谅解。
```

## 1.3.0BETA(202109) 深色＋鸿蒙
- **深色模式**重磅上线！
- “签到”链接更新（叶子换了签到discuz插件）（但是我后来发现并没有更新QwQ）
- 完成了对**HarmonyOS设备**的兼容性检查
- 完成了对平板电脑设备的兼容性检查
- 顶栏菜单项目增加了个~~新奇的~~[小玩意儿](https://aidn.jp/mikutap)

*由于未知错误，此版本无启动图QwQ

## 1.2.0BETA(202108) 优化体验
- 默认打开PC版页面，使用体验大幅度提升
- 优化了应用图标，强迫症狂喜（终于改了）
- “追番TV版”优化，隐藏B站广告 [插件原链接](http://via-app.cn/#/pluginDetail/67)
- 顶栏图标按钮“BETA公测”移到侧滑栏
- “清理缓存”功能出现异常，故删除
- 更改了“历史版本”百度网盘链接
- 增加启动图啦～ 
>Tips：可以在“历史版本”>文件夹“画廊”看到历史所有的启动图QwQ
- 作者老家发洪水，天佑河南加弹窗

## 1.1.0BETA(202107)技术救世！
- 庆祝共产党百年华诞！主题启动弹窗得有吧？
- 精简了内部版本号[^1]
- 修改“关于”页面元素[^2]
- 众生之门功能导流（game.heibbs.net）
- 论坛API功能导流（open.heibbs.net）
**庆祝吧！欢呼吧！作者喜提论坛技术组offer啦！**

[^1]: 当初在确定固定的更新频率（每月5日）后，我们做出了这个决定
[^2]: “作者大大BLOG”移除，本人不习惯用博客（QQ空间它不香吗2333）<br/>反馈功能导向从兔小巢换为腾讯文档收集表，兔小巢反馈通道同步关闭。主要是为了信息大一统（当初主要使用腾讯文档）


## 1.0.1BETA(20210605)细节优化
- 无奈地把所有历史版本搬进了百度网盘，顺手修正了历史版本的链接
- 高考加油！添加了个加油推送
- 修复了每次网页加载完毕就会弹出“若网站错误的话请点击三个点的通知窗口”的bug，已经改为泡沫对话框 抱歉影响体验惹QwQ
>感谢论坛妖精@gongzhihaosh(UID: 1631)的批评指正！[在这个帖子里的12楼](https://www.heibbs.net/forum.php?mod=redirect&goto=findpost&ptid=1586&pid=34660)～同时兔小巢也有匿名反馈，一并感谢！
![兔小巢反馈截图](/docs/兔小巢反馈截图.png)

## 1.0.0BETA(20210505) 爆炸更新
- “清理缓存”图标更改，代码去除多余空行
- “官方Q群”更名为“罗小黑官方Q群”，顺序优化，群名小改；添加帮助，可直达QQ更新下载
- “电脑UA”进行翻新，并更名为“浏览器UA标识”，添加提示
- 欢迎使用弹窗更改
- 部分页面措辞调整
>注：此版本与0.9.9ALPHA功能几乎一致，故合并在此，而后者采用了非常不方便的下载量统计功能

## 0.2.0ALPHA(20210125) 丰富功能
- 创建底栏项目“一键追更”
- 添加“”ALPHA内测”按钮的彩蛋（戳一下试试？）
- 添加顶栏菜单项目“”综合帮助”及其提醒弹窗
- 添加侧边栏项目“历史版本”
- 添加侧边栏项目“检查更新”
- 添加侧边栏项目“清理缓存”
- “关于”页面大改，直接跳转至“官网”（腾讯文档）并丰富功能
- 搜索功能名副其实，转为百度对站内进行搜索

## 0.1.0ALPHA(20210121) 树立架构
- 创建底栏“主页”“签到”“妖灵日报”“我的”（后三项未实装）
- 创建顶栏搜索（必应）
- 创建模块“官方Q群”“关于”
- 创建电脑UA（横屏）
- 创建顶栏项目“ALPHA内测”
- 创建更多操作“刷新”“使用IP地址访问”
- 创建欢迎使用相关消息
- ……
>PS：此版本是第一个正式版。

## 0.1.0 框架搭建
- 搭建主体框架
- 更多项目已和0.1.0ALPHA合并，请自行体验。
>PS：此版本是第一个版本（非正式版），谨以此铭记历史。
