# pics
使用 github + PicGo 作为图床。

## 1、github 配置

- 在 github 上创建一个 public 库
- 创建成功后， 在用户头像下的 setting 中生成 token

<img src='https://raw.githubusercontent.com/HappyJeannie/pics/main/img/20210104121712.png' width=60%/>

- 1 中为 token 使用的描述，可以随意填写
- 2 中 repo 必选，其他可选
- 配置完成后，拉至最底部直接生成

<img src='https://raw.githubusercontent.com/HappyJeannie/pics/main/img/20210104122028.png' width=60%/>

## 2、PicGo 配置

PicGo [下载地址](https://github.com/Molunerfinn/PicGo/releases)，本次使用版本 `2.3.0-beta.4`，安装成功后，做如下配置：

<img src='https://raw.githubusercontent.com/HappyJeannie/pics/main/config/20210104122602.png' width=60%/>

- 由于本次只做 github 配置，其他图床配置全部关闭

<img src='https://raw.githubusercontent.com/HappyJeannie/pics/main/config/20210104122821.png' width=60%/>

- 仓库名为 {username}/{库名}
- 分支名为选定要上传的分支，github 默认为 main
- token 为第一步中在 github 中生成的 token
- 存储路径为图片存储目录，无则为根目录

以上配置完成后，可直接进行上传。
