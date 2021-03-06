# 魔众文章投稿系统

魔众文章投稿系统是一个多用户文章管理系统，支持用户文章投稿、文章审核，通过评论、打赏等模块可以轻松支持多种用户营销功能。

## 运行环境


```
操作系统
Linux/Unix 或&nbsp;&nbsp;Windows
软件环境
Laravel 5.1的运行环境
Apache/Nginx , PHP 5.5.9+ / PHP 7.0 , MySQL 5.0+
```

## 系统截图


### 

![](https://mz-assets.tecmz.com/data/image/2021/11/26/60503_ktkz_6137.png)


### 

![](https://mz-assets.tecmz.com/data/image/2021/11/26/60504_cozm_3851.png)


### 

![](https://mz-assets.tecmz.com/data/image/2021/11/26/60504_2f6j_8177.png)


### 

![](https://mz-assets.tecmz.com/data/image/2021/11/26/60505_o0nt_9344.png)


### 

![](https://mz-assets.tecmz.com/data/image/2021/11/26/60660_hb7c_9583.png)


### 

![](https://mz-assets.tecmz.com/data/image/2021/11/26/60660_pioc_8436.png)


### 

![](https://mz-assets.tecmz.com/data/image/2021/11/26/60661_vevi_3322.png)



## 版本迭代



### V1.8.0

**发布时间**：2022-07-07

- [新功能] 安全检测新增安装向导文件删除检测
- [新功能] 用户登录页面样式优化调整
- [新功能] 静态资源打包新增文件类型
- [新功能] 用户默认登录方式可切换用户名密码或手机验证码
- [新功能] 手机验证码快捷登录方式
- [新功能] 富文本图片编辑宽高为空时自动清除图片宽度和高度
- [新功能] 用户登录跳转URL安全验证可配置
- [新功能] 创建文件夹失败时记录日志
- [新功能] 手机验证码快捷注册方式
- [新功能] 账号删除功能，后台可手动删除用户
- [新功能] 注销账号功能，用户可主动申请注销账号
- [新功能] 用户积分名称全局可修改
- [新功能] 接口不存在时提示显示接口路径
- [新功能] 用户中心微信小程序授权绑定逻辑优化调整
- [新功能] 后台用户列表新增授权登录标记
- [新功能] 后台管理用户批量禁用账户的功能
- [新功能] 后台管理用户信息查看列表新增用户ID
- [系统优化] Grid 文件预览显示优化
- [系统优化] 文件显示多语言显示优化
- [系统优化] 后台登录验证码缓存问题
- [系统优化] 用户消息发送模板查找逻辑升级
- [系统优化] 调整用户设置相关菜单到用户中心
- [系统优化] 用户授权登录OpenId绑定key逻辑
- [系统优化] UEditorPlus升级为v2.2.0
- [系统优化] 字符串工具类中的特殊字符处理重复
- [Bug修复] Form 新增规则校验失效问题
- [Bug修复] 静态资源JS打包异常时文件没有复制问题



### V1.7.0

**发布时间**：2022-06-03

- [新功能] 富文本过滤新增HTML5标签
- [新功能] 启用富文本UEditorPlus
- [新功能] 用户登录完成默认跳转到用户中心
- [新功能] 接口异常友好提示
- [新功能] 默认支持webp图片文件格式
- [新功能] 用户名最少3个字符限制
- [新功能] Hook新增DialogPageHeadAppend和DialogPageBodyAppend
- [新功能] 模块目录非法时自动过滤
- [系统优化] 接口异常返回信息提示
- [系统优化] 文件上传获取路径为空问题
- [系统优化] 配置值为空时缓存设置和存储优化
- [系统优化] 搜索框样式优化，优化Grid列表样式和Tab样式



### V1.6.0

**发布时间**：2022-05-04

- [新功能] 模块市场登录增加微信扫一扫
- [新功能] 404页面和500错误页面美化升级
- [新功能] 系统初始化安装引导文件升级
- [新功能] 系统升级文件写入权限检查校验
- [新功能] UEditor支持本地视频插入
- [新功能] 管理日志列表增加管理员字段
- [新功能] 日志新增Rotate特性，避免历史日志堆积
- [新功能] 后台问题反馈调整为新Tab显示
- [系统优化] 内容增加/编辑默认遮罩层点击不关闭
- [系统优化] Select组件Key不存在时候友好显示
- [系统优化] Env文件解析功能优化
- [系统优化] 富文本编辑器添加视频小屏适配
- [系统优化] 富文本编辑器图片可配置对其方式，可二次编辑
- [系统优化] 富文本HTML行高显示，大字体显示异常
- [系统优化] 文件选择组件显示样式优化
- [Bug修复] 管理菜单为URL时不能自动定位当前
- [Bug修复] 模块卸载版本检测失效问题



### V1.5.0

**发布时间**：2022-03-31

- [新功能] UEditor 粘贴图片自动上传功能
- [新功能] 后台应用概况显示系统名称
- [新功能] 用户中心新增退出登录
- [新功能] 图标大小统一调整优化
- [系统优化] 后台界面显示优化升级
- [系统优化] 优化弹窗重复导入的异常问题
- [系统优化] 表格无数据时内容优化（增加图标）
- [系统优化] 表格刷新自动跳转到顶部优化
- [系统优化] 标签样式显示方式
- [系统优化] 上传错误时显示提醒错误信息
- [Bug修复] Grid筛选条件部分失效问题
- [Bug修复] 文件选择弹窗自定义输入链接不生效问题
- [Bug修复] 后台链接选择同类别不能自动合并问题
- [Bug修复] 后台浮动确定区域左侧宽度问题调整



### V1.4.0

**发布时间**：2022-03-01

- [新功能] Banner批量删除功能
- [新功能] 二级导航功能
- [新功能] 导航批量删除功能
- [新功能] 导航位置Tab切换
- [新功能] 本地模块筛选Tab，只显示本地模块
- [新功能] 可升级模块筛选，显示系统可升级的模块
- [新功能] 文件上传事件触发 DataFileUploadedEvent，增加 DriverName
- [新功能] 管理员登录成功、登录失败、退出事件触发
- [系统优化] GridFilter 下拉选择、单选匹配逻辑优化
- [系统优化] 长请求监控、长SQL监控、多SQL请求监控
- [系统优化] 表单页面组件overflow显示优化
- [系统优化] Decimal 组件不能为负数问题
- [系统优化] Detail 记录不存在显示问题
- [Bug修复] 用户后台VIP列表修改不生效问题修复



### V1.3.0

**发布时间**：2022-01-29

- [新功能] 后台菜单快捷搜索（支持汉字、简拼、全拼）
- [系统优化] 字段渲染模式异常捕获
- [系统优化] 状态组件显示优化
- [系统优化] 普通表单提交Loading优化
- [系统优化] 后台自动升级Token存储优化
- [Bug修复] 自定义字段详情显示异常问题
- [Bug修复] 修复已知若干问题



### V1.2.0

**发布时间**：2021-12-31

- [新功能] 轮播文字内容新增动画
- [新功能] 后台菜单一键展开所有菜单功能
- [新功能] 数据表格列未设置宽度自动适配
- [新功能] 默认文章封面，可以根据文章ID随机取一张默认文章封面
- [新功能] 文件选择弹窗增加文件链接复制功能
- [新功能] 安装助手新增显示应用名称和版本
- [新功能] 新增富文本显示优化
- [新功能] 会员隐私协议可配置
- [系统优化] 字段ID默认固定宽度去除
- [系统优化] 视图查找顺序重构优化
- [系统优化] 富文本内容视频显示优化
- [系统优化] 完成网站ICO图标更新
- [Bug修复] 顶部导航Logo手机端高度适应问题



### V1.1.0

**发布时间**：2021-12-08

- [新功能] 升级页面登录内容优化
- [系统优化] 新增模块时系统自动升级优化
- [系统优化] 富文本前台iframe显示尺寸优化
- [系统优化] 后台管理框架Logo显示
- [系统优化] 清理Laravel优化文件缓存
- [系统优化] 页面SEO全面优化
- [系统优化] 小窗口表单显示边距调整
- [系统优化] 文章系统展示SEO优化
- [Bug修复] 快速CRUD中hookSaving调用异常
- [Bug修复] 前端UrlEncode为数字时处理异常



### V1.0.0

**发布时间**：2021-11-05

- [新功能] 初版发布


## 演示地址

[https://writer.demo.tecmz.com/](https://writer.demo.tecmz.com/)

## 下载试用

[http://tecmz.com/product/writer](http://tecmz.com/product/writer)