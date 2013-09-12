# Git Flow
http://keijinsonyaban.blogspot.jp/2010/10/successful-git-branching-model.html
* いろいろ複雑

#GitHub Flow
https://gist.github.com/Gab-km/3705015
* masterはリリース出来るもの。という考え
* ブランチを作って、Pull Requestでマージする

# メモメモ

* remoteとlocalとorigin

* fetch と pullの違い
   * http://qiita.com/y42sora/items/e082d64f3f8b424e9b7d
    ただし、mergeしたくない時にやってしまうと大変なことになる。
    そんな時は、戻したいコミットのIDを調べて、git reset --hard IDで元に戻せる。

* mergeとrebaseの違い
   rebaseは、ベースの再構築　ハッシュが変わるよー

* Pull Requestの方法

* Web Stormで、git push先を変える
　git push ダイアログの「Push current branch to alternative branch」をチェックして、名前入れて
　"更新"を押すと先が変わる
