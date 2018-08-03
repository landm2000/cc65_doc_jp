　Since I wrote Japanese with UTF-8 encoding code, when you build the documentation got garbled characters, 
please set the following "environment variable" and execute　the "make" command.

　日本語の対訳をUTF-8エンコーディングコードで書いたので、ビルドしたドキュメントが文字文字化けしたときは
次の環境変数を設定してからmakeコマンドを実行してしてください。

$  export SP_CHARSET_FIXED=yes SP_ENCODING=xml  ↩︎

$  make  ↩︎
