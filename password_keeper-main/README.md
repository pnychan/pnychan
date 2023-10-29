# password_keeper
このパスワードキーパーは、クリックするだけで作ったアカウントの情報を保存できます。

## 使い方
まず、自分のメールアドレスをpassword_info.jsonに追加しましょう。
追加方法: 
<pre>
{
  "null@test.com": [
      {
          [...]
      }
  ]<b>,
  "test@example.com": []</b>
}
</pre>

次に、add.pyを開きましょう。
自分のメールアドレスを入力したら、質問に答えるだけ。
password_info.jsonに自分の情報を保存できます。

## ディレクトリ構成
<pre>
├─main
└─password_assemble
    └─__pycache__
</pre>


