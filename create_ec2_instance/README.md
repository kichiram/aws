# EC2インスタンスの作成方法
#### 1. 下記URLにアクセスします
https://ap-northeast-1.console.aws.amazon.com/ec2/v2/home?region=ap-northeast-1#Home:
#### 2. 「インスタンス」リンクを開きます
#### 3. 「インスタンスを起動」を開きます
#### 4. 「無料利用枠の対象」と記載された「Amazon Linux」の「64 ビット (x86)」（下記参照）を選択します
![image](https://user-images.githubusercontent.com/91726058/137092217-1f46ff3f-62ef-4452-9cbb-be6c4a5ab653.png)
#### 5. 「インスタンスタイプの選択」で「無料利用枠の対象」を選択し「確認と作成」を押します
![image](https://user-images.githubusercontent.com/91726058/137093081-8ae4e6d3-bcdb-4c60-83e9-89659bd4115f.png)
#### 6. 「インスタンス作成の確認」で「起動」を押します
#### 7. 下記が開くので「新しいキーペアの作成」、キーペアタイプに「RSA」、キーペア名に「aws」を入力し「キーペアのダウンロード」を押し保存したあとに「インスタンスの作成」を押します。なお、ダウンロードしたキーペア（aws.pem）はインスタンスへ接続する際に利用するので大切に保存してください
![image](https://user-images.githubusercontent.com/91726058/137095101-f0c62ebb-c5ee-4102-a7cb-3bad4bcb6761.png)
#### 8. 以上でインスタンスの作成は完了です。念のため下記にアクセスしてインスタンスが実行中であることを確認してください
https://ap-northeast-1.console.aws.amazon.com/ec2/v2/home?region=ap-northeast-1#Instances:
