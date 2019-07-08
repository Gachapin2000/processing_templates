# processing_templates

TODO: ここに自分の作成したprocessing codeの簡単な内容を紹介してください．
ブロック崩し（崩すと背景が見えてくる）
## Installation

TODO: この項目はclone, pushが終了したら消してください．

githubでdaddygongon/processing_templatesをforkしてください．
その後，
```
> mkdir /home/user_name
> ssh-keygen
> ssh-copy-id user_name@host_url
> cd e:
> git clone git@github.com:USER_NAME/processing_templates.git
```
でcloneしてください．

そこへprocessing codeをcopyした後，
```
> git add -A
> git commit -m 'first commit'
> git push origin master
```
してください．
: git remote -v
で出てくるアドレスをLUNAに提出してください．
このファイル(README.md)の修正も忘れずに．

## Usage

TODO: ここに使い方を書いてください．
ブロック崩しゲーム
ブロックを崩すと、背景の画像が出てくるように！

## Code review
コードは
TODO: ここにcodeの概要と，どのような意図で作成したかを書いてください．
どこの誰のコードを基にして書いたかの引用を忘れずに．
私はブロック崩しゲームを作りたかったが、ただのブロック崩しでは面白くないので、ブロックを崩すと絵柄が出てくるようなゲームを作りたいと思った。そこで私は、絵柄をカオスCGと呼ばれる、綺麗な模様を挿入した。そのコードはhttps://ayumu-nagamatsu.com/archives/431/　
から私は引っ張ってきた。そして、私はこのプログラムを画像に落とし込み、ブロック崩しゲームの背景として利用した。ブロック崩しを作るこードはこの　　サイトから引っ張ってきた。今回の作品で頑張ったところは、絵柄を背景に落としこむ作業である。

sampleをそれぞれのdirectoryに置いています．

今見ている，README.mdはmark downで書いています．

robotx_class/REAME.orgはorg-modeで書いています．コードも綺麗にカラー表示されているでしょう．

もちろんmark downでもcodeを綺麗に表示できます．
書き方は，googleで調べてください．

``` java
rect(0, 0, 10, 10);
```
なんかです．

## License

ここではサンプルとしてMITライセンスの表示をしています．Creative commonsとかLGPLでもOKです．
[Githubのライセンシングを解説した記事](https://www.catch.jp/oss-license/2013/09/10/github/)は
とても参考になります(だいぶその時...2013か...からは改訂されてるけど)．

The processing application is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Test project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/[USERNAME]/processing_templates/blob/master/CODE_OF_CONDUCT.md).
