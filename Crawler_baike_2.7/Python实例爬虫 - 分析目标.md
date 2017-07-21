### Python实例爬虫 - 分析目标  （Python2.7版）

******

- 目标：百度百科Python词条相关词条网页 - 标题和简介
- 入口页：https://baike.baidu.com/item/Python/407313?fr=aladdin
- URL格式：
  - 词条页面URL ： /view/VBScript
- 数据格式：
  - 标题：
      -  <dd class="lemmaWgt-lemmaTitle-title"><h1>***</h1></dd>
  - 简介：
      - <div class= "lemma-summary" label-module="lemmaSummary">***</div>
- 页面编码：UTF-8