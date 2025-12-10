<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>小伟同学 - CSDN 个人主页</title>
  <link rel="stylesheet" href="css/style.css" />
</head>
<body>

  <!-- 头部导航 -->
  <header class="header">
    <div class="logo">CSDN</div>
    <nav class="nav-links">
      <a href="#">博客</a>
      <a href="#">下载</a>
      <a href="#">学习</a>
      <a href="#">社区</a>
      <a href="#">GitCode</a>
      <a href="#">InsCode</a>
      <a href="#">会议</a>
      <a href="#">星聚AI</a>
    </nav>
    <div class="search-bar">
      <input type="text" placeholder="搜索..." />
      <button class="btn-search">Q 搜索</button>
      <button class="btn-ai">AI 搜索</button>
    </div>
    <div class="user-area">
      <img src="images/avatar.jpg" alt="头像" class="avatar" />
      <span>会员中心</span>
      <span>消息</span>
      <span>历史</span>
      <span>创作中心</span>
      <button class="btn-create">+ 创作</button>
    </div>
  </header>

  <!-- 主体内容 -->
  <main class="container">
    <!-- 用户信息卡片 -->
    <div class="user-card">
      <img src="images/avatar.jpg" alt="头像" class="user-avatar" />
      <h2>小伟同学</h2>
      <div class="badges">
        <span class="badge">码龄8年</span>
        <span class="badge">原创</span>
      </div>
      <p><strong>7,563</strong> 总访问量 | <strong>7</strong> 原创 | <strong>1</strong> 粉丝 | <strong>17</strong> 关注</p>
      <p><small>IP 属地：河北省 | 加入CSDN时间：2017-12-16</small></p>
      <p>个人简介：不那么彪悍的程序媛</p>
      <a href="#" class="view-profile">查看详细资料</a>
    </div>

    <!-- 左侧栏 -->
    <aside class="sidebar">
      <div class="section">
        <h4>个人成就</h4>
        <ul>
          <li>获得 0 次点赞</li>
          <li>内容获得 0 次评论</li>
          <li>获得 7 次收藏</li>
          <li>博客总排名 988,088 名</li>
        </ul>
      </div>

      <div class="section">
        <h4>原力等级</h4>
        <div class="level-info">
          <span class="level">原力等级</span>
          <span class="score">-1</span>
          <span class="current-month">本月获得 0</span>
        </div>
      </div>

      <div class="section">
        <h4>node.js</h4>
        <h4>网络与通信</h4>
        <h4>https</h4>
      </div>

      <div class="section">
        <h4>创作活动</h4>
        <div class="activity-item">
          <span class="icon">🔥</span>
          <span>AI赋能编程语言挑战赛</span>
        </div>
      </div>
    </aside>

    <!-- 右侧文章列表 -->
    <div class="article-list">
      <div class="tabs">
        <span class="tab active">最近</span>
        <span class="tab">文章7</span>
        <span class="tab">专栏3</span>
        <span class="tab">代码6</span>
        <span class="tab">资源</span>
        <span class="tab">收藏</span>
        <span class="tab">关注订阅/互动</span>
        <span class="tab">更多</span>
      </div>

      <article class="article-item">
        <h3><a href="article.html">Vue.js基本指令v-text，v-html，v-bind，v-on</a></h3>
        <p>先记住这句话：Vue.js的指令都是带有 v-前缀的...</p>
        <div class="meta">
          <span>博文更新于 2019.06.13</span>
          <span>754 阅读</span>
          <span>0 点赞</span>
          <span>0 评论</span>
          <span>2 收藏</span>
        </div>
      </article>

      <article class="article-item">
        <h3><a href="article.html">Vue.js基础 v-on实例——跑马灯效果</a></h3>
        <p>&lt;!DOCTYPE html&gt;&lt;html lang="en"&gt;&lt;head&gt; ...</p>
        <div class="meta">
          <span>博文更新于 2019.06.13</span>
          <span>293 阅读</span>
          <span>0 点赞</span>
          <span>0 评论</span>
          <span>0 收藏</span>
        </div>
      </article>

      <article class="article-item">
        <h3><a href="article.html">Vue.js v-on指令的事件修饰符</a></h3>
        <p>Vue指令 v-on 事件修饰符 stop 阻止冒泡 prevent 阻止默认事件...</p>
        <div class="meta">
          <span>博文更新于 2019.06.13</span>
          <span>994 阅读</span>
          <span>0 点赞</span>
          <span>0 评论</span>
          <span>1 收藏</span>
        </div>
      </article>

      <article class="article-item">
        <h3><a href="article.html">Vue.js基本代码结构和插值表达式</a></h3>
        <p>Vue.js 基本的代码结构&lt;!DOCTYPE html&gt;&lt;html lang="en"&gt;&lt;head&gt; ...</p>
        <div class="meta">
          <span>博文更新于 2019.06.13</span>
          <span>377 阅读</span>
          <span>0 点赞</span>
          <span>0 评论</span>
          <span>0 收藏</span>
        </div>
      </article>
    </div>
  </main>

  <!-- 底部 -->
  <footer class="footer">
    <p>© 1999-2025 北京创新乐知网络技术有限公司</p>
  </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>JavaScript的三种引入方式 - 小伟同学</title>
  <link rel="stylesheet" href="css/style.css" />
