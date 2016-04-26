#$#cn
<article class="markdown-body entry-content" itemprop="text"><h1><a id="user-content-flashlight" class="anchor" href="#flashlight" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Flashlight" data-dst="手电筒">手电筒</trans></h1>

<p><trans data-src="A pluggable integration with ElasticSearch to provide advanced content searches in Firebase." data-dst="一个可插拔的集成在Firebase提供先进Elasticsearch的内容搜索。"><trans data-src="一个可插拔的集成在Firebase提供先进Elasticsearch的内容搜索。" data-dst="一个可插拔的集成在Firebase提供先进Elasticsearch的内容搜索。">一个可插拔的集成在Firebase提供先进Elasticsearch的内容搜索。</trans></trans></p>

<p><trans data-src="This script can:" data-dst="这个脚本可以：">这个脚本可以：</trans></p>

<ul>
<li><trans data-src="monitor multiple Firebase paths and index data in real time" data-dst="实时监控多个火力点的路径和索引数据">实时监控多个火力点的路径和索引数据</trans></li>
<li><trans data-src="communicates with client completely via Firebase (client pushes search terms to " data-dst="与客户沟通完全通过火力点（客户端将搜索条件">与客户沟通完全通过火力点（客户端将搜索条件</trans><code><trans data-src="search/request" data-dst="search request／">search request／</trans></code><trans data-src=" and reads results from " data-dst="读取结果">读取结果</trans><code><trans data-src="search/result" data-dst="搜索/结果">搜索/结果</trans></code><trans data-src=")" data-dst="）">）</trans></li>
<li><trans data-src="clean up old, outdated requests" data-dst="清理旧的，过时的请求">清理旧的，过时的请求</trans></li>
</ul>

<h1><a id="user-content-getting-started" class="anchor" href="#getting-started" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Getting Started" data-dst="入门指南">入门指南</trans></h1>

<ul>
<li><trans data-src="Install and run " data-dst="安装和运行">安装和运行</trans><a href="http://www.elasticsearch.org/guide/en/elasticsearch/reference/current/setup.html"><trans data-src="ElasticSearch" data-dst="Elasticsearch">Elasticsearch</trans></a><trans data-src=" or add " data-dst="或添加">或添加</trans><a href="https://addons.heroku.com/bonsai#starter"><trans data-src="Bonsai service" data-dst="盆景服务">盆景服务</trans></a><trans data-src=" via Heroku" data-dst="通过Heroku">通过Heroku</trans></li>
<li><code><trans data-src="git clone https://github.com/firebase/flashlight" data-dst="git clone https://github.com/firebase/flashlight"><trans data-src="git clone https://github.com/firebase/flashlight" data-dst="git clone https://github.com/firebase/flashlight">git clone https://github.com/firebase/flashlight</trans></trans></code></li>
<li><code><trans data-src="npm install" data-dst="NPM安装">NPM安装</trans></code></li>
<li><trans data-src="edit config.js (see comments at the top, you must set FB_URL at a minimum)" data-dst="编辑config.js（见顶部，评论必须设置fb_url至少）">编辑config.js（见顶部，评论必须设置fb_url至少）</trans></li>
<li><code><trans data-src="node app.js" data-dst="结app.js">结app.js</trans></code><trans data-src=" (run the app)" data-dst="（运行程序）">（运行程序）</trans></li>
</ul>

<p><trans data-src="Check out the recommended security rules in example/seed/security_rules.json.
See example/README.md to seed and run an example client app." data-dst="查看推荐的安全规则的例子/种子/ security_rules。JSON。
见例子/ readme.md种子和运行一个实例的客户端。">查看推荐的安全规则的例子/种子/ security_rules。JSON。
见例子/ readme.md种子和运行一个实例的客户端。</trans></p>

<p><trans data-src="If you experience errors like " data-dst="如果你经历这样的错误">如果你经历这样的错误</trans><code><trans data-src="{" error":"indexmissingexception[[firebase]="" missing]","status":404}"="" data-dst="{“错误”：“indexmissingexception [发] [失踪]”，“状态”：404 }">{“错误”：“indexmissingexception [发] [失踪]”，“状态”：404 }</trans></code><trans data-src=", you may need
to manually create the index referenced in each path:" data-dst="，你可能需要
手动创建在每个路径的参考指标：">，你可能需要
手动创建在每个路径的参考指标：</trans></p>

