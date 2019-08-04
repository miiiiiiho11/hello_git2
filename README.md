# どんな処理を実装したのか
初めに、画像の読み込みをし、この画像に対してフーリエ変換と逆フーリエ変換を行い、３枚の画像を名前を付けて並べて表示した.

次に、逆フーリエ変換、正弦波、マウス操作時の３つの関数を定義した.

さらに、別ウィンドウを３つ表示し、黒い画像の上でマウスの左ボタンを（押したあと）上げたときのマウスの位置座標を取得し白く塗りつぶし、計算結果を他の２つのウィンドウにリアルタイムで表示した.

# 依存ライブラリとバージョン
openCV(4.1.0),numpy(1.16.2),matplotlib(3.0.3)

# 参考文献
Hatena Blog "PythonとOpenCVで画像処理④【マウスイベント】"
http://rasp.hateblo.jp/entry/2016/01/24/204539
'マウスイベントを使って図形やテキストを描画'のコード

Qiita "Pythonで白画像を作成する時のメモ。" 宮本 圭一郎
https://qiita.com/miyamotok0105/items/b04fab6598f690fd60ba
'カラー版'のコード

EnsekiTT Blog "Python+OpenCVでMouseイベントを取得してお絵かきする話" EnsekiTT
https://ensekitt.hatenablog.com/entry/2018/06/17/200000
'左クリックがあったら表示'のコード

OpenCV "フーリエ変換" 
http://labs.eecs.tottori-u.ac.jp/sd/Member/oyamada/OpenCV/html/py_tutorials/py_imgproc/py_transforms/py_fourier_transform/py_fourier_transform.html
'Numpyを使ったフーリエ変換'のコード

# 実行の様子


