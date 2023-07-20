# 基本

サーバ起動  
hexo server
hexo server --draft  
hexo generate
hexo deploy

ドラフト作成  
docker exec karinto-manga hexo new draft {draft名}  
docker exec karinto-manga hexo publish {draft名}    

諸々きれいにする  
hexo clean

まとめてやる
docker exec karinto-manga hexo clean && hexo generate && hexo deploy

Docker
docker exec karinto-manga


# タグスクリプト
![](initializr.png) //　トップページでしくじる

{% codeblock docker-compose.yml lang:yaml %}
{% endcodeblock %}

{% asset_img about_style.png [著者プロフィール] %}
{% asset_img about_style.png %}

[ブログ内のリンク](/tech-memo/2020/04/2020-0415-hexoCheatsheet/)

こんにちは。[karintomania](https://twitter.com/karintozuki)です。
[リンク文面](https://orchid.run/wiki/learn )

https://karintomania.github.io/tech-memo/

tags: [Java, PHP, Java script]

テーブル
|
--- | ---
|
|

アフィリリンク用
{% raw %}
{% endraw %}

## 画像
feature は10 x 5くらいでOK

## Deployエラー
```
rm -rf .deploy_git && \
git config --global user.name karintomania && git config --global user.email 19652340+karintomania@users.noreply.github.com && \
hexo deploy
```
