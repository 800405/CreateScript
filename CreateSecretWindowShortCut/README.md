# Chromeのシークレットウィンドウで実行するショートカットを作成

## Chromeで特定のURLをシークレットウィンドウで実行するショートカットを作成する

- Chromeのパスはレジストリから取得するため、環境によってはChromeのパスが違う可能性があるため注意すること
- 規定のブラウザがChromeであること前提で作成しているので規定のブラウザがChromeでない場合は正しくないものが作成されます
- 「HKEY_CLASSES_ROOT\HTTP\shell\open\command\」から規定のブラウザのパスを取得する ※Windows10だと規定のブラウザのパスが入っていないので仕様が変わったかも……