<pre><code><trans data-src="curl -X POST http://localhost:9200/firebase
" data-dst="卷曲后X：http：／／本地/ firebase 9200">卷曲后X：http：／／本地/ firebase 9200</trans></code></pre>

<h1><a id="user-content-client-implementations" class="anchor" href="#client-implementations" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Client Implementations" data-dst="客户implementations">客户implementations</trans></h1>

<p><trans data-src="Read " data-dst="阅读">阅读</trans><code><trans data-src="example/index.html" data-dst="example / index.html">example / index.html</trans></code><trans data-src=" and " data-dst="和">和</trans><code><trans data-src="example/example.js" data-dst="example.js / example">example.js / example</trans></code><trans data-src=" for a client implementation. It works like this:" data-dst="一个客户端的实现。它的工作原理是这样的：">一个客户端的实现。它的工作原理是这样的：</trans></p>

<ul>
<li><trans data-src="Push an object to " data-dst="把一个对象">把一个对象</trans><code><trans data-src="/search/request" data-dst="／／search request">／／search request</trans></code><trans data-src=" which has the following keys: " data-dst="它有以下的钥匙：">它有以下的钥匙：</trans><code><trans data-src="index" data-dst="指数">指数</trans></code><trans data-src=", " data-dst="，">，</trans><code><trans data-src="type" data-dst="类型">类型</trans></code><trans data-src=", and " data-dst="，和">，和</trans><code><trans data-src="query" data-dst="查询">查询</trans></code></li>
<li><trans data-src="Listen on " data-dst="听">听</trans><code><trans data-src="/search/response" data-dst="/搜索/响应">/搜索/响应</trans></code><trans data-src=" for the reply from the server" data-dst="从服务器的回复">从服务器的回复</trans></li>
</ul>

<p><trans data-src="The query object can be any valid ElasticSearch DSL structure (see More on Queries)." data-dst="查询对象可以是任何有效的Elasticsearch DSL结构（见更多的查询）。">查询对象可以是任何有效的Elasticsearch DSL结构（见更多的查询）。</trans></p>

<h2><a id="user-content-more-on-queries" class="anchor" href="#more-on-queries" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="More on Queries" data-dst="更多的查询">更多的查询</trans></h2>

<p><trans data-src="The full ElasticSearch API is supported. For example, you can control the number of matches (defaults to 10) and initial offset for paginating search results:" data-dst="全Elasticsearch API支持。例如，您可以控制比赛的数目（默认为10）和对搜索结果的初始偏移：">全Elasticsearch API支持。例如，您可以控制比赛的数目（默认为10）和对搜索结果的初始偏移：</trans></p>

<pre><code><trans data-src="queryObj : { " from"="" :="" 0,="" "size"="" 50="" ,="" "query":="" queryobj="" };="" "="" data-dst="queryobj：{“from”：0、50、“大小”：“查询”：queryobj }">queryobj：{“from”：0、50、“大小”：“查询”：queryobj }</trans></code></pre>

<p><trans data-src="Check out " data-dst="退房">退房</trans><a href="http://okfnlabs.org/blog/2013/07/01/elasticsearch-query-tutorial.html"><trans data-src="this great tutorial" data-dst="这个伟大的教程">这个伟大的教程</trans></a><trans data-src=" on querying ElasticSearch. And be sure to read the " data-dst="在查询Elasticsearch。一定要读">在查询Elasticsearch。一定要读</trans><a href="http://www.elasticsearch.org/guide/en/elasticsearch/reference/current/"><trans data-src="ElasticSearch API Reference" data-dst="Elasticsearch API参考">Elasticsearch API参考</trans></a><trans data-src="." data-dst="。">。</trans></p>

<h1><a id="user-content-deploy-to-heroku" class="anchor" href="#deploy-to-heroku" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Deploy to Heroku" data-dst="部署到Heroku">部署到Heroku</trans></h1>

