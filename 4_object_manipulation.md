# Object 操作



## Quick Tools Menu

![Quick Tools Menu](images/quick_tools_menu.png)

### ショートカット

表示/非表示切り替え

- t

### 画面上で操作

表示

- 左端の > をクリック

![Quick Tools Menu](images/quick_tools_menu_show.png)


### 手元に表示

- Shift + Space

![Quick Tools Menu を手元に表示](images/quick_tools_menu_with_label.gif)



## Additional Quick Settings

![Additional Quick Settings](images/additional_quick_settings.png)

### ショートカット

表示/非表示切り替え

- n

### 画面上で操作

表示

- 右端の < をクリック

![Quick Tools Menu](images/additional_quick_settings_show.png)



## Undo

### ショートカット

- Ctrl (Command) + z

### 画面上で操作

- [Edit] - [Undo]


## Mesh Object 追加

[3D Cursor](cursor.md) の位置に出現します

### ショートカット

- Shift + a
  - [Mesh] - [Cube]とか

### 画面上で操作

- [Add] - [Mesh] - [Cube]とか

![Mesh Object 追加](images/object_add.gif)

## 削除

### ショートカット

- x 
  - d

![Object 削除](images/object_delete.png)

### 画面上で操作

- [Object] - [Delete]

![Object 削除](images/object_delete2.png)



## 選択

![Duplicate Objects](images/object_selection.gif)

### 単一選択
 
- 左クリック

（＊右クリックで Object 選択する設定にすることも可能）

### 選択解除

- 空の領域を左クリック

### 全選択

#### ショートカット

- a

#### 画面上で操作

- [Select] - [All]

![Duplicate Objects](images/select_all.png)


### 選択全解除

#### ショートカット

- Alt (option) + a

#### 画面上で操作

- [Select] - [None]

![Duplicate Objects](images/select_none.png)

### 複数選択

- Shift + 左クリック

選択を解除するときも同じ操作

最後に選択されたオブジェクトが Active Object になる。Active Object は他より少し明るい選択色になっている。

![Active Object](images/active_object.png)


### 範囲選択

Select Box の状態で

- 左クリックしたままドラッグ

### 選択解除範囲選択

Select Box の状態で

- Ctrl + 左クリックしたままドラッグ


## 移動

移動するとき

- Ctrl を押していると、グリッドに snap しながら移動する
- Shift を押していると、細かく移動する

### ショートカット

- オブジェクトを選択
  - g : 移動 
    - x : X軸に沿って移動 
    - y : Y軸に沿って移動 
    - z : Z軸に沿って移動 
    - shift + x : YZ平面に沿って移動 
    - shift + y : XZ平面に沿って移動 
    - shift + z : XY平面に沿って移動 
    - x x : Local X軸に沿って移動
    - y y : Local Y軸に沿って移動
    - z z : Local Z軸に沿って移動
    - shift + x x : Local YZ平面に沿って移動
    - shift + y y : Local XZ平面に沿って移動
    - shift + z z : Local XY平面に沿って移動
    - esc : キャンセル

![ショートカットでオブジェクト移動](images/object_move_shortcut.gif)

### 画面上で操作

- オブジェクトを選択
  - Move tool をクリック
    - 真ん中の白い円をドラッグ : 自由移動
    - X軸の矢印をドラッグ : X軸に沿って移動
    - Y軸の矢印をドラッグ : Y軸に沿って移動
    - Z軸の矢印をドラッグ : Z軸に沿って移動
    - 赤の四角をドラッグ : YZ軸方向に沿って移動
    - 緑の四角をドラッグ : XZ軸方向に沿って移動
    - 青の四角をドラッグ : XY軸方向に沿って移動
    - Transform Orientation を Local にすると、Local の座標軸に沿って移動
    - ドラッグ中に esc : キャンセル

![Move tool](images/object_move_tool.png)

![オブジェクト移動](images/object_move.gif)

### リセット

- Alt (Option) + g
- [Object] - [Clear] - [Location]

## 回転

回転するとき

- Ctrl を押していると、5°ずつ回転する
- Shift を押していると、細かく回転する

### ショートカット

- オブジェクトを選択
  - r : 回転
    - x : X軸まわりに回転
    - y : Y軸まわりに回転
    - z : Z軸まわりに回転
    - x x : Local X軸まわりに回転
    - y y : Local Y軸まわりに回転
    - z z : Local Z軸まわりに回転
    - esc : キャンセル

![ショートカットでオブジェクト回転](images/object_rotate_shortcut.gif)

### 画面上で操作

- オブジェクトを選択
  - Rotate tool をクリック
    - 外周の白い円をドラッグ : 見えている向きを軸として回転
    - 内側の色付き曲線の間をドラッグ : 自由回転
    - 赤の曲線をドラッグ : X軸まわりに回転
    - 緑の曲線をドラッグ : Y軸まわりに回転
    - 青の曲線をドラッグ : Z軸まわりに回転
    - Transform Orientation を Local にすると、Local の座標軸に沿って移動
    - ドラッグ中に esc : キャンセル

