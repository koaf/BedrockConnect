# BedrockConnect

![Logo](https://i.imgur.com/H9zVzGT.png)

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)
[![HitCount](http://hits.dwyl.com/Pugmatt/BedrockConnect.svg)](http://hits.dwyl.com/Pugmatt/BedrockConnect)

Minecraftの統合版では、Xbox One、Nintendo Switch、PS4のプレイヤーは、Mojang/Microsoftが承認した公式サーバーのみでのプレイに限定されます。これらのプレイヤーは、IP/アドレス経由でサーバーに参加することができません。Java版のサーバーコミュニティは、Minecraftを作り上げた大きな要素の1つであり、現在「Mojangサーバーパートナー」とされているサーバーを今日の姿にしたものでもあるので、これは私や他の人にとっても問題です。私はこれを解決したかったので、誰でも簡単にセットアップできる解決策を作りました。

BedrockConnectは、Xbox One、Nintendo Switch、PS4のMinecraft Bedrock Editionプレイヤー向けに、任意のサーバーIPに参加できるとともに、サーバーの一覧を管理できるサーバーリストにもアクセスできる使い勝手の良いソリューションです。ダウンロードは不要で、設定を少し変更するだけです。


   * [FAQ](#faq)
   * [Publicly available BedrockConnect instances](#publicly-available-bedrockconnect-instances)
   * [Hosting your own serverlist server](#hosting-your-own-serverlist-server)
   * [Defining your own custom servers](#defining-your-own-custom-servers)
   * [Change wording of serverlist](#change-wording-of-serverlist)
   * [Using your own DNS server](#using-your-own-dns-server)
   * [Libraries used](#libraries-used)
   * [Donations](#donations)

# FAQ

**How does it work?** Minecraft Bedrock Editionでは、どのバージョンのプレイヤーも、公式サーバーに参加することができます。DNS サーバーを使用することで、これらのサーバーに参加するために使用されるドメインを、実際のサーバーではなく、BedrockConnect サーバーリストサーバーに直接アクセスできるようにすることができます。
要するに外部サーバーに入れるようになるってことったね

BedrockConnectサーバーリストサーバーは、Minecraftのサーバーに参加することを目的とした特製のMinecraftサーバーです。そう、Minecraftサーバーから、Minecraftサーバーに参加するのです。通常のサーバーリストのように、好きなサーバーに転送したり、サーバーを保存したりすることができます。

**What is a DNS server?** 優先DNSを【】に設定して、代替DNSを8.8.8.8にしたらつかえるよ


**Some featured server aren't redirecting to the serverlist** BedrockConnectのサーバーリストにリダイレクトされる注目のサーバーとされないサーバーがある場合、デバイスやゲーム機のDNSキャッシュが更新されていないことが原因である可能性があります。キャッシュがクリアされるのをゲーム機で待つ以外には、何もできません。

また、Hiveなどの一部のサーバーは、BedrockConnectなどのDNSサーバーにオーバーライドされないようにするためのDNSSECを使用していることも考えられます。これはまだテスト中で、ある人のコンソールではうまくいき、他の人のコンソールではうまくいかないようです。


# Donations

If you like what you see, feel free to throw a few bucks. I won't ever charge for this service. Donations go toward hosting the main BedrockConnect instance, 104.238.130.180.

https://paypal.me/Pugmatt

