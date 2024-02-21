# audio-fromexamples

https://github.com/huggingface/transformers/tree/main/examples/pytorch/audio-classificationよりコードをコピーして変更

## task

### 動作確認まで
+ [x] 保存先をraid_elmoに変更
  - サーバー側にディレクトリも作る
+ [x] cache_dirを変更
  - データセットもcache内に保存（10GBある）
+ [x] tensorboardにlog
+ [x] .gitignore
+ [x] サーバーにsftp
+ [ ] 仮想環境の作成