# ubuntu-fast-install
Ubuntuをインストールしたら一番最初にやること  
ターミナルを開いたら上から順に脳死でコマンドを叩け  
****

## 1. ソフトウェアアップデート
```bash
sudo apt update && sudo apt upgrade
```

## 2. ソフトウェアインストール
```bash
sudo apt install -y git vim curl jq
```

## 3. Gitの設定
```bash
git config --global user.name yudaishimanaka
git config --global user.email gurutaminn.h8@gmail.com
```

[ユーザーページ](https://github.com/yudaishimanaka) -> Settings -> Developer settings -> Personal access tokens -> Generate new token から新しいトークンを生成  
期限は`No expiration`ですべてにチェックを入れて`Generate token`を押して生成  
画面が戻り生成されたトークンをクリップボードにコピーしてターミナルに戻る  

```bash
echo [コピーしたクリップボードのトークン] > github_personal_access_token 
``` 

## 4. Google Chrome
```bash
wget -P Downloads/ https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo dpkg -i Downloads/google-chrome-stable_current_amd64.deb
```

## 5. zsh
```bash
sudo apt install -y zsh
chsh -s $(which zsh)
```

コンピューターに再ログインする

ターミナルを開き`1`を押す

## 5. Node.js
```bash
curl -o-
```

## 4. Python
```bash
sudo apt update && sudo apt upgrade
```

## 5. Go
```bash
sudo apt update && sudo apt upgrade
```

## 1. ソフトウェアアップデート
```bash
sudo apt update && sudo apt upgrade
```

## 1. ソフトウェアアップデート
```bash
sudo apt update && sudo apt upgrade
```

## 1. ソフトウェアアップデート
```bash
sudo apt update && sudo apt upgrade
```

## 1. ソフトウェアアップデート
```bash
sudo apt update && sudo apt upgrade
```

## 1. ソフトウェアアップデート
```bash
sudo apt update && sudo apt upgrade
```
