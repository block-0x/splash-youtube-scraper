# splash-youtube-scraper



<details>
<summary>English</summary>

## setting

## Overview
YouTube scraper. An unlimited number of words with the highest search ranking will be searched on YouTube to obtain video information.
Based on the acquired data, you can perform further searches to find out which videos are stuck in a wide range of searches and people can search for popular content without searching.
All the acquired data is written to csv, and you can update the data collectively when you want to update it.

## Data

|  **splash-youtube-scraper** |
|  :------: |
|  title |
|  video_url |
|  video_length |
|  views |
|  description |
|  like |
|  dislike |
|  tags |
|  channel_name |
|  channel_url |
|  channel_subscriber |
|  mean_views |
|  mean_views_views |
|  all_video_views |
|  channel_country |
|  queriy |
|  turn_id |
|  instagram |
|  twitter |
|  blog |

1. Install [docker](https://www.docker.com/)

2. Pull docker image

```bash
# Linux
sudo docker pull scrapinghub/splash
# Mac
docker pull scrapinghub/splash
```

3. Create / Start container

```bash
# Linux
sudo docker run -it -p 8050:8050 scrapinghub/splash
# Mac
docker run -it -p 8050:8050 scrapinghub/splash
```

http://localhost:8050/ Access

</details>

---

<details>
<summary>日本語</summary>

## 概要
YouTubeのスクレイパーです。検索ランキングが上位のワードをYouTube内で無制限数検索し、動画の情報を取得します。
取得したデータを元に、さらに検索をかけ、どの動画が広範囲の検索に引っかかっているのかや、流行りのコンテンツを人が検索ぜずに調べることができます。
取得したデータは全てcsvへと書き込まれ、更新したい時期のデータを一括指定して更新できます。

## 取得できるデータ

|  **splash-youtube-scraper** |
|  :------: |
|  動画のタイトル |
|  動画のURL |
|  動画の長さ |
|  動画の投稿日時 |
|  動画の説明文 |
|  動画のいいね数 |
|  動画のタグ |
|  動画のバッド数 |
|  動画を投稿したチャンネル名 |
|  チャンネルURL |
|  チャンネルの登録者数 |
|  チャンネルの平均再生数 |
|  平均再生数を1としたときの、再生数の割合 |
|  チャンネルの総再生数 |
|  チャンネルの国 |
|  検索キーワード |
|  検索後に表示されていた順番 |
|  InstagramアカウントのURL |
|  TwitterアカウントのURL |
|  BlogのURL |

## 設定

1. [docker](https://www.docker.com/)をインストール

2. dockerイメージをpull

```bash
# Linux
sudo docker pull scrapinghub/splash
# Mac
docker pull scrapinghub/splash
```
　
3. コンテナを作成・起動

```bash
# Linux
sudo docker run -it -p 8050:8050 scrapinghub/splash
# Mac
docker run -it -p 8050:8050 scrapinghub/splash
```

http://localhost:8050/ にアクセスして起動確認

# HTTP API
Splashでは，HTTP APIを使うことで簡単にページ情報を取得できます。ここではその一例を紹介しますが，より詳しく知りたい方は[公式ドキュメント](https://splash.readthedocs.io/en/stable/api.html)を御覧ください。

# HTTP API
Splashでは，HTTP APIを使うことで簡単にページ情報を取得できます。ここではその一例を紹介しますが，より詳しく知りたい方は[公式ドキュメント](https://splash.readthedocs.io/en/stable/api.html)を御覧ください。


1. [docker](https://www.docker.com/)をインストール
　
2. dockerイメージをpull

```bash
# Linux
sudo docker pull scrapinghub/splash
# Mac
docker pull scrapinghub/splash
```
　
3. コンテナを作成・起動

```bash
# Linux
sudo docker run -it -p 8050:8050 scrapinghub/splash
# Mac
docker run -it -p 8050:8050 scrapinghub/splash
```

http://localhost:8050/ にアクセスして起動確認

# HTTP API
Splashでは，HTTP APIを使うことで簡単にページ情報を取得できます。ここではその一例を紹介しますが，より詳しく知りたい方は[公式ドキュメント](https://splash.readthedocs.io/en/stable/api.html)を御覧ください。

</details>
