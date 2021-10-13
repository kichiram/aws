# EC2インスタンスへの接続方法
詳細は[公式ドキュメント](https://docs.aws.amazon.com/ja_jp/AWSEC2/latest/UserGuide/AccessingInstances.html)をご確認ください
## 接続例
### 1. EC2 instance connectを利用してブラウザから接続する
#### 1.1. 下記URLにアクセスします
https://ap-northeast-1.console.aws.amazon.com/ec2/v2/home?region=ap-northeast-1#Instances:
#### 1.2. 「インスタンスID」のリンクを開き「接続」を押します
#### 1.3. 「EC2 instance connect」タブで「接続」を押します。下記のように表示されれば成功です
![image](https://user-images.githubusercontent.com/91726058/137103464-5f40f962-4f18-400d-872a-83ade0748d35.png)
### 2. Windows10でssh接続する
#### 2.1. 下記URLにアクセスします
https://ap-northeast-1.console.aws.amazon.com/ec2/v2/home?region=ap-northeast-1#Instances:
#### 2.2. 「インスタンスID」のリンクを開き接続に必要な情報を取得します。「パブリック IPv4 DNS」の値がhostname、userはec2-userになります
![image](https://user-images.githubusercontent.com/91726058/137101274-35ce5886-14b4-4f5a-981c-47c97c96b643.png)
#### 2.3. windows PowerShellを起動します
#### 2.4. sshコマンドで接続します（下記はaws.pemは「c:\Users\\\<username>」に保存してある場合です）
```
ssh -i C:\Users\<username>\aws.pem ec2-user@ec2-54-249-95-177.ap-northeast-1.compute.amazonaws.com
```
