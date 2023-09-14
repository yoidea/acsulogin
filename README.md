# acsulogin

信州大学の学内ネットワークのACSUにSSOログインするためのシェルスクリプト
https://www.shinshu-u.ac.jp/institution/iic/service/portalsiteacsu.html

## インストール
Homebrewからインストールできる
```bash
brew tap yoidea/acsulogin
brew install acsulogin
```
もしくは手動でインストール
```bash
git clone https://github.com/yoidea/acsulogin.git
cd acsulogin/
cp acsu /usr/bin
```

## 使用法
- `acsu`: ACSUネットワークにログイン（省略形）
- `acsu init`: 初期設定を行う
- `acsu login`: ACSUネットワークにログイン
- `acsu reset`: 設定をリセット