</head>
<body>

  <!-- 头部导航 -->
  <header class="header">
    <div class="logo">CSDN</div>
    <nav class="nav-links">
      <a href="#">博客</a>
      <a href="#">下载</a>
      <a href="#">学习</a>
      <a href="#">社区</a>
      <a href="#">GitCode</a>
      <a href="#">InsCode</a>
      <a href="#">会议</a>
      <a href="#">星聚AI</a>
    </nav>
    <div class="search-bar">
      <input type="text" placeholder="搜索..." />
      <button class="btn-search">Q 搜索</button>
      <button class="btn-ai">AI 搜索</button>
    </div>
    <div class="user-area">
      <img src="images/avatar.jpg" alt="头像" class="avatar" />
      <span>会员中心</span>
      <span>消息</span>
      <span>历史</span>
      <span>创作中心</span>
      <button class="btn-create">+ 创作</button>
    </div>
  </header>

  <main class="container article-detail">
    <!-- 左侧边栏 -->
    <aside class="sidebar">
      <div class="section">
        <img src="images/banner.jpg" alt="Banner" class="banner-img" />
      </div>

      <div class="section">
        <h4>热门文章</h4>
        <ul>
          <li><a href="#">JavaScript的三种引入方式</a> <span>4603</span></li>
          <li><a href="#">Vue.js v-on指令的事件修饰符</a> <span>994</span></li>
          <li><a href="#">Vue.js基本指令v-text，v-html，v-bind，v-on</a> <span>756</span></li>
          <li><a href="#">Vue.js基本代码结构和插值表达式</a> <span>377</span></li>
          <li><a href="#">Vue.js简介</a> <span>296</span></li>
        </ul>
      </div>

      <div class="section">
        <h4>分类专栏</h4>
        <ul>
          <li><span class="tag">JavaScript</span> 1篇</li>
          <li><span class="tag">Vue.js</span> 4篇</li>
          <li><span class="tag">笔记本</span> 1篇</li>
        </ul>
      </div>

      <div class="section">
        <h4>上一篇：JavaScript的组成</h4>
        <h4>下一篇：Vue.js简介</h4>
      </div>

      <div class="section">
        <h4>最新文章</h4>
        <ul>
          <li><a href="#">Vue.js基础 v-on实例——跑马灯效果</a></li>
          <li><a href="#">Vue.js v-on指令的事件修饰符</a></li>
          <li><a href="#">Vue.js基本指令v-text，v-html，v-bind，v-on</a></li>
        </ul>
        <div class="year-stats">
          <span>2019年 5篇</span>
          <span>2018年 2篇</span>
        </div>
      </div>
    </aside>

    <!-- 文章主体 -->
    <div class="article-content">
      <h1>JavaScript的三种引入方式</h1>
      <div class="article-meta">
        <span>原创</span>
        <span>于 2018-12-07 14:38:24 发布</span>
        <span>公开</span>
        <span>4.6k 阅读</span>
        <span>0 点赞</span>
        <span>4 收藏</span>
        <span>CC 4.0 BY-SA版权</span>
      </div>

      <div class="article-tags">
        <span class="tag">JavaScript</span>
        <span class="tag">专栏收录该内容</span>
      </div>

      <div class="summary">
        <strong>摘要：</strong>本文详细介绍了JavaScript的三种引入方式：外部引入、内部引入和行内引入，并提供了具体的代码示例，帮助读者理解如何在网页中使用JavaScript。
      </div>

      <div class="content-section">
        <h3>第一种：外部引入</h3>
        <pre><code>&lt;script type="text/javascript" src="路径/文件名.js"&gt;&lt;/script&gt;</code></pre>
      </div>

      <div class="content-section">
        <h3>第二种：内部引入</h3>
        <pre><code>&lt;script type="text/javascript"&gt;