![Rotate tool](images/object_rotate_tool.png)

![オブジェクト回転](images/object_rotate.gif)

### リセット

- Alt (Option) + r
- [Object] - [Clear] - [Rotation]



## 拡大縮小

- Ctrl を押していると、グリッドに snap しながら拡大縮小する
- Shift を押していると、細かく拡大縮小する

### ショートカット

- オブジェクトを選択
  - s : 拡大縮小 
    - x : X軸方向に拡大縮小
    - y : Y軸方向に拡大縮小 
    - z : Z軸方向に拡大縮小 
    - shift + x : YZ軸方向に拡大縮小 
    - shift + y : XZ軸方向に拡大縮小 
    - shift + z : XY軸方向に拡大縮小 
    - x x : Local X軸方向に拡大縮小
    - y y : Local Y軸方向に拡大縮小
    - z z : Local Z軸方向に拡大縮小
    - shift + x x : Local YZ軸方向に拡大縮小
    - shift + y y : Local XZ軸方向に拡大縮小
    - shift + z z : Local XY軸方向に拡大縮小 
    - esc : キャンセル

![ショートカットでオブジェクト拡大縮小](images/object_scale_shortcut.gif)

### 画面上で操作

- オブジェクトを選択
  - Scale tool をクリック
    - 外側をドラッグ : XYZ軸方向に拡大縮小
    - 赤の直線をドラッグ : X軸方向に拡大縮小
    - 緑の直線をドラッグ : Y軸方向に拡大縮小
    - 青の直線をドラッグ : Z軸方向に拡大縮小
    - 赤の四角をドラッグ : YZ軸方向に拡大縮小
    - 緑の四角をドラッグ : XZ軸方向に拡大縮小
    - 青の四角をドラッグ : XY軸方向に拡大縮小 
    - Transform Orientation を Local にすると、Local の座標軸に沿って移動
    - ドラッグ中に esc : キャンセル

![Scale tool](images/object_scale_tool.png)

![オブジェクト拡大縮小](images/object_scale.gif)

- オブジェクトを選択
  - Scale tool を長押しして Scale Cage にカーソルを移動してから離す
    - Cage 内のハンドル以外をドラッグ : XYZ軸方向に拡大縮小
    - Cage のハンドルをドラッグ : Cage のハンドル方向に拡大縮小
    - ドラッグ中に esc : キャンセル


![オブジェクト Scale Cage で拡大縮小](images/object_scale_cage.gif)


### リセット

- Alt (Option) + s
- [Object] - [Clear] - [Scale]


## 複製

### Duplicate Objects

メッシュも含めて複製する

- オブジェクトを選択
  - Shift + d
  - または
  - [Object] - [Duplicate Objects]

![Duplicate Objects](images/duplicate.gif)

![Duplicate Objects](images/duplicate.png)

### Duplicate Linked

メッシュがリンクしたオブジェクトを複製する
 
- オブジェクトを選択
    - Alt(Option) + d
    - または
    - [Object] - [Duplicate Linked]


![Duplicate Linked](images/duplicate_linked.gif)

![Duplicate Linked](images/duplicate_linked.png)

[メッシュとは](about_mesh.md)


## Parent

オブジェクトに親子関係をセットする

- 子にするオブジェクトを選択
- Shift を押しながら親にするオブジェクトを選択
  - [Object] - [Parent] - [Object]
  - 右クリック [Parent] - [Object]
  - Ctrl (Command) + p - [Object]

![Parent](images/parent_object.png)

オブジェクトが親子関係になると、 親の Transform（移動、回転、拡大縮小）が子にも適用されます。

![Parent](images/parent_object.gif)

### 解除

#### 親の Transform を適用しないで解除

- 解除する子オブジェクトを選択
  - [Object] - [Parent] - [Clear Parent]
  - 右クリック [Parent] - [Clear Parent]
  - Alt (Option) + p - [Clear Parent]

![Clear Parent](images/parent_clear.gif)


#### 親の Transform を適用して解除

- 解除する子オブジェクトを選択
  - [Object] - [Parent] - [Clear and Keep Transformation]
  - 右クリック [Parent] - [Clear and Keep Transformation]
  - Alt (Option) + p - [Clear and Keep Transformation]

![Clear and Keep Transformation](images/parent_clear_and_keep_transformation.gif)


## Object の Origin を変える

Object の Origin とは、Location が 0,0,0 になる位置です

## Object の Origin を 3D Cursor の位置にする

- オブジェクトを選択
  - [Object] - [Set Origin] - [Origin to 3D Cursor]
  - 右クリック [Set Origin] - [Origin to 3D Cursor]

![Clear Parent](images/origin_3d_cursor.gif)
