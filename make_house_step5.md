# 窓を作る

1. 「窓」Collection を追加する 
2. 他の Collection を非表示にする

![窓 Collection を追加する](images/window_collection.png)

3. [Add] - [Mesh] - [Cube]
4. n 
5. Dimension の X を 1 m にする 
6. Dimension の Y を 0.142 m にする 
7. Dimension の Z を 1 m にする 
8. Location の X を 0 m にする 
9. Location の Y を 0 m にする 
10. Location の Z を -0.5 m にする

![窓の形にする](images/window_transform.png)

11. [Object] - [Apply] - [All Transforms] をクリックして、変更した Transform をメッシュに適用する

![変更した Transform をメッシュに適用する](images/window_transform_apply.png)

12. 窓 Object を窓の位置に移動し、Location の Z を 2 m にする

![窓を移動する](images/window_move.png)

13. 窓をつける壁 Object を選択し、Properties の Modifiers を選択する

![Properties の Modifiers を選択する](images/window_modifiers.png)

14. Add Modifiers をクリックし、[Generate] - [Boolean] を選択する

![Boolean Modifier を追加する](images/modifiers_generate_boolean.png)

![Boolean Modifier](images/boolean_modifier.png)

15. Boolean Modifier の Object のところにあるスポイトツールをクリックし、窓 Object を選択する

![Boolean Modifier のスポイトツール](images/boolean_modifier_object_selection.png)

![Boolean Modifier のスポイトツール](images/wall_modifier_window.png)

16. 窓 Object を「部屋1_窓」にリネームする
17. 部屋1_窓 Object を選択したあと、Shift を押しながら窓のある壁 Object を選択する

![Boolean Modifier のスポイトツール](images/window_selections.png)

18. Ctrl (Command) + p
19. Object を選択

![Boolean Modifier のスポイトツール](images/set_parent_to.png)

（壁 Object の移動に窓が追随することを確認）

20. 部屋1_窓 Object を非表示にする

![Boolean Modifier のスポイトツール](images/window_room1.png)

21. 部屋2 に窓をつける
22. リビングに掃き出し窓をつける（高さ 2.01 m、幅自由）
23. キッチンに横長の窓をつける（高さ 30 cm、幅自由）
24. 廊下の突き当たりに窓をつける（50 cm x 50 cm）
25. トイレに窓をつける（50 cm x 50 cm）

![全ての窓を作る](images/window_all.png)
