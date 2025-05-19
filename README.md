# `___cxa_current_primary_exception`を起こしてみるリポジトリ

### 環境
- Xcode: 16.3 (16E140)
- iOS: 表を参照
  - 全てシミュレータ

### 結果
起きた → ⭕️

起きなかった → ❌️

|ライブラリ\バージョン|iOS 18.4|iOS 18.3.1|iOS 17.5|iOS 16.4|iOS 15.5|
|-|-|-|-|-|-|
|[Ads-Global](https://github.com/Gurrium/reproduce-___cxa_current_primary_exception-crash/tree/Ads-Global)|❌️|⭕️|⭕️|⭕️|❌️|
|[Firebase-packages](https://github.com/Gurrium/reproduce-___cxa_current_primary_exception-crash/tree/Firebase-packages)|❌️|❌️|❌️|❌️|❌️|
