# fd-library-booklist

Book List of FD-Library

[英文|English](README.md) 中文|Chinese

## 要投稿新书

### 方法一（通过 GitHub Pull Request）

如果你知道如何发起一个 PR，则根据 booklist.json 内的格式直接发起 PR。
**注意：你的 PR 必须包含电子书的下载链接（人工下载，因此网盘链接可以被接受）**
至于其他的可选额外信息，请阅读方法二。

### 方法二（通过电子邮件）

发送邮件到 publish_etl@tsstudio.top.

#### 邮件**必须**包含:

书名  
作者 (**必须**包括封面上的所有作者，可以包括其他作者)  
ISBN 码  
出版社  
版次（严格按照书籍内页，删掉所有空格，数字使用汉字还是数字取决于书籍原本使用的）  
电子书下载链接

#### 邮件**可以**包含：

书的条码  
书的封面

## 下载链接的编码方式

下载链接分为两部分，地域和索引，最终链接是 `Endpoint+index`。  
地域可以被认为是镜像服务器，以`https://`开始，以 `/`结束。

书籍本身的下载链接: book/`sha256(ISBN+revision)`.pdf

书籍封面的下载链接（可选）: cover/`sha256(ISBN+revision)`.jpg
