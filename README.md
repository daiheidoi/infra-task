# infra-task
Infraの課題やってみよう

## 神からの課題
1. centos7のdocker imageを使ってapacheでphp7.3を動かし、hello worldと /index で表示されるようにせよ(/index.phpはダメとする)
2. 1を今度はaws ec2を使って実現せよ
3. aws RDSをたてて外部からmysql8を使えるようにせよ
4. 踏み台(basion)サーバーの活用意義を調べて説明せよ
5. 踏み台サーバーを構築してrdsにsshトンネリングできるようにせよ(この際、VPCやネットワークゲートウェイなどの用語の意味を調べること)
6. IAMを作成し、第三者のログインアカウントを作成せよ(権限は問わないものとする)
7. s3のバケットを作成し、適当な画像をpublicで保存してURLを共有せよ
8. cloudfrontを作成し、7で用意した画像をcloudfront経由で表示させよ