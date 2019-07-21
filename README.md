# aaa

ソースコード

　1 im1 = imread('images/yubi1.jpg')

　2 im2 = imread('images/yubi2.jpg')

　3 im3 = imread('images/yubi3.jpg')

　4 im4 = imread('images/yubi4.jpg')


　5 y=[im1.mean(),im2.mean(),im3.mean(),im4.mean()]

　6 x=[1,2,3,4]

　7 plt.plot(x,y,'o')

　8 plt.show()



コード説明

　１～４行：画像を読み込み

　5行：画像を配列に代入

　6行：１～４を配列に代入して画像と対応させる。

　7，8行；グラフをプロット


処理の説明

　あらかじめ撮影しておいた画像を読み込んでそのそれぞれの画像の平均を出して、その画像ごとにグラフにプロットする。


使い方

　azurenotebook上にimagesというファイルを作成し、平均をだしたい画像にyubi1,2,3,4という名前をつける

実行の仕方

　クラウド上でCtrl＋Enterを入力する。

依存ライブラリ

　np(version 1.16.4)

　matplotlib

　
参考サイト

　なし