// js代码
&lt;/script&gt;</code></pre>
      </div>

      <div class="content-section">
        <h3>第三种：行内引入</h3>
        <pre><code>&lt;input type="button" value="行内引入方式" onclick="javascript:alert('我是行内引入方式');"&gt;</code></pre>
      </div>

      <div class="author-info">
        <img src="images/avatar.jpg" alt="作者头像" class="author-avatar" />
        <span class="author-name">小伟同学</span>
        <div class="action-buttons">
          <button class="btn-like">👍 0</button>
          <button class="btn-dislike">👎 0</button>
          <button class="btn-star">⭐ 4</button>
          <button class="btn-comment">💬 0</button>
          <button class="btn-share">分享</button>
          <button class="btn-more">...</button>
          <button class="btn-category">专栏目录</button>
        </div>
      </div>

      <div class="footer-info">
        <p>关于我们 | 招贤纳士 | 商务合作 | 寻求报道 | 400-660-0108 | kefu@csdn.net | 在线客服 | 工作时间 8:30-22:00</p>
        <p>公安备案号11010502030143 | 京ICP备19004658号 | 京网文 [2020] 1039-165号 | 经营性网站备案信息 | 北京互联网违法和不良信息举报中心</p>
        <p>家长监护 | 网络110报警服务 | 中国互联网举报中心 | Chrome商店下载 | 账号管理规范 | 版权与免责声明 | 版权申诉 | 出版物许可证 | 置业执照</p>
        <p>©1999-2025北京创新乐知网络技术有限公司</p>
      </div>
    </div>
  </main>

</body>
</html>
/* 通用样式 */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Microsoft YaHei", sans-serif;
  background-color: #f5f8ff;
  color: #333;
  line-height: 1.6;
}

.container {
  display: flex;
  margin: 30px auto;
  max-width: 1200px;
  gap: 20px;
}

/* 头部样式 */
.header {
  background: white;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  padding: 10px 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: sticky;
  top: 0;
  z-index: 100;
}

.logo {
  font-size: 20px;
  font-weight: bold;
  color: #e83e8c;
}

.nav-links a {
  margin-right: 20px;
  text-decoration: none;
  color: #555;
}

.search-bar {
  display: flex;
  gap: 10px;
}

.search-bar input {
  padding: 8px 12px;
  border: 1px solid #ccc;
  border-radius: 20px;
  width: 200px;
}

.btn-search, .btn-ai {
  padding: 8px 16px;
  border: none;
  border-radius: 20px;
  cursor: pointer;
  font-size: 14px;
}

.btn-search {
  background: #e83e8c;
  color: white;
}

