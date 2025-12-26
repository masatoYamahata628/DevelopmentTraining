#### Webシステム⇒Webブラウザ上で動くアプリケーションの総称
* HTML,CSS,Java
  * Javaなどのプログラムが、DBとの橋渡しとなり、DBにデータを追加したり読み出し動的なページを作る

#### 動的なWebページ
  * ブラウザがURLを通じリクエスト
  * JavaなどのプログラムがDBと連携しHTMLのデータを生成
  * レスポンスとしてHTMLデータを送る

#### JavaによるWebシステム
  * Servlet/JSPというサーバー側(サーブレットコンテナ上)で動作するJavaの技術で実現
  * Servletはリクエストを受け、計算やDBとの連携をおこなう
  * JSPは画面表示のデータを生成する
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

