# 外部からssh以外のアクセスを許可する設定をします。
#### 1. 下記URLにアクセスします
https://ap-northeast-1.console.aws.amazon.com/ec2/v2/home?region=ap-northeast-1#Home:
#### 2. 「セキュリティグループ」リンクを開きます
#### 3. 下記のようにセキュリティグループが2つあると思うので「default」じゃない「セキュリティグループ ID」リンクを開きます
![image](https://user-images.githubusercontent.com/91726058/137287842-75e9aedb-9523-4688-8708-60ddfa7badda.png)
#### 4. 「インバウンドルール」タブを開き「Edit inbound rules 」を押します
#### 5. 「ルールを追加」を押し追加された行にタイプを「全てのTCP」、ソースで「Anywhere IPv4」を選択して「ルールを保存」を押します
![image](https://user-images.githubusercontent.com/91726058/137289487-28cd18d1-6374-4dd2-9432-f2bb1e8584fa.png)
#### 6. 以上で設定は完了です
