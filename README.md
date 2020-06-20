🍉 本项目已打包，查看效果请单独下载dist文件夹，使用Chrome + iPhone X 模拟浏览更佳 🍉
 <br>
 <br>
 
 
 ![image](http://m.qpic.cn/psc?/V11E9jQr163cUb/UVjGSBgujG6XwMFsQlvXRYXplMsRO1TlpXlPZtf5cMWqGpYXp4iD9qrsV674uduxBnf.TS0OC31XlnPWAo14qQ!!/b&bo=ygWAAlsHLQMDCRM!&rf=viewer_4)
 <br>
 <br>


### 面试作业：

>#### 学习VUE框架和UI库，调用提供的接口数据，编写淘宝H5页面，包括首页、商品详情页、我的淘宝。
>
>- 像素级还原淘宝移动端网页，高度还原了首页、商品详情页的功能，且基本模拟出购物车、地址列表的页面效果。
>- 整个项目组件化思想完成较好，在有限的时间内尽可能地将每一个功能模块封装成组件，且注重数据的动态渲染，为接口保留延展性。
>- 初学Vue + 制作项目共 7 天时间，从无到有地掌握了VUE框架、VantUI的基本使用，对组件化开发有了更深的了解，目前对VUE生命周期、组件通信、VUEX状态管理有极大的学习兴趣，期待接下来的进一步学习。
>- 本项目对全部组件进行了完整而精细的注释，即使是前端初学者也可以迅速通过项目结构和注释快速了解VUE框架开发模式，另一方面，便于本人日后对此项目的完善，日后时间充沛会对本项目进行深层次地开发完善。


 <br>
 <br>
 
 
### 项目详情：

>#### 技术选型：
>
>- Vue +  Vue CLI + VueRouter + Vant UI(有赞) + rem适配布局等
>
>#### 各页面组件构成：
>
>- 全局
>  - 底部Tabbar跳转组件（购物车页面隐藏）
>- 首页
>  - 顶部搜索组件（点击触发顶部弹框组件）
>  - 轮播图组件
>  - Gird宫格多功能入口组件
>  - 聚划算、有好货等会场入口组件
>  - 淘宝头条纵向轮播组件（此组件有时加载不成功，可尝试刷新页面，暂未查明此bug原因）
>  - 商品推荐列表组件（包括下拉页底加载更多）
>  - 返回顶部组件
>- 商品详情页
>  - 主图轮播组件（包括点击放大预览）
>  - 顶部返回、购物车按钮
>  - 商品描述信息组件
>  - 服务、规格、参数横栏组件（点击触发页底弹框组件）
>  - 宝贝评价、问大家组件
>  - 详情、商品推荐入口分隔栏组件
>  - 商品详情长图组件
>  - 详情结束推荐更多商品组件
>  - 底部加入购物车、立即购买等横栏组件
>- 购物车（本页面仅做界面还原，功能实现待开发）
>- 地址列表（本页面仅做界面还原，功能实现待开发）
>- 我的淘宝（本页面仅做界面还原，功能实现待开发）
>- 更多（此页面官网为多种外部链接，这里贴入本人WeChat二维码）
>
>#### 其他功能：
>
>- 页面跳转前位置保留
>  - 首页滑动至商品列表时，点击任一商品跳转至详情页，此时点击顶部返回按钮，可再次回到首页跳转前的位置，涉及到组件keeplive状态保存、生命周期等知识。
>- 移动端rem适配 + 电脑端同时适配（最大宽度750px，最小宽度320px）+ 居中对齐
>  - 本项目在淘宝移动端触屏版（非App）的基础上进行了优化，将所有页面进行了针对性的rem布局，不会出现官网存在的扩大屏幕尺寸后各组件宽度不统一、非居中对齐等缺点。
>  - 页面在rem适配上表现较好，可适配各种移动端设备，同时支持电脑端查看，在不使用chrome调试工具模拟移动设备的情况下，界面最大宽度750px防止元素过大，最小宽度320px防止继续缩放文字排版失真，基本上做到了完美适配PC、平板、手机三端用户。

 <br>
 <br>


### 运行方法：

> - 查看效果
>   - 下载 dist 文件夹，解压后使用 chrome 浏览器调试工具 iPhone X 机型浏览最佳
> - 运行项目
>   - 下载依赖  npm install 
>   - 启动项目  npm start

 <br>
 <br>


#### **🐕感谢您的阅读🐕**
