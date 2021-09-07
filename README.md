# [Netflix clone](https://netflix-clone-f3505.web.app/)

Netflixのクローンサイトです。

[The Movie Database API](https://www.themoviedb.org/documentation/api)から映画とドラマの情報を取得しています。

[【React+TypeScript】Netflixのクローンを作るチュートリアル](https://zenn.dev/gunners6518/books/4c4672f32dd100)で作成したものを拡張しました。

拡張前は映画とドラマの画像をクリックすると、react-youtubeとmovie-trailerモジュールを用いてYouTubeの予告動画が見つかれば、動画が再生されるようになっていましたが、映画とドラマに関係のない動画が再生されたり予告動画が見つからず動画が再生されないことが多く、うまく機能していませんでした。

react-youtubeとmovie-trailerモジュールを使うのではなく、[YouTube Data API](https://developers.google.com/youtube/v3/getting-started?hl=ja)を用いて、映画とドラマの画像がクリックされると映画とドラマのタイトルでYouTubeを検索して、最も再生されている動画を取得し、表示されるようにしました。

また、react-slickモジュールを追加して画像がカルーセルで表示されるようにしました。

サイトのURLはこちらです。

https://netflix-clone-f3505.web.app/

# 使用技術

## 開発環境

* Windows 10 Home

* Docker

* Docker Compose

## フロントエンド

* HTML

* SCSS

* JavaScript

* TypeScript

* Node.js 14.17.5

* React 17.0.2

## インフラストラクチャ

* Firebase Hosting
