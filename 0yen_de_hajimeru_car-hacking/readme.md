# 正誤表

| ページ | 記載   | 正しい記載 | 備考 |
| ------ | ------ | ---------- | ---- |
| P27    | 攻撃車 | 攻撃者     |      |



# 補足事項

## [p3] CAN-FD は名前に反して CAN と直接の互換性はなく～
誤解を招く表現なので補足します。  
そもそも CAN-FD は CAN も対応しています。つまり CAN-FD 対応 IC であれば、従来の CAN 通信を行うことも可能です（ただし同じ CAN バス内で CAN、CAN-FD の混在はできません)。

しかしながら、CAN-FD は論理的な規格だけではなく電気的な仕様変更を伴っているため、対応をするためには CAN コントローラおよび CAN トランシーバーの置き換えが必要になります。
「直接の互換性」というのは、ソフトウェアのアップデートか何かですぐに対応できるかどうか、そして CAN、CAN-FD が同じ CAN バス内で混在できるかどうかを示したものでした(=>それができないので直接の互換性はないという主張）。

が、改めて読んでみると適切な表現ではありませんでした。
お詫びします。
