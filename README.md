# kill_china_traitors
NLP查找精日分子

## 由来

中国精日分子的反人类倾向越来越严重，有些高知精日分子潜伏在人群中，只会成为社会的毒瘤。

作为一个中国人，我们的核心价值观是： 富强、民主、文明、和谐,自由、平等、公正、法治,爱国、敬业、诚信、友善。

本人想发起此项目用来搜集相关精日份子的信息，并将信息无偿举报给国家公共安全机关。

## 分类
### 数据获取
使用爬虫 https://github.com/jonbakerfish/TweetScraper
手动查找获取一些关键词，并作为判断依据。
### 数据标注
关键词搜索结果已经较为准确，为了保险起见，进行进一步的标注。
### 分类
构建分类器，做分类。
尝试使用预训练模型做迁移学习。
分类的理想结果是判断某句话是否为支持精日。
希望可以做到准确判断某人是否为精日份子。

## 部署、展示

本程序将自动运行，持续从twitter爬取关联人员、关联关键词数据，并进行标记。

搜集到的人员将存储在图数据库中，并在网页中展示。

将支持API导出。

## 后续扩展

关联人员的其他社交账号信息。包括但不限于：

- Github
- 个人主页
- Telegram
- Facebook
- 微博
- 微信

