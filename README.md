# springBoot_simplleOutputJSON

### SpringBoot最初の一歩 REST編②

RESTControllerを使ってJSONを出力するシンプルなソースです。

RESTはテキストを出力するシンプルな仕組みですが、

実際の開発では、テキストを出力するだけの実装はあまりしないと思います。


ほとんどの場合は、オブジェクトデータをテキストとして出力することが必要です。

RestControllerで、JSONを出力するには？

オブジェクトデータをreturnするだけです。

RestControllerはreturnする値がオブジェクト型であれば、
自動的にJSON形式に変換して出力してくれる協力な助っ人なのです(^.^)

プログラマーは手作業でJSON形式にしなくて良くて、returnするだけです。

サンプルソースではDataObjectクラスをreturn値にしています。
URLを入力すると、JSON形式で出力されていることが確認できます。
ブラウザでlocalhost:8080/id とURLを入力すれば、DataObjectのidが動的に変更されます。
