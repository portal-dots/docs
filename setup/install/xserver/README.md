---
description: エックスサーバーに PortalDotsをインストールする方法をご説明します。
---

# エックスサーバーに PortalDotsをインストールする

{% hint style="info" %}
ここでは、PortalDots 3 以上について説明しています。PortalDots 1 はさくらのレンタルサーバーでのみ動作します。
{% endhint %}

## 「エックスサーバー」で PortalDots を利用するメリット・デメリット <a href="#roripoppurentarusbde-portaldots-wosurumerittodemeritto" id="roripoppurentarusbde-portaldots-wosurumerittodemeritto"></a>

* 「エックスサーバー」では、利用料金の支払いにクレジットカード決済のほか、銀行振替やコンビニ決済が利用できます。
* 「お知らせ」の検索機能はエックスサーバーでは利用できません。検索機能を利用したい場合、MySQL 5.7 以上に対応した他のレンタルサーバーの利用をご検討ください。

## このマニュアルで説明する内容 <a href="#konomanyuarudesuru" id="konomanyuarudesuru"></a>

* FTP 接続ソフトとして Cyberduck を使用する前提で説明します。
* レンタルサーバー申し込み時に決める URL を、PortalDots の URL としてそのまま利用する前提で説明します。
  * 独自ドメインを利用したい場合や、1 つのエックスサーバーの契約で PortalDots 以外のウェブサイトも設置したい場合のセットアップ方法は、このページでは説明しません。
* レンタルサーバー申し込み時に自動で作成されるメールアドレスを、PortalDots から自動配信されるメールの差出人としてそのまま利用する前提で説明します。
  * PortalDots から自動配信するメールの差出人のメールアドレスをカスタマイズしたい場合のセットアップ方法は、このページでは説明しません。



では早速、以下の「ステップ1」をクリックし、PortalDots のインストール方法を見ていきましょう。