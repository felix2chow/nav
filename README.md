
<p align="center">
  <a href="https://门户.网站">
    <img src="src/assets/logo.png" width="130" />
  </a>
  <br />
  <a href="https://门户.网站"><b>https://门户.网站</b></a>
    <br />
    <br />
    <a href="https://github.com/xjh22222228/nav"><b>原版来源“ xjh22222228/nav”
</b></a>
  一个纯静态、支持SEO、在线编辑的强大导航网站，希望您会喜欢 
 
  
</p>


## ！！！配置的重点：
1、nav.config.ts 文件：  
``` bash
// [必填], 请填写您的仓库地址
  gitRepoUrl: 'https://github.com/xjh22222228/nav',
```
2、后台导出导入db.json会导致部署失败,解决方案：
``` bash
把data/db.json里代码剪切出去用json格式化工具格式化一遍，然后粘贴回去保存
```
3、后台设置网站logo报错错误: 404，上传失败，请重试！，
``` bash
1、data/settings.json 里修改  "favicon": "https://cdn.jsdelivr.net/gh/xjh22222228/nav@image/logo.png",
2、search.json 里修改  "icon": "https://raw.sevencdn.com/xjh22222228/nav/image/logo.png",
```


## 升级
在升级之前请备份根目录下的 `data` 文件夹和 `nav.config.ts`, 升级完后替换即可。

点击右上角 `Watch` 按钮第一时间跟踪版本升级。


## 预览
**主题**

- [Sim 在线预览](https://nav3.cn/#/sim)
- [Light 在线预览](https://nav3.cn/#/light)
- [Side 在线预览](https://nav3.cn/#/side)
- [App 在线预览](https://nav3.cn/#/app)

![Preview](https://raw.githubusercontent.com/xjh22222228/public/gh-pages/nav/1.png)
![Preview](https://raw.githubusercontent.com/xjh22222228/public/gh-pages/nav/2.png)
![Preview](https://raw.githubusercontent.com/xjh22222228/public/gh-pages/nav/3.png)
![Preview](https://raw.githubusercontent.com/xjh22222228/public/gh-pages/nav/4.png)
![Preview](https://raw.githubusercontent.com/xjh22222228/public/gh-pages/nav/5.png)






## 特性
`发现导航` 的理念就是做一款无需依赖后端服务既简单又方便，没有繁杂的配置和数据库等配置概念, 做到开箱即用。

- 🍰 内置 `800+` 实用网站。
- 🍰 支持 SEO。
- 🍰 完全纯静态, 提供自动化部署功能。
- 🍰 三叉树分类、结构清晰、分类清晰。
- 🍰 支持一个网站关联多个网址
- 🍰 颜值与简约并存，不再是杀马特时代。
- 🍰 完全开源，轻松定制化。
- 🍰 支持多种浏览模式，创新。
- 🍰 支持足迹记忆。
- 🍰 支持移动端浏览。
- 🍰 支持搜索查询。
- 🍰 支持自定义引擎搜索。
- 🍰 多款主题切换。
- 🍰 支持暗黑模式。
- 🍰 支持后台管理, 无需部署。
- 🍰 支持从Chrome书签导入
- 🍰 多种Loading加载动画




## 部署
像数 `321` 一样简单。

#### 方式一(gh-pages免费)
1、Fork 当前项目。

2、[https://github.com/settings/tokens](https://github.com/settings/tokens) 申请 token, 勾选相应的权限, 如果不懂就全部选中，复制并保存Token。

3、https://github.com/用户名/nav/settings/secrets/actions/new  添加申请的token， name填写 `TOKEN` 大写。

4、打开 https://github.com/用户名/nav/actions 点击 `绿色按钮`

5、务必修改项目配置文件 [nav.config.ts](nav.config.ts)

6、5分钟后打开 https://用户名.github.io/nav 就能看到一个非常强大的导航网站了。

### 推荐方式二(Vercel免费)
和方式一的步骤一样，除了第4步不用。

具体使用跟着步骤走即可 [https://github.com/apps/vercel](https://github.com/apps/vercel)



### 推荐方式三(Netlify免费)
[https://www.netlify.com/](https://www.netlify.com/)



## 后台
将路由地址修改为 `system` 即可进入，如: https://www.nav3.cn/#/light 修改为 https://www.nav3.cn/#/system


## 书签导入
支持从 Chrome 书签导入（WebKit内核应该都是支持的~），会自动检测满足三级分类的导航，其他一律设为未分类：

![](https://raw.githubusercontent.com/xjh22222228/public/gh-pages/nav/import.png)

浏览器打开 [chrome://bookmarks/](chrome://bookmarks/) 导出书签得到 html 文件, 接着从导航网站后台导入即可。







## 更新日志
[CHANGELOG](https://github.com/xjh22222228/nav/releases)






## 开发构建
``` bash
# 下载
git clone --depth=1 https://github.com/xjh22222228/nav.git

cd nav

# 安装依赖
yarn

# 启动
yarn start

# 打包
yarn build
```



## 贡献
Thank you for your [contribution](https://github.com/xjh22222228/nav/issues), men.

<a href="https://github.com/YutHelloWorld">
  <img src="https://avatars1.githubusercontent.com/u/20860159?s=460&v=4" width="30px" height="30px" />
</a>
<a href="https://github.com/JJJTHuang">
  <img src="https://avatars3.githubusercontent.com/u/22817432?s=460&v=4" width="30px" height="30px" />
</a>
<a href="https://github.com/Fechin">
  <img src="https://avatars1.githubusercontent.com/u/2541482?s=460&v=4" width="30px" height="30px" />
</a>
<a href="https://github.com/setdiaoyong">
  <img src="https://avatars1.githubusercontent.com/u/62551864?s=460&v=4" width="30px" height="30px" />
</a>








## 协议
[MIT](./LICENSE)