<ul>
<li><code><trans data-src="cd flashlight" data-dst="CD的手电筒">CD的手电筒</trans></code></li>
<li><code><trans data-src="heroku login" data-dst="Heroku登录">Heroku登录</trans></code></li>
<li><code><trans data-src="heroku create" data-dst="Heroku的创建">Heroku的创建</trans></code><trans data-src=" (add heroku to project)" data-dst="（添加Heroku项目）">（添加Heroku项目）</trans></li>
<li><code><trans data-src="heroku addons:add bonsai" data-dst="Heroku插件：添加盆景">Heroku插件：添加盆景</trans></code><trans data-src=" (install bonsai)" data-dst="（安装盆景）">（安装盆景）</trans></li>
<li><code><trans data-src="heroku config" data-dst="Heroku的配置">Heroku的配置</trans></code><trans data-src="  (check bonsai instance info and copy your new BONSAI_URL - you will need it later)" data-dst="（检查盆景实例信息和复制你的新bonsai_url -你会需要它）">（检查盆景实例信息和复制你的新bonsai_url -你会需要它）</trans></li>
<li><code>heroku config:set FB_NAME=&lt;instance&gt; FB_TOKEN="&lt;token&gt;"</code><trans data-src=" (declare environment variables)" data-dst="（申报环境变量）">（申报环境变量）</trans></li>
<li><code><trans data-src="git add config.js" data-dst="git add config.js"><trans data-src="git add config.js" data-dst="git add config.js">git add config.js</trans></trans></code><trans data-src=" (update)" data-dst="（更新）">（更新）</trans></li>
<li><code><trans data-src="git commit -m " configure="" bonsai""="" data-dst="git commit -m“配置盆景”">git commit -m“配置盆景”</trans></code></li>
<li><code><trans data-src="git push heroku master" data-dst="git push Heroku的主人">git push Heroku的主人</trans></code><trans data-src=" (deploy to heroku)" data-dst="（部署到Heroku）">（部署到Heroku）</trans></li>
<li><code>heroku ps:scale worker=1</code><trans data-src=" (start dyno worker)" data-dst="（开始赛道工人）">（开始赛道工人）</trans></li>
</ul>

<h3><a id="user-content-setup-initial-index-with-bonsai" class="anchor" href="#setup-initial-index-with-bonsai" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Setup Initial Index with Bonsai" data-dst="设置初始指标与盆景">设置初始指标与盆景</trans></h3>

<p><trans data-src="After you've deployed to Heroku, you need to create your initial index name to prevent IndexMissingException error from Bonsai. Create an index called " firebase"="" via="" curl="" using="" the="" bonsai_url="" that="" you="" copied="" during="" heroku="" deployment."="" data-dst="当你部署到Heroku，你需要创建初始指标名称防止indexmissingexception误差从盆景。创建一个索引称为“火力点”通过cURL使用bonsai_url你复制在Heroku的部署。">当你部署到Heroku，你需要创建初始指标名称防止indexmissingexception误差从盆景。创建一个索引称为“火力点”通过cURL使用bonsai_url你复制在Heroku的部署。</trans></p>

<ul>
<li><code><trans data-src="curl -X POST <BONSAI_URL>/firebase" data-dst="卷发x后< bonsai_url > /火力点">卷发x后&lt; bonsai_url &gt; /火力点</trans></code><trans data-src=" (ex: https://user:" data-dst="（例如：https: / /用户：">（例如：https: / /用户：</trans><a href="mailto:pass@yourbonsai.bonsai.io"><trans data-src="pass@yourbonsai.bonsai.io" data-dst="yourbonsai.bonsai.io通”">yourbonsai.bonsai.io通”</trans></a><trans data-src="/firebase)" data-dst="/发）">/发）</trans></li>
</ul>

<h1><a id="user-content-support" class="anchor" href="#support" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="Support" data-dst="支持">支持</trans></h1>

<p><trans data-src="Submit questions or bugs using the " data-dst="提交问题或错误使用">提交问题或错误使用</trans><a href="https://github.com/firebase/flashlight"><trans data-src="issue tracker" data-dst="问题跟踪器">问题跟踪器</trans></a><trans data-src="." data-dst="。">。</trans></p>

<p><trans data-src="For Firebase-releated questions, try the " data-dst="对火力点相关问题，尝试">对火力点相关问题，尝试</trans><a href="https://groups.google.com/forum/#!forum/firebase-talk"><trans data-src="mailing list" data-dst="通讯名单">通讯名单</trans></a><trans data-src="." data-dst="。">。</trans></p>

