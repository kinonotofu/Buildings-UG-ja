次ページ [1. はじめに Getting Started](./1_GettingStarted.md)  
  
# [Modelica Buildings Library User Guide](http://simulationresearch.lbl.gov/modelica/userGuide/index.html)  
このユーザーガイドでは、フリーかつオープンソースのModelica Buildingsライブラリの使用方法について説明しています。  
具体的には以下の内容を記載しています。  
* はじめに  
* モデル作成やシミュレーション実行の際のベストプラクティスの適用方法  
* モデルの翻訳（解釈）やシミュレーションの際の一般的な問題の解決方法  
* モデル入出力の前処理と後処理の自動化方法  
* 新しいモデルを開発してライブラリに貢献する方法  
* ヘルプ  
  
次の情報は、このドキュメントではなくライブラリ内のそれぞれのModelicaファイル(.mo)のannotationに記載されています。  
* モデルが基づいている物理的な仮定および方程式  
* 類似の機器または物理現象に対して複数のモデルが利用可能な場合、どのモデルを使用するかについてのアドバイス  
  
# 目次  
## [1. はじめに Getting Started](./1_GettingStarted.md)  
### 1.1. ユーザーのための文献  
### 1.2. 開発者のための文献  
### 1.3. ソフトウェア要件  
### 1.4. はじめてのシミュレーションの実行  
### 1.5. 参考文献  
## [2. ベストプラクティス Best Practice](./2_BestPractice.md)  
### 2.1. パッケージの構成  
### 2.2. 大規模システムモデルの構築  
### 2.3. パラメータとメディアパッケージの伝播(Propagating parameters and media packages)  
### 2.4. 熱流体システム  
#### 2.4.1. 過度の初期化問題と一貫性のない方程式Overdetermined initialization problem and inconsistent equations  
#### 2.4.2. 流体ジャンクションのモデリングModeling of fluid junctions  
#### 2.4.3. 流体フローシステムにおけるセンサの使用Use of sensors in fluid flow systems  
#### 2.4.4. 水などの非圧縮性流体の基準圧力Reference pressure for incompressible fluids such as water  
#### 2.4.5. デフォルト値（Nominal Values）  
### 2.5. 反復変数の初期値Start values of iteration variables  
### 2.6. イベントの回避Avoiding events  
### 2.7. コントロールControls  
### 2.8. 遅いシミュレーションをデバッグして修正する方法の例Examples for how to debug and correct slow simulations  
#### 2.8.1. 状態イベントState events  
#### 2.8.2. エラー制御を支配する状態変数State variables that dominate the error control  
### 2.9. 数値ソルバー  
## [3. エラー防止 Work-Arounds](./3_Work-Arounds.md)  
### 3.1. ステップ変更の回避  
### 3.2. 数値ループの回避Breaking algebraic loops  
### 3.3. 直列接続された流れ抵抗の非線形方程式の低減Reducing nonlinear equations of serially connected flow resistances  
### 3.4. 規定された質量流量  
### 3.5. 過度に指定された初期化問題の回避  
## [4. 前処理と後処理 Pre- and Post-Processing](./4_Pre-AndPost-Processing.md)  
## [5. 開発 Development](./5_Development.md)  
### 5.1. 貢献(Contributing)  
### 5.2. 新しいクラスの追加  
#### 5.2.1. 熱流体装置（Thermofluid flow device）  
#### 5.2.2. 圧力降下  
## [6. ヘルプ Help](./6_Help.md)  
## [7. 用語集 Glossary](./7_Glossary.md)  
## [8. 謝辞 Acknowledgments](./8_Acknowledgments.md)  
## [9. 免責事項 Disclaimers](./9_Disclaimers.md)  
## [10. 著作権とライセンス Copyright and License]  (./10_Copyright_and_License.md)  