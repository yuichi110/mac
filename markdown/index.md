## 画像

### 形式変換
sips -s format png --out 02.png

### サイズ変換
sips -Z 640 02.jpg --out 02-2.jpg

-Z の後に Width, Height のうち長い方の長さを指定
アスペクト比を保ってサイズ変換

### 圧縮

brew install pngquant
pngquant image.png
