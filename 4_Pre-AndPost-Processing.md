前ページ [3. エラー防止 Work-Arounds](./3_Work-Arounds.md)　｜　次ページ [5. 開発 Development](./5_Development.md)
  
# [4. 前処理と後処理 Pre- and Post-Processing](http://simulationresearch.lbl.gov/modelica/userGuide/prePostProcessing.html)  
Modelica言語の仕様ではモデルをシミュレートするためのスクリプト言語は指定されておらず、計算結果ファイルのファイル形式も標準化されていません。モデルのシミュレーションと計算結果の後処理を自動化するスクリプトの提供を目的としてLBNLはPythonのライブラリである[BuildingsPy](http://simulationresearch.lbl.gov/modelica/buildingspy/)を作成しました。このライブラリは以下の目的に使用できます。  
* Dymolaを使用したModelicaシミュレーションの実行  
* DymolaまたはOpenModelicaによって生成された出力ファイル(*.mat)の処理  
* ライブラリ開発の際の単体テストの実行  
  
このライブラリの使用方法については、[http://simulationresearch.lbl.gov/modelica/buildingspy/](http://simulationresearch.lbl.gov/modelica/buildingspy/)の個別の文書を参照してください。  
さらに、Dymolaは、Dymolaで生成した出力ファイル(*.mat)を処理するMATLABスクリプトも提供しています。このスクリプトの使用方法については、Dymolaのドキュメントを参照してください。  
Dymolaによって計算されるコスト関数を最適化するために、最適化プログラム[GenOpt](http://simulationresearch.lbl.gov/GO/)を使用することができます。最適制御問題のコスト関数の計算にDymolaを使用した例については、GenOptのディレクトリexample/dymolaを参照してください。  
  
前ページ [3. エラー防止 Work-Arounds](./3_Work-Arounds.md)　｜　次ページ [5. 開発 Development](./5_Development.md)