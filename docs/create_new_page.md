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
1. `base`の部分が`base: master`になっていることを確認(なってなかったらクリックしてmasterを選択)します  
  緑の`Create pull request`をクリックしてリクエスト完了です  
![Screenshot from 2020-06-04 21-46-13](https://user-images.githubusercontent.com/15693656/83758369-f0a2ac80-a6ac-11ea-9e35-4196ddccf0b6.png)
