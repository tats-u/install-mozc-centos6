# mozcインストールシェルスクリプト for CentOS6.x
## はじめに
CentOS6.xはデフォルトでAnthyを日本語IMEとして採用しています。しかし、このAnthyの変換精度はそこまでよくありません。ある程度パソコンに詳しい人ならGoogleの開発した「Google日本語入力」をご存知でしょう。しかし、Android以外のLinuxではこれを使うことはできません。しかし、Ubuntuなどではオープンソース版である「mozc」を使用することができます。mozcは少なくともAnthyよりは賢いIMEです。そうなるとCentOSにもインストールしたいところですが、公式リポジトリには入っていません。従って、シェルスクリプトの実行だけでインストールできるようにしたいと思い、ここに公開することにしました。
## インストール方法
###オフライン版(中身をダウンロード)

```
sudo ./install-mozc
```

###オンライン版

```bash
wget https://raw.githubusercontent.com/tats-u/install-mozc-centos6/master/onlineinstall-mozc
sudo ./onlineinstall-mozc
rm -f onlineinstall-mozc
```
