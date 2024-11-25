### exp011

- late sub
- 信号機のマスク情報とdepth画像をチャネル方向に結合して入力とするNN
- 数値特徴量も入力とする
- 全結合層を4層に
- targetを標準化して学習する → 推論時にスケールを戻す
- backbone：resnet18
