リオ式「ブレンダーちゃん」は、SearKitchen氏の"Blender-chan!の三面図を元に、川音リオが制作したBlenderの非公式マスコットキャラクターです。このモデルは https://kawane.booth.pm にて無料配布してます。


【VRChatにモデルをアップロードしようぜ編】

1. 新しいUnityプロジェクトを開きます。
2. https://vrchat.com/home/download から最新のVRCSDKをインポートします。
3. Dynamic Bonesをインポートします（任意)
4. blender-chan_v0.22h.unitypackage をインポートします。
5. Ctrl+5でProjectパネルを開き、Assets > Blender-chan > v22h > blender-chan_v0.22j.fbx のところにあるファイルを左のHierachyタブへD&Dします）。
6. Scene内のblender-chan_v0.22jと書かれた青いボックスをクリックします。
7. UIの右側にあるInspectorタブの一番下にあるAdd ComponentからVRC Avatar Descriptorを追加します。
7.1 "View Position" をX:0 Y:1.4 Z:0.06に設定します。
7.2 "Auto Detect!" を押してLipsyncを設定します。
7.2.1 Visemeの "ih "と "oh "には、"new_I "と "new_U "を使ってね。
8. Eye Look は現在サポートされてをりません(ごめんなさい(_ _；))
9. "Playable Layers" > Base > FX から "Blender-chan_HandsLayer"を選択します。
10. "Playable Layers" > Base > Base から"Blender-chan_Locomotion"を選択します。
11. "Expressions" > Menu から "Blender-chan_ExpressionsMenu"を選択します。
12. "Expressions" > Parameters から "Blender-chan_ExpressionParameters "を選択します。
13. ダイナミックボーンの設定をします(任意)。現在揺れ物ボーンが入ってるパーツは髪の毛と制服の帯です。
14. VRCSDKのエラーを修正します。
15. アップロードします! もし良ければ高評価とチャンネル登録...じゃなかった、アバターをPublicにして、クローン可にしてくださると嬉しいです!(でもなんかダメだと思ったら普通にPrivateにしてくださいまし)
おつかれさまです!!

全然関係無いけどこのreadmeは川音リオがSKK日本語入力を使って初めて作成した書類だよ。興味がある人はニコニコ大百科のSKKの記事を読んでみてねっ!


【以下英語版】
Blender-chan RT (リオ式ブレンダーちゃん) is the unofficial mascot character for Blender modeled by KawaneRio based on SearKitchen's sketch of "Blender-chan!". Blender-chan RT is in no way affiliated with the Blender Foundation or any of its affiliates or subsidiaries (hence, "unofficial"). This is a free/open model and can be found on https://kawane.booth.pm

Instructions on uploading this model to VRChat follows:

1. Open a new Unity Project
2. Import the latest VRCSDK found in https://vrchat.com/home/download
3. Import Dynamic Bones (Optional)
4. Import the blender-chan_v0.22h.unitypackage
5. Ctrl+5 and open Project, then go to Assets > Blender-chan > v22h > blender-chan_v0.22j.fbx and Drag&Drop the said file into your scene (D&D to the Hierachy tab on the left)
6. Click on the blue box that says blender-chan_v0.22j in your scene.
7. Add the VRC Avatar Descriptor from the Add Component button located at the bottom of the inspector panel on the right hand side of the UI.
7.1 Set the "View Position" to X:0 Y:1.4 Z:0.06
7.2 Setup the Lipsync by pressing "Auto Detect!"
7.2.1 Note: Please use "new_I" and "new_U" for the viseme "ih" and "oh"
8. Eye Look is currently unsupported for some reason (sorry!><)
9. Go to "Playable Layers" > Base > FX and Define define "Blender-chan_HandsLayer"
10. Also define the locomotion layer via "Playable Layers" > Base > Base and select "Blender-chan_Locomotion"
11. Go to "Expressions" > Menu and define "Blender-chan_ExpressionsMenu"
12. Go to "Expressions" > Parameters and define "Blender-chan_ExpressionParameters"
13. Setup the Dynamic bones (optional). There are bones in the fronthair, sidehair, pythonhair, and the side ribbons of the uniform.
14. Correct any errors from VRCSDK if necessary.
15. Upload! It would be nice if the avatar was Public and Clonable, but that's ultimately up to you. Please use common sense and your best judgement.

Not that it matters at all, but this readme was the first document I've ever made with GNU Emacs (you know? the best text editor ;)
