# 学習メモ

## Gradle によるビルドに失敗した。

`gradlew build` と試しにやってみたら失敗したのでメモ。

インストール済みの JDK が Java 8 であり、Java プロジェクトが Java 18 だったために発生した。

Adouptium の Java 18 用 JDK を JAVA_HOME への登録含めてインストールしたら解決。

## Gradle

始めて Gradle 使った。npm みたいに使えるっぽい。
Spring Boot アプリケーションを実行するには `gradlew bootRun` とする。

パッケージインストールはどうすんだろうね。
