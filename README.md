# Probabilistic-robotics
確率ロボティクスの課題としてJupyter Notebookを使ったパーティクルフィルタの実装を行った

# ideal_robot.ipynb
詳細確率ロボティクスに掲載されているコードを使用し、自律移動ロボットのモデル化を行った

# noise_simulathion.ipynb
詳細確率ロボティクスに掲載されているコードを使用し、不確かさのモデル化を行った
このコードで使用されているロボットのモデルはideal_robot.ipynbにより設定されたモデルをコードの再利用により使用している

# particle_filter.ipynb
詳細確率ロボティクスに掲載されているコードを使用し、パーティクルフィルタの実装を行った
このコードで使用されているロボットのモデルはideal_robot.ipynbにより設定されたモデルをコードの再利用により使用している　同様に不確かさのモデルはnoise_simurathion.ipynbにより設定されたモデルをコードの再利用により使用している

ランドマークを３つ設定することにより、参考にしたコードと比較して自己位置推定の精度の向上が確認できた

# 参考
詳細確率ロボティクス

[ryuichiueda/LNPR_BOOK_CODES](https://github.com/ryuichiueda/LNPR_BOOK_CODES/tree/master)

# 謝辞
このパーティクルフィルタは[上田隆一さん](https://github.com/ryuichiueda/LNPR_BOOK_CODES/tree/master)
のコードを参考に製作しました。誠にありがとうございます。


