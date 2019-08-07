#购物商城
###一 制作首页APP组件
* 1.完成Header区域，使用的是Mint-UI中的Header组件
* 2.制作底部的Tabbar区域，使用的是MUI的 Tabbar.html
  + 在制作购物车的小图标的时候，操作会相对多一些
  + 先把扩展图标的 css 样式，拷贝到项目中
  + 再拷贝扩展字体库 ttf文件到项目中
  + 为 购物车 小图标，添加如下的样式‘mui-icon mui-icon-extra mui-icon-extra-cart’ 
* 3.要在中间区域放置一个router-view 来展示路由匹配到的组件
#### 改造 tabbar 为 router-link
#### 设置路由高亮
#### 点击tabbar 中的路由连接，展示对应的路由组件
### 二 制作手写轮播图数据
+ 1.获取数据，获取数据的方法 vue-resource
+ 2.使用vue-resource 的 this.$http.get 获取数据
+ 3.获取到的数据，哟啊保存到data身上
+ 4.使用v-for 循环渲染没一个item项
#### 改造九宫格区域的样式，九宫格中的样式在MUI的grid中找