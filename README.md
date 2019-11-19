# Midori-chan  
## ***MCP-OfficialSite***  

> 公開準備中  
> URLは↓  
> https://mie-cheeringparty.netlify.com/  
  
## **概要**
githubとNetlifyをアカウント連携し、Netlifyで公開しています。  
  
### ・**NetlifyとGithub**  
ソースコードはGithub上で管理します。リポジトリに含まれるファイルは全てオープンになっているため、  
個人情報・アカウント情報等を含むファイルはアップロードしないでください。  
#### ホスティング  
githubのmasterブランチがNetlifyでホスティングされています。  
masterブランチに変更を反映(commit)すると、公開されているサイトに  
即時反映される為注意してください。  
  
### .htaccess  
旧サイトに.htaccessを設定すると新サイトへの誘導がスムーズ。  
旧サイトへのアクセスをすべて新サイトへリダイレクト(転送)するため、導入するかどうかお任せします。  
RewriteEngine On
RewriteRule  index.html$ https://mie-cheeringparty.netlify.com/index.html [R=301,L]
  
---
> **以下、関係者向けの内容となります。**  
## 使い方  
### github  
> ※基本的にコンテンツの更新(テキスト・画像など)はmicroCMSから更新するため、  
> 　github上では編集作業を行ないません。
  
### 準備中HeadlessCMS  
[microCMS](https://microcms.io/)を使用してAPIでコンテンツを取得し、サイト内に表示します。  
コンテンツの更新は原則microCMSから実施し、HTMLを編集する必要がなくなります。  
