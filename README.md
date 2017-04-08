# dtm

このリポジトリはDTMのプロジェクト&ファイル管理用です。

## GitHubで.logicxを管理する時の注意
サンプラーが重いので.gitignoreで.cafを除外しないと100MB制限に引っかかって死にます。  
一度やってしまうと.gitのログファイルが膨れ上がるので、  
問題のファイルを除外してもgit pushできなくなります。  
その場合はgit cloneからやり直しましょう。  
