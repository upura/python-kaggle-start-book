[![readme_en](https://img.shields.io/static/v1?label=README&message=English&color=blue)](README_EN.md)

# サンプルコード・脚注・正誤表

- 『PythonではじめるKaggleスタートブック』のサンプルコードです。
- 書籍内の脚注は[こちら](footnote.md)にまとめています。
- 正誤表は[こちら](errata.md)です。
- ご感想・ご質問は、[issue](https://github.com/upura/python-kaggle-start-book/issues)にてお願いします。よくある質問（FAQ）は、[下記](https://github.com/upura/python-kaggle-start-book#%E3%82%88%E3%81%8F%E3%81%82%E3%82%8B%E8%B3%AA%E5%95%8Ffaq)にまとめています。

## 各ディレクトリの内容

- 「Kaggle (py36)」は、書籍の第1刷に合わせて公開したファイルです。Pythonバージョンは3.6です。ディレクトリ名`ch02`と`ch03`のファイルをアップロードしました。
- 「Kaggle (py310)」は、書籍の第5刷に合わせて公開したファイルです。Pythonバージョンは3.10です。

| ディレクトリ | 内容 | ファイル名 | Kaggle (py36) | Kaggle (py310) |
|:---|:---|:---|:---|:---|
| input | 入力ファイル | - | - | - |
| ch02 | 第2章のサンプルコード | ch02_01.ipynb | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/sishihara/python-kaggle-start-book-ch02-01) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/sishihara/py310-python-kaggle-start-book-ch02-01) |
| | | ch02_02.ipynb |  [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/sishihara/python-kaggle-start-book-ch02-02) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/sishihara/py310-python-kaggle-start-book-ch02-02) |
| | | ch02_03.ipynb |  [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/sishihara/python-kaggle-start-book-ch02-03) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/sishihara/py310-python-kaggle-start-book-ch02-03) |
| | | ch02_04.ipynb |  [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/sishihara/python-kaggle-start-book-ch02-04) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/sishihara/py310-python-kaggle-start-book-ch02-04) |
| | | ch02_05.ipynb |  [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/sishihara/python-kaggle-start-book-ch02-05) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/sishihara/py310-python-kaggle-start-book-ch02-05) |
| | | ch02_06.ipynb |  [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/sishihara/python-kaggle-start-book-ch02-06) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/sishihara/py310-python-kaggle-start-book-ch02-06) |
| | | ch02_07.ipynb |  [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/sishihara/python-kaggle-start-book-ch02-07) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/sishihara/py310-python-kaggle-start-book-ch02-07) |
| | | ch02_08.ipynb |  [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/sishihara/python-kaggle-start-book-ch02-08) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/sishihara/py310-python-kaggle-start-book-ch02-08) |
| ch03 | 第3章のサンプルコード | ch03_01.ipynb | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/sishihara/python-kaggle-start-book-ch03-01) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/sishihara/py310-python-kaggle-start-book-ch03-01) |
| | | ch03_02.ipynb |  [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/sishihara/python-kaggle-start-book-ch03-02) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/sishihara/py310-python-kaggle-start-book-ch03-02) |
| | | ch03_03.ipynb |  [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/sishihara/python-kaggle-start-book-ch03-03) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/sishihara/py310-python-kaggle-start-book-ch03-03) |

### 「Kaggle (py310)」での主な変更点

- 注：乱数やライブラリの仕様変更などの問題で、初版と合わせた公開したファイルと実行結果が一致しない場合があります。
- 第5刷：LightGBMの[仕様変更](https://github.com/microsoft/LightGBM/pull/4908)に伴い`early_stopping_rounds`引数を削除しました。
- 第5刷：ch03_02.ipynbで`dataiter.next()`を`next(dataiter)`に変更しました。
- 第5刷：ch03_03.ipynbで`word2vec.Word2Vec`の引数の`size`を`vector_size`に変更しました。
- 第6刷：ch02_03.ipynbでimportするライブラリ名を`pandas_profiling`から`ydata_profiling`に変更しました。

## よくある質問（FAQ）

過去の全質問・やり取りは[こちら](https://github.com/upura/python-kaggle-start-book/issues?q=is%3Aissue)で公開しています。

### 電子版の販売はありますか？

2020年5月26日から、kindle版やkobo版などリフロー型で配信しています。[オンライン書店](https://bookclub.kodansha.co.jp/buy?item=0000325172)にてご確認ください。

### p.41: Kaggle Notebookの「Commit」が存在しません

Kaggle Notebookのデザインは随時更新されています。2023年5月時点のCommit方法は、[動画](https://youtu.be/u6Bc0jiWu38)で解説しています。

### 他言語版はありますか？

中国語繁体字版の『[Kaggle大師教您用Python玩資料科學，比賽拿獎金](http://books.gotop.com.tw/v_ACD021100)』と、韓国語版の『[파이썬으로 시작하는 캐글: 입문에서 컴피티션까지](https://jpub.tistory.com/1147)』が、2021年4月に出版されました。
