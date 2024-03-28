# metb4

A new Flutter project.

## 仕様
位置情報をもとにしてマッチング
マッチングの送信→2−3日後に相手側に受信
※リアルタイムではない

Air dropのタイムラグ版

プロフィール類は既存のマッチングアプリと同様

1日の送信可能数に上限あり

広告収益モデル

### マッチングの仕様
アプリ側の設定でマッチングのON/OFFを切り替える
→勤務時間帯はOFFにできるようにする

マッチング処理はバッチ処理で行う
→→ユーザーへの配信タイミングを制御したい

## Environment

ruby 3.3.0
rbenv 1.2.0
rubygems 3.5.7
flutter 
dart 




## ディレクトリ構成
参考
[lutterのディレクトリ構成はどうしたらいいの？](https://pentagon.tokyo/app/2937/#toc_id_2)

### lib
#### model
#### const

## Package

[ImageCropper](https://pub.dev/packages/image_cropper)

[Dio](https://pub.dev/packages/dio/install)
[JsonSerializable](https://pub.dev/packages/json_serializable)


## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