.btn-ai {
  background: #007bff;
  color: white;
}

.user-area {
  display: flex;
  gap: 15px;
  align-items: center;
}

.avatar {
  width: 30px;
  height: 30px;
  border-radius: 50%;
}

.user-area span {
  font-size: 14px;
  cursor: pointer;
}

.btn-create {
  background: #e83e8c;
  color: white;
  border: none;
  padding: 8px 16px;
  border-radius: 20px;
  cursor: pointer;
}

/* 用户卡片 */
.user-card {
  background: white;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  margin-bottom: 20px;
  text-align: center;
}

.user-avatar {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  margin-bottom: 10px;
}

.badges {
  display: flex;
  gap: 8px;
  margin: 10px 0;
}

.badge {
  background: #e83e8c;
  color: white;
  padding: 3px 8px;
  border-radius: 4px;
  font-size: 12px;
}

.view-profile {
  color: #e83e8c;
  text-decoration: none;
  font-size: 14px;
  margin-top: 10px;
  display: inline-block;
}

/* 侧边栏 */
.sidebar {
  flex: 1;
  background: white;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.section {
  margin-bottom: 20px;
}

.section h4 {
  margin-bottom: 10px;
  font-size: 16px;
  color: #333;
}

.level-info {
  display: flex;
  justify-content: space-between;
  margin-top: 10px;
  font-size: 14px;
}

.level-info .score {
  font-weight: bold;
}

/* 文章列表 */
.article-list {
  flex: 2;
  background: white;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.tabs {
  display: flex;
  gap: 10px;
  margin-bottom: 20px;
}

.tab {
  padding: 8px 12px;
  border-bottom: 2px solid transparent;
  cursor: pointer;
  font-size: 14px;
}

.tab.active {
  border-bottom: 2px solid #e83e8c;
  color: #e83e8c;
}

.article-item {
  border-bottom: 1px solid #eee;
  padding: 15px 0;
}

.article-item h3 {
  margin-bottom: 8px;
  font-size: 18px;
}

.article-item p {
  color: #666;
  margin-bottom: 10px;
}

.meta {
  font-size: 12px;
  color: #999;
}

/* 文章详情页布局 */
.article-detail {
  display: flex;
  gap: 20px;
}

.article-content {
  flex: 2;
  background: white;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.article-content h1 {
  font-size: 24px;
  margin-bottom: 15px;
}

.article-meta {
  font-size: 12px;
  color: #999;
  margin-bottom: 15px;
}

.article-tags {
  margin-bottom: 20px;
}

.tag {
  background: #e83e8c;
  color: white;
  padding: 3px 8px;
  border-radius: 4px;
  font-size: 12px;
  margin-right: 8px;
}

.summary {
  background: #f0f5ff;
  padding: 15px;
  border-left: 4px solid #e83e8c;
  margin-bottom: 20px;
  font-size: 14px;
}

.content-section {
  margin-bottom: 20px;
}

.content-section pre {
  background: #1e1e1e;
  color: #f8f8f2;
  padding: 15px;
  border-radius: 5px;
  overflow-x: auto;
  margin-top: 10px;
}

.content-section code {
  font-family: Consolas, monospace;
}

.author-info {
  display: flex;
  align-items: center;
  margin-top: 30px;
  padding-top: 20px;
  border-top: 1px solid #eee;
}

.author-avatar {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  margin-right: 10px;
}

.author-name {
  font-weight: bold;
}

.action-buttons {
  display: flex;
  gap: 10px;
  margin-left: auto;
}

.action-buttons button {
  background: none;
  border: none;
  font-size: 14px;
  cursor: pointer;
}

.footer-info {
  margin-top: 30px;
  font-size: 12px;
  color: #999;
  text-align: center;
}

/* 响应式调整 */
@media (max-width: 1000px) {
  .container {
    flex-direction: column;
  }

  .sidebar {
    width: 100%;
  }
}
