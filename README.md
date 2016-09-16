# WordPressのテーマを公式ディレクトリに登録するためのヒント

## ガイドライン  
[Guidelines](https://make.wordpress.org/themes/handbook/review/)  

必須機能 [Required](https://make.wordpress.org/themes/handbook/review/required/)  
必須のテンプレートタグやCSSクラスがあります  

コーディング規約
[WordPress Coding Standards](https://make.wordpress.org/core/handbook/best-practices/coding-standards/)  
* [The W3C Markup Validation Service](https://validator.w3.org/)  
* [W3C CSS 検証サービス](http://jigsaw.w3.org/css-validator/)  

テーマタグ [Theme Tags](https://make.wordpress.org/themes/handbook/review/required/theme-tags/)  

## 国際化　
[WordPress の翻訳](https://wpdocs.osdn.jp/WordPress_%E3%81%AE%E7%BF%BB%E8%A8%B3)  

翻訳ツール [Poedit](https://poedit.net/)  

## テーマユニットテスト  
[Theme Unit Test](https://codex.wordpress.org/Theme_Unit_Test)  
[日本語版テストデータ](https://raw.githubusercontent.com/jawordpressorg/theme-test-data-ja/master/wordpress-theme-test-date-ja.xml)  

テーマの表示を確認するためのテストデータ  
どちらかをダウンロードし、テーマを開発中のサイトにインポートします  
このなかにある投稿やコメント、画像、動画などが正常に表示されるか確認します  

## Theme Check  
[Theme check plugin](https://ja.wordpress.org/plugins/theme-check/)  

最新の WordPress 標準および慣例のすべてに対してテーマをテストしてくれるプラグイン  
このチェックをすべてクリアしてから、テーマを審査に出します  
テーマチェックは、WordPressをデバッグモードにして確認します  

** デバッグモード**  
wp-config.php のなかで  
```
define('WP_DEBUG', true);  
```
と書き換えます。  
WP_DEBUGの項目がない場合は、「 編集が必要なのはここまでです ! 」の直前に追加します。  

## ウィジェット
* [Monster Widget](https://ja.wordpress.org/plugins/monster-widget/) 
さまざまなウィジェットを表示するプラグインで表示を確認する  

## その他
* 2バージョン前までのWordPressに対応する  
* 英語環境で確認する  
* テーマカスタマイズでヘッダーテキスト非表示の確認をする
* 最近のブラウザでひととおり確認する

##  審査に出すフォーム  
[Submit Your Theme or Theme Update to the Directory](https://wordpress.org/themes/upload/)  

審査待ちの状況 [New](https://themes.trac.wordpress.org/query?status=new)  

## 国内テーマ開発者
* [WordPress公式テーマ登録のための5ステップ](http://www.slideshare.net/mignonstyle/wordpress5-38514853)  
* [できる！WordPressの公式ディレクトリにテーマを登録](https://wp-d.org/2013/02/12/2590/)  
* [[WordPress]公式ディレクトリにテーマをアップする際の覚え書き](http://wp-kyoto.net/upload-wordpress-official-theme/)  
* [WordPress テーマ Kotetsu が公式ディレクトリに掲載された！](http://2inc.org/blog/2014/09/08/4385/)
* [WordPress公式テーマディレクトリへの申請のためにやったこと](http://welcustom.net/wordpress-theme-review/)  
* [自作WordPressテーマの国際化（翻訳）の方法] (http://welcustom.net/internationalize-wordpress-theme/)  
* [GitHub と Travis CI で WordPress テーマをテスト、ビルド、そして自動化](https://speakerdeck.com/featherplain/github-to-travis-ci-de-wordpress-temawotesuto-birudo-sositezi-dong-hua)  


