# Another One Of Statbars
趣味に走りまくったステータスバーを表示します。  

## 表示  
![1](https://user-images.githubusercontent.com/50558182/71636975-472e3980-2c7c-11ea-82be-5089f5b56578.png)  
![4](https://user-images.githubusercontent.com/50558182/71637005-e5220400-2c7c-11ea-82fa-0db3c8d2c194.png)  

水色はSP  
緑色はHP  
紫色は装備耐久値  
黄色はスタミナ  
  
画面中央の水色ダイヤはセット装備スキルのクールダウン  

です。

* アーケインエナジー有効化中は以下の画像のように２段表示になり、SP回復量がわかります。  
![2](https://user-images.githubusercontent.com/50558182/71636976-472e3980-2c7c-11ea-9caf-bae39c39d0f6.png)
* ヒーリングファクター有効化中は以下の画像のように２段表示になり、HP回復可能閾値がわかります。  
![3](https://user-images.githubusercontent.com/50558182/71636977-472e3980-2c7c-11ea-8616-a6d0bb8ed6a7.png)

## 使い方
バー中央のアイコンをつかむとドラッグできます。  
画面中央上か下に配置するようデザインしています。  
バーは最大値に応じて結構長く伸びます。  (HPは100000、SPは10000まで伸びます) MHのオマージュです。  


元のステータスバーは  
weizlogy氏のCompact Heads Up Display 及び MizukiBelhi氏のExtendedUI をご使用いただいて片づけておくと便利です。  
セット装備スキルのクールダウンはおおよそ対応しているかと思いますが、すべてをテストはしておりません。

## 注意点
* Lv300以上のキャラを想定して作成していますので、それ未満のキャラだと表示がいまいちかもしれません。

## 今後の予定
* カスタマイズできるようにする
* バー長さを短くする・固定するモードの追加
* 水色ダイヤが表す内容の変更もしくはカスタマイズできるように

# リリースノート
## v0.0.3
* 表示の微調整
  今回のアップデートにより表示位置が少し右にずれます。  
  画面をドラッグできなくなった場合は、`addons/anotheroneofstatbars/`フォルダ内の`settings.json`を削除してください。
* バーを常時レンダリングに変更（今まではステータス変化時にレンダリング）  
* ステータスが30%以下になった時に該当するバーの背景を点滅するように
  (装備耐久値については、0になったら点滅をやめます)

## v0.0.2
* HP・SPの最大値がバーの上限に達しているとき、バー減少エフェクトの色がおかしいのを修正
* 装備耐久値の色を明るくした
* 表示の微調整

## v0.0.1
* 初回試験公開