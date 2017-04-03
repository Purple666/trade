
FXの過去ローソク値（MySQL格納）を使用した、機械学習（ランダムフォレスト）結果のシリアライズ

※マシン環境

  VPS、Ubuntu16.10,mem2G

※使用ツール

  Anaconda・・・機械学習ライブラリー及びPython3,numpy,pandas

       https://www.continuum.io/downloads

  TA-LIB・・・・ローソク足--->MA.Rsi等の指標算出

       http://mrjbq7.github.io/ta-lib/install.html

   Python-MySQL・・・MySQL操作

       http://www.python-izm.com/contents/external/mysql.shtml

◎このサンプルソースは以下について掲載しております。

（参照・・・/Ind/main2.py)

１．PythonでMySQLに格納されているFXのローソク足取得

２．ローソク足を元にTA-LIB及び一目均衡表を使用して指標算出

３．指標値を元にxx期間のパターン（位置関係）算出

４．指標パターンの正則化及び未来xx期間の値のラベル付け

５．ランダムフォレストによる機械学習

６．機械学習結果のシリアライズ

