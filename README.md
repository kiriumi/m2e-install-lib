# 概要
EclipseのMavenプラグイン（m2e）で、ローカルリポジトリにライブラリをインストールする、サンプルプロジェクト

# 使い方
POMに以下情報を設定し、ゴールをinstall:install-fileで実行
``` xml
<file>【Jarの絶対パス】</file>
<groupId>【GroupId】</groupId>
<artifactId>【ArtifactId】</artifactId>
<version>【バージョン】</version>
```
