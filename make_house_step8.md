# 床をフローリングにする

## テクスチャを用意する

テクスチャを配布しているサイトがいろいろあります。  
ライセンスをチェックしましょう。

例えば https://ambientcg.com/ の[ライセンス](https://docs.ambientcg.com/license/)は  
Creative Commons CC0 1.0 Universal License（商用利用可能、クレジット表記不要）  
です。

では、

https://ambientcg.com/list?category=WoodFloor

から好きなフローリングを選んで、1K-JPG をダウンロードします。

![Wood Floor カテゴリ](images/texture_wood_floor.png)

![WoodFloor 51](images/texture_wood_floor_51.png)

## Node Wrangler Addon を入れる

1. [Edit] - [Preferences]

で Blender の設定を開く

![Blender の設定を開く](images/blender_preferences.png)

2. 左側の Add-ons をクリックする
3. 上部の Community をチェックする
4. 検索窓に「node」と入力する
5. Node: Node Wrangler のチェックを ON にする
6. 設定を閉じる

![Blender の設定を開く](images/node_wrangler.png)


## 床に Texture をセットする

1. Shading workspace に移動
2. 床 Object を選択
3. New をクリックして Material を追加

![フローリング用の Material を追加](images/floor_wood_new.png)

4. Material の名前を「フローリング」に変更

![Material の名前をフローリングに変更](images/floor_wood_rename.png)

5. Principled BSDF を選択
6. Ctrl + Shift + t
7. ウィンドウが表示されるので、ダウンロードした zip を解凍したディレクトリを開く
8. プレビュー以外の画像（拡張子が .jpg のやつ）を全て選択する
9. Principled Texture Setup ボタンをクリックする

![Node のセットアップ](images/floor_wood_node_setup.png)

Node がセットアップされる

![Node のセットアップ](images/floor_wood_nodes.png)


### Texture Coordinate 用の Object を用意する

部屋によってフローリングの目地の大きさがバラバラなのを直します。

1. Layout workspace に移動する
2. 新しく Collection を作り、名前を「Texture Coordinate」にする

![Node のセットアップ](images/texture_coordinate_collection.png)

3. Texture Coordinate Collection を選択
4. [Add] - [Mesh] - [Plane]

![Plane Mesh を追加](images/add_mesh_plane.png)

5. 適当な場所に Plane を移動
6. Plane の名前を「Texture Coordinate 用」にする

![Plane の名前を「Texture Coordinate 用」](images/add_mesh_plane2.png)


### Texture Coordinate 用の Object を Node にセットする

1. Shading Workspace に移動する
2. フローリング Material がセットされている 床 Object （どれか）をクリックする
3. Texture Coordinate Node の Object をドラッグして、Mapping Node の Vector に繋げる
4. Texture Coordinate Node の Object: に先ほど追加した Plane を指定する
5. Mapping Node の Scale: の X, Y で大きさを調整する


![Texture Coordinate Node を編集](images/texture_coordinate_node.gif)

![床がフローリングになった](images/floor_wood_all.png)


# お風呂の床を直す

お風呂の床までフローリングになってしまったので、風呂用の Material を用意して変更します。


![床がフローリングになった](images/bath_material.gif)
