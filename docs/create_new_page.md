# ページの新規作成方法
## 編集権限のリクエスト
1. GitHubのアカウントを作成し、ログインします  
1. VirtualSpaceProgram organizationのOwnerに先ほど作成したGitHubアカウントのIDを伝え、編集権限を取得します  
    Ownerは下記リンクから確認できます  
    [People · VirtualSpaceProgram](https://github.com/orgs/VirtualSpaceProgram/people)  
    要するにVSP DiscordにてKuwamaiにGitHub IDを伝えればOKです

## ページの新規作成
1. [VirtualSpaceProgram.github.io](https://github.com/VirtualSpaceProgram/VirtualSpaceProgram.github.io)のページを開きます  
1. スクショ中央付近のCreate new fileをクリックします
![Screenshot from 2020-06-04 21-14-51](https://user-images.githubusercontent.com/15693656/83755653-d8c92980-a6a8-11ea-836e-583fb0ae1c9d.png)  
1. Markdownで好きに書きます  
  `_posts`ディレクトリに`yyyy-mm-dd-page_title.md`(`年-月-日-ページタイトル.md`)というファイル名で作成します  
  `/`でディレクトリ(フォルダ)を区切ることができます  
  Previewタブでページのプレビューができます  
  `---`で挟んだ部分でレイアウト、タイトル、タグを設定します  
  よくわからなかったらKuwamaiが後で追記するので気にせず記事の内容を書き進めてください
![Screenshot from 2020-06-04 21-24-49](https://user-images.githubusercontent.com/15693656/83756340-e59a4d00-a6a9-11ea-8be6-84654e9bb69d.png)  
1. ページ下部に何のページを書いたかコメントを書いてください  
  `Create a new branch`にチェックを入れてください  
  緑の`Propose file changes`をクリックして保存します  
  この状態はまだ下書きなので、実際のページには反映されません  
![B4E2892D-E43E-4C31-BC72-570D86BE5120](https://user-images.githubusercontent.com/15693656/83757756-eb912d80-a6ab-11ea-9220-6908693f8597.JPG)  

## 更新のリクエスト
1. Forkしたリポジトリの内容を本家リポジトリに反映してもらうようリクエストします  
  [VirtualSpaceProgram.github.io](https://github.com/VirtualSpaceProgram/VirtualSpaceProgram.github.io)のページを開き、スクショ中央付近の`New pull request`をクリックします  
![Screenshot from 2020-03-31 12-11-17](https://user-images.githubusercontent.com/15693656/77983449-0791ef00-734a-11ea-8a1a-c7a1fcfaec04.png)  
1. これがリクエスト画面です  
  Forkしたリポジトリ内容を反映してほしいので、`compare across forks`をクリックします  
![Screenshot from 2020-03-31 13-00-50](https://user-images.githubusercontent.com/15693656/77985970-d79a1a00-7350-11ea-8476-ebf88abdc077.png)  
1. 矢印の左側が反映先の本家リポジトリなので、右側をクリックして自分がForkしたリポジトリを選択します  
![Screenshot from 2020-03-31 13-01-16](https://user-images.githubusercontent.com/15693656/77986021-fd272380-7350-11ea-9858-904634b17362.png)  
1. それっぽいタイトルとコメントを入力して緑の`Create pull request`ボタンを押せばリクエストの完了です  
![Screenshot from 2020-03-31 13-02-39](https://user-images.githubusercontent.com/15693656/77986022-00baaa80-7351-11ea-8b7f-bf3be0770446.png)  
