# item_modifier-set_custom_data
item_modifierの1項目であるset_custom_dataのサンプルになります。

~詳しくはブログ記事『[]()』を参考にしてください。~<br>
現在執筆中

<h3>概要</h3>
アイテムにデータを付与できます。

<h3>使い方</h3>

データパック導入後、ワールドに入り```/reload```と入力し実行してください。

ダイヤモンドが付与されますので、それを手に持った状態で以下のコマンドを実行します。

```copy
/item modify entity @s weapon.mainhand sample:set_custom_data
```

見た目上の変化は起きませんが、正しく実行できていればデータが格納されました。

以下のコマンドでデータを確認できます。<br>
※このコマンドも手に持っている状態である必要があります。

```copy
/data get entity @s SelectedItem
```

test、list、sampleといったデータが確認できればOKです。
