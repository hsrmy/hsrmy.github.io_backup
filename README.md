## hsrmy.github.io
https://www.emradc.xyz のソース

基本的には```source```ブランチで作業

  1. ```hugo new post/(ファイル名).md```を実行すると、```content/post/(ファイル名).md```が作成されるので編集
  2. ```hugo server```を実行して、見た目などを確認
  3. ```hugo```を実行して、本番用ファイルの作成
  4. sourceブランチにcommit
  5. **publicフォルダのみ**をmasterブランチにpush (```git subtree push --prefix public/ origin master```)
  6. 生成元のファイルをsourceブランチにpush (```git push origin source```)
  7. [ここ](https://github.com/hsrmy/hsrmy.github.io/deployments)で最新のコミットがActiveになっていることを確認(なっていない場合はgithubからメールが来るはず...)
