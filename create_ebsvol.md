## EBSボリュームを作成してみましょう

1. マネジメントコンソールにアクセスし、EC2のサービス画面へ移動しましょう。
1. 画面左のナビゲーションペイン(サブメニュー)から、`ボリューム`をクリックします。

![image](https://github.com/user-attachments/assets/5e68f693-8ba9-4a87-84a7-b988d80c6e99)

1. `ボリュームの作成`ボタンをクリックします。

![image](https://github.com/user-attachments/assets/e97d71bd-0d0e-4650-89d6-a3c00cd2230a)

1. ボリュームの作成画面が開きますので、次のように設定します。
    - ボリュームタイプ : 汎用SSD (gp2)
    - サイズ(GiB) : 8
    - 他の設定はデフォルト
1. `ボリュームの作成`ボタンをクリックします。
1. EBSボリュームが作成されました。既存のEC2インスタンスにアタッチして利用することができます。
