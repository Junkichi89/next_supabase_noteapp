## middlewareとは？

apiのエンドポイントや特定のページにアクセスがあった際に、
そのApiやページの処理を行う前にmiddlewareで前処理を行うことができる

- requestのheaderを確認して適切なtokenがなければ、別のページへ遷移させる
- reqestがあったブラウザを識別して、表示　するページを切り替える
- 
