# FadeManager.cs

## Overview

[https://kenko-san.com/unity-fade/](https://kenko-san.com/unity-fade/)

様から頂きました。
大変役立っております！

### change point
* FadeIn, FadeOut の引数でフェード時間を設定できるようにしました
* 移動先シーンをシーン名で指定するようにしました

## Usage

### フェードイン
```
FadeManager.FadeIn(1.5f);
```

###フェードアウト
```
FadeManager.FadeOut("GameOverScene", 3f);
```