#### Webシステム⇒Webブラウザ上で動くアプリケーションの総称
* HTML,CSS,Java
  * Javaなどのプログラムが、DBとの橋渡しとなり、DBにデータを追加したり読み出し動的なページを作る

#### 静的なWebページ
* ブラウザ⇔Webサーバー
* あらかじめ用意されたHTMLをレスポンスとして返す

#### 動的なWebページ
  * ブラウザ⇔Webサーバー⇔アプリケーションサーバー⇔データベースサーバー
  * ブラウザがURLを通じリクエスト
  * JavaなどのプログラムがDBと連携しHTMLのデータを生成
  * レスポンスとしてHTMLデータを送る

#### JavaによるWebシステム
  * Servlet/JSPというサーバー側(サーブレットコンテナ上)で動作するJavaの技術で実現
  * Servletはリクエストを受け、計算やDBとの連携をおこなう
  * JSPは画面表示のデータを生成する
  * ServletやJSPを動作させるにはServletコンテナ(アプリケーションサーバー)が必要
  * サーブレットコンテナ⇒アプリケーションサーバー⇒Apache Tomcat 

#### フレームワーク
* Webシステム開発で必要な共通の機能や仕組みを提供
  * MVCモデル
  * バリデーション
  * データベースアクセス

* Spring Boot
  * Apache Tomcat
    * Servlet
    * HTML
  * Controller
  * MyBatis
  * Thymeleaf
* DIコンテナ
* AOPコンテナ
* Spring Web
* その他フレームワークとの連携
  * MyBatisなど

