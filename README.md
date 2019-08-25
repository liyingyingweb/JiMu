# jimu

## 前言


    初学vue时曾在网上搜索vue的实战项目源码，无奈大部分都是简单的demo，对于深究vue没有太大的帮助，剩下的一些大部分都是像音乐播放器之类的展示型项目，交互没有预期那么复杂。
    
    但我们实际在工作中，经常会遇到对逻辑严谨度要求高，页面之间交互复杂，又会伴随着登录、注册、用户信息等等，常常会让我们很头疼。
    
    既然还没人用vue写过这样的项目，那不如我用业余的时间来写。
    
    所以打算做一款社交类软件，积目成为首选，专属年轻人的社交平台。
    
    此项目大大小小共 30 个页面，涉及注册、登录、交友、社区、聊天、匹配等等，是一个完整的流程。一般公司即便是官网的单页面项目都没这么复杂，如果这个项目能驾驭的了，相信大部分公司的其他单页面应用也就不在话下，即便更复杂，也不会比这个高到哪里去。
    
    因为利用业余时间来做，周期有点长，项目从零布局。
    
    **注：此项目纯属个人瞎搞，正常积目交友请选择积目官方客户端。**


## 技术栈

vue3 + vuex + vue-router + framework7 + ES6/7 + sass + flex + svg


## 项目运行

```
git@github.com:bishaolong/JiMu.git

cd jimu

npm install

npm run serve

npm run build

```

## 说明

    如果对您有帮助，您可以点右上角 "Star" 支持一下 谢谢！ ^_^

## 效果演示

[演示](http://oano.cn/bsl/dist/)

手机扫码演示

![QQ截图20190825230710](E:\JC5ZH\Vue\Vue-jimu\jimu\src\assets\screenshots\QQ截图20190825230710.png)



[可下载 安装包]( https://service.dcloud.net.cn/build/download/e3329460-c74a-11e9-822e-d5f5328d6e9b)


## 目标 功能

    -卡牌效果
    
    -视屏效果
    
    -筛选
    
    -共鸣
    
    -共鸣筛选
    
    -共鸣提示
    
    -我的
    
    -编辑资料
    
    -系统设置
    
    -弹幕管理
    
    -喜欢我
    
    -我的卡牌
    
    -个性标签
    
    -我的内容
    
    -我赞过的
    
    -喜欢的活动
    
    -社区
    
    -全部
    
    -同城
    
    -好友
    
    -录制
    
    -收到的评论
    
    -不同类型切换
    
    -对话
    
    -距离
    
    -匹配

## 总结

    1.因为并不是jimu官方，而且因为要开代理，必须在pc端打开
    
    2.vue因其轻量级的框架在中小型项目中表现亮眼，在大型单页面应用中因为vuex的存在，表现依然出色，在处理复杂交互逻辑的时候，vuex的存在是不可或缺的。所以说利用 vue + vuex 完全可以去做大型的单页面项目。
    
    3.项目写到现在，从 登录注册到、首页、共鸣、社区列表、对话、个人中心 一个流程走完之后、不但对vue的理解更深一层，而且对以后掌控大型项目的时候也有非常多的帮助，做一个实际的项目才能对自己有很大的提升。
    
    4.曾一度怀疑，花几个月的时间做这样一个项目到底有没有意义，本来只是想做一个小项目练练手，没想到后来越写越多，不过坚持下来后我相信一切都是值得的。

## 最终目标

    1.用node.js构建一个模拟数据的后台系统。
    
    2.写出跨 Android 和 IOS 的原生APP版本。
    
    3.所以我的目的是构建一个横跨前后端，移动IOS、Android的完整生态圈。
    
    4.敬请期待

## 部分截图

### 主页截图

![1566738180(1)](E:\JC5ZH\Vue\Vue-jimu\jimu\src\assets\screenshots\1566738180(1).jpg)![GIF](E:\JC5ZH\Vue\Vue-jimu\jimu\src\assets\screenshots\GIF.gif)



### 共鸣截图

![QQ截图20190825210318](E:\JC5ZH\Vue\Vue-jimu\jimu\src\assets\screenshots\QQ截图20190825210318.png)



### 我的截图



![QQ截图20190825210334](E:\JC5ZH\Vue\Vue-jimu\jimu\src\assets\screenshots\QQ截图20190825210334.png)



### 对话截图

![QQ截图20190825210344](E:\JC5ZH\Vue\Vue-jimu\jimu\src\assets\screenshots\QQ截图20190825210344.png)



### 社区截图

![QQ截图20190825210354](E:\JC5ZH\Vue\Vue-jimu\jimu\src\assets\screenshots\QQ截图20190825210354.png)![GIF2](E:\JC5ZH\Vue\Vue-jimu\jimu\src\assets\screenshots\GIF2.gif)



## 项目布局

    |—— dist                                        //项目打包生成文件
    |—— node_modeules                               //依赖
    |—— public                                      //公共文件
    |—— src                                         //源码目录 
    |   |—— assets                                  //项目图片
    |   |   |—— figure                              //卡牌
    |   |   |—— images                              //项目各类素材
    |   |   |—— portrait                            //社区
    |   |   |—— screenshots                         //项目部分截图
    |   |—— components                              //组件
    |   |—— css                                     //样式
    |   |—— fonts                                   //Framework7文件
    |   |—— js                                      //js文件
    |   |—— pages
    |   |—— views
    |   |   |—— community                           
    |   |   |   |—— index.vue                       //社区页
    |   |   |—— dialogue
    |   |   |   |—— index.vue                       //对话页
    |   |   |—— home
    |   |   |   |—— index.vue                       //卡牌页
    |   |   |—— me
    |   |   |   |—— index.vue                       //个人中心页
    |   |   |—— resonance
    |   |   |   |—— index.vue                       //共鸣页
    |   |—— App.vue                                 //app 首页
    |   |—— main.js                                 //入口文件
    |   |—— routes.js                               //路由
    |—— .gitignore                                  //忽略文件
    |—— package.json                                //json文件
    |—— README.md                                   //说明文档
    |—— vue.config.js                               //配置文件
