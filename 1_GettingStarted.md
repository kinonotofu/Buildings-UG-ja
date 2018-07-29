前ページ [0. 目次](./0_Top.md)　｜　次ページ [2. ベストプラクティス](./2_BestPractice.md)  
***  
  
# [1. はじめに](http://simulationresearch.lbl.gov/modelica/userGuide/gettingStarted.html)  
## 1.1. ユーザーのための文献  
新規ユーザーがはじめるにあたって役に立つ書籍を以下に示します。  
* Michael Tillerのインタラクティブな例を含む[オンラインブック](http://book.xogeny.com/)  
* Michael Tiller[Til2001]とPeter Fritzson([Fri2011]、[Fri2004])による本(1.5. 参考文献)  
* [https://www.modelica.org/publications](https://www.modelica.org/publications)に掲載されているチュートリアル  
  
[the Modelica Language Tutorial](https://www.modelica.org/documents/ModelicaTutorial14.pdf)は古いバージョン（Modelica 1.4）ですが、Modelica言語の概念を理解するためのものとしては現在でも有益で妥当な資料と言えます。  
  
Buildingsライブラリについての記述がある、または使用している論文は[http://simulationresearch.lbl.gov/modelica/publications.html](http://simulationresearch.lbl.gov/modelica/publications.html)にまとめています。また、ダウンロードページの[ドキュメント](http://simulationresearch.lbl.gov/modelica/releases/v5.1.0/help/Buildings.html)には、個々のパッケージを説明するユーザーガイドが含まれています。  
  
[The IEA EBC Annex 60 final report](http://www.iea-annex60.org/final-report.html) ではFMI規格に基づく連成シミュレーションのためのMoodelicaモデルやアプローチやツールの開発、IFCに基づくBIM技術、ワークフロー自動化のためのツールについてまとめられています。また、建物やコミュニティのエネルギーシステムを設計、運用する際にこれらの技術を適用した多くの事例も含まれています。  
  
ModelicaのインタラクティブなWebベースのツアーは[http://modelica.university/res/lesson/training.json](http://modelica.university/res/lesson/training.json)で利用できます。  
  
初心者のための音声チュートリアルは[http://spoken-tutorial.org/tutorial-search/?search_foss=OpenModelica&search_language=English](http://spoken-tutorial.org/tutorial-search/?search_foss=OpenModelica&search_language=English)で利用できます。  
  
## 1.2. 開発者のための文献  
新しく熱流体モデルを開発する際にはストリームコネクタの概念を理解することが重要です。ストリームコネクタについては[https://www.modelica.org/documents](https://www.modelica.org/documents)の[Modelicaの言語定義](https://www.modelica.org/documents/ModelicaSpec34.pdf)やFrankeらによる[論文[Fra2009a]](https://www.modelica.org/events/modelica2009/Proceedings/memorystick/pages/papers/0078/0078.pdf)に説明があります。Buildingsライブラリは、Modelica.Fluidライブラリと類似したモデリング規則や同じ基底クラスを使用しているため、Modelica.Fluidの熱流体モデルの標準化についての[論文[Fra2009b]](https://www.modelica.org/events/modelica2009/Proceedings/memorystick/pages/papers/0077/0077.pdf)を読むことをすすめます。  
Xogenyの[Modelica Web Reference](http://modref.xogeny.com/)は、Modelica言語の簡潔な概要と説明、さらなる情報のリンクを提供しています。  
  
## 1.3. ソフトウェア要件  
[http://simulationresearch.lbl.gov/modelica/download.html](http://simulationresearch.lbl.gov/modelica/download.html)にあるそれぞれのバージョンのBuildingsライブラリのソフトウェア要件を確認してください。 バージョン5.1.0においてはModelica標準ライブラリ3.2.2が必要であり、動作確認はDymola2018FD01とJModelica(revision 11291)において行われています。  
  
## 1.4. はじめてのシミュレーションの実行  
Modelicaをはじめるにあたり、まずはBuildingsライブラリのサンプルモデルを実行します。これらの例を用いてモデルパラメータの値を変更したり、既存のモデルを新しいものに置き換えることによってバリエーションを作成してみましょう。サンプルモデルはExamplesパッケージに、システムモデルを一つずつ構築する詳細なチュートリアルは[Tutorial](http://simulationresearch.lbl.gov/modelica/releases/latest/help/Buildings_Examples_Tutorial.html)パッケージにあります。  
  
注）Buildings.HeatTransfer.*.Examplesにある熱伝達モデルは以下の理由により流体流動モデルよりも理解しやすくなっています。  
* 流体の流れを扱う場合は流れの逆転（質量流量が方向を変える場合）により複雑さが増してしまいます。  
* 流体流動モデルは空気や水蒸気、CO2のような微量物質など複数の種類の物質を扱う必要があるかもしれません。  
* 流体流動モデルは、乾燥空気、湿った空気、水または他の流体のような媒体モデルを定義するパッケージを使用しています。  
  
## 1.5. 参考文献  
|||
|:-:|:--|
|[Fri2004]|Peter Fritzson. Principles of Object-Oriented Modeling and Simulation with Modelica 2.1. John Wiley & Sons,2004.|
|[Fri2011]|Peter Fritzson. Introduction to Modeling and Simulation of Technical and Physical Systems with Modelica.Wiley-IEEE Press, ISBN 978-1-1180-1068-6, 2011.|
|[Fra2009a]|R. Franke, F. Casella, M. Otter, M. Sielemann, H. Elmqvist, S. E. Mattsson, and H. Olsson. [Stream connectors – an extension of modelica for device-oriented modeling of convective transport phenomena.](https://www.modelica.org/events/modelica2009/Proceedings/memorystick/pages/papers/0078/0078.pdf) In F. Casella, editor, Proc. of the 7-th International Modelica Conference, Como, Italy, Sept. 2009.|
|[Fra2009b]|R. Franke, F. Casella, M. Otter, K. Proelss, M. Sielemann, and M. Wetter. [Standardization of thermo-fluid modeling in Modelica.Fluid.](https://www.modelica.org/events/modelica2009/Proceedings/memorystick/pages/papers/0077/0077.pdf) In F. Casella, editor, Proc. of the 7-th International Modelica Conference, Como, Italy, Sept. 2009.|
|[Til2001]|Michael M. Tiller. Introduction to Physical Modeling with Modelica. Kluwer Academic Publisher, 2001.|
  
***  
前ページ [0. 目次](./0_Top.md)　｜　次ページ [2. ベストプラクティス](./2_BestPractice.md)