<h1><a id="user-content-license" class="anchor" href="#license" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewBox="0 0 16 16" width="16"><path d="M4 9h1v1h-1c-1.5 0-3-1.69-3-3.5s1.55-3.5 3-3.5h4c1.45 0 3 1.69 3 3.5 0 1.41-0.91 2.72-2 3.25v-1.16c0.58-0.45 1-1.27 1-2.09 0-1.28-1.02-2.5-2-2.5H4c-0.98 0-2 1.22-2 2.5s1 2.5 2 2.5z m9-3h-1v1h1c1 0 2 1.22 2 2.5s-1.02 2.5-2 2.5H9c-0.98 0-2-1.22-2-2.5 0-0.83 0.42-1.64 1-2.09v-1.16c-1.09 0.53-2 1.84-2 3.25 0 1.81 1.55 3.5 3 3.5h4c1.45 0 3-1.69 3-3.5s-1.5-3.5-3-3.5z"></path></svg></a><trans data-src="License" data-dst="许可证">许可证</trans></h1>

<p><a href="http://firebase.mit-license.org/"><trans data-src="MIT LICENSE" data-dst="MIT许可证">MIT许可证</trans></a><trans data-src="
Copyright © 2013 Firebase " data-dst="版权所有©2013年firebase">版权所有©2013年firebase</trans><a href="mailto:opensource@firebase.com"><trans data-src="opensource@firebase.com" data-dst="“firebase.com开源">“firebase.com开源</trans></a></p>
</article>
###en
Flashlight
==========

A pluggable integration with ElasticSearch to provide advanced content searches in Firebase.

This script can:
 - monitor multiple Firebase paths and index data in real time
 - communicates with client completely via Firebase (client pushes search terms to `search/request` and reads results from `search/result`)
 - clean up old, outdated requests

Getting Started
===============

 - Install and run [ElasticSearch](http://www.elasticsearch.org/guide/en/elasticsearch/reference/current/setup.html) or add [Bonsai service](https://addons.heroku.com/bonsai#starter) via Heroku
 - `git clone https://github.com/firebase/flashlight`
 - `npm install`
 - edit config.js (see comments at the top, you must set FB_URL at a minimum)
 - `node app.js` (run the app)

Check out the recommended security rules in example/seed/security_rules.json.
See example/README.md to seed and run an example client app.

If you experience errors like `{"error":"IndexMissingException[[firebase] missing]","status":404}`, you may need
to manually create the index referenced in each path:

    curl -X POST http://localhost:9200/firebase

Client Implementations
======================

Read `example/index.html` and `example/example.js` for a client implementation. It works like this:

 - Push an object to `/search/request` which has the following keys: `index`, `type`, and `query`
 - Listen on `/search/response` for the reply from the server

The query object can be any valid ElasticSearch DSL structure (see More on Queries).

More on Queries
---------------

The full ElasticSearch API is supported. For example, you can control the number of matches (defaults to 10) and initial offset for paginating search results:

```
queryObj : { "from" : 0, "size" : 50 , "query": queryObj }; 
```

Check out [this great tutorial](http://okfnlabs.org/blog/2013/07/01/elasticsearch-query-tutorial.html) on querying ElasticSearch. And be sure to read the [ElasticSearch API Reference](http://www.elasticsearch.org/guide/en/elasticsearch/reference/current/).

Deploy to Heroku
================

 - `cd flashlight`
 - `heroku login`
 - `heroku create` (add heroku to project)
 - `heroku addons:add bonsai` (install bonsai)
 - `heroku config`  (check bonsai instance info and copy your new BONSAI_URL - you will need it later)
 - `heroku config:set FB_NAME=<instance> FB_TOKEN="<token>"` (declare environment variables)
 - `git add config.js` (update)
 - `git commit -m "configure bonsai"`
 - `git push heroku master` (deploy to heroku)
 - `heroku ps:scale worker=1` (start dyno worker)

### Setup Initial Index with Bonsai

After you've deployed to Heroku, you need to create your initial index name to prevent IndexMissingException error from Bonsai. Create an index called "firebase" via curl using the BONSAI_URL that you copied during Heroku deployment.

 - `curl -X POST <BONSAI_URL>/firebase` (ex: https://user:pass@yourbonsai.bonsai.io/firebase)

Support
=======

Submit questions or bugs using the [issue tracker](https://github.com/firebase/flashlight).

For Firebase-releated questions, try the [mailing list](https://groups.google.com/forum/#!forum/firebase-talk).

License
=======

[MIT LICENSE](http://firebase.mit-license.org/)
Copyright © 2013 Firebase <opensource@firebase.com>
