# officeconfig
microsoft office カスタム設定

## カスタムadd-in
copy makeShape.xlam %USERPROFILE%\AppData\Roaming\Microsoft\AddIns

## スタートアップ画面を表示させずにデフォルトテンプレートを自動で起動させる方法

### Excelの場合
Excel→オプション→詳細設定
     → 起動時にすべてのファイルを開く
     → このアプリケーションのスタート画面を表示する→オフ
     → copy "%APPDATA%\Microsoft\Excel\XLSTART\Book.xltx"

### PPTの場合
PowerPoint→オプション→全般→このアプリケーションのスタート画面を表示する→オフ
     → copy "%APPDATA%¥Microsoft¥Templates\blank.potx"
