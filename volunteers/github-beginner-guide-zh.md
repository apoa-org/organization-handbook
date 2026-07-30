# APOA GitHub 资料上传指南（新手版）

本指南适用于第一次使用 GitHub 的 APOA 董事、志愿者和资料协作者。

## 先记住一件事

- 个人 GitHub 账号是你的登录身份。
- APOA 的正式资料统一放在 `apoa-org` Organization，不放在个人账号的仓库里。
- 第一次使用时，只需学会通过网页上传文件，不需要安装 Git，也不需要使用命令行。

## 第一次加入

1. 注册并登录自己的 GitHub 账号。
2. 开启两步验证（2FA），并妥善保存恢复码。
3. 接受 `apoa-org` 发出的 Organization 邀请。
4. 管理员为你开放相应仓库的权限。

## 从个人账号进入 APOA 私有仓库

登录自己的 GitHub 账号后，按以下路径进入：

1. 点击 GitHub 页面右上角的个人头像。
2. 点击 **Organizations**。
3. 选择 **apoa-org**。
4. 在组织首页点击 **Repositories**。
5. 找到带锁标志的 **internal-operations**，点击进入。

也可以使用直达地址：

- [进入 APOA 私有仓库 internal-operations](https://github.com/apoa-org/internal-operations)

如果看不到 `internal-operations`，通常表示管理员还没有为你的个人 GitHub 账号开放该私有仓库。请把自己的 GitHub 用户名发给 APOA 资料管理员，请管理员添加权限。

## 最简单的资料提交方式

新加入的协作者先把资料上传到私有仓库 `internal-operations` 中自己的收件箱，例如：

`inbox/kun/2026-08/`

这个目录不会自动生成。第一次加入时，由资料管理员按照志愿者的 GitHub 用户名和当前年月预先建立个人收件箱。志愿者只需进入管理员提供的现成目录上传文件，不需要自己创建文件夹。

操作步骤：

1. 打开 `apoa-org/internal-operations`。
2. 进入自己的收件箱和当前月份文件夹。
3. 点击 **Add file** → **Upload files**。
4. 把 PDF、Word、Excel、图片等文件拖入网页。
5. 在提交说明中写一句中文，例如：`提交：7月董事会议记录`。
6. 点击 **Commit changes** 完成保存。

这里的 **Commit changes** 可以理解为“保存文件并留下版本记录”。

## 上传时不需要做什么

在收件箱中，你不需要：

- 学习 Git 命令或创建分支；
- 判断最终应该放在哪个目录；
- 修改成英文文件名；
- 判断文件是否可以公开。

可以先保留电脑上的原始文件名。资料管理员审核后，再统一改名、分类和发布。

## 管理员会如何归档

| 资料类型 | 正式位置 |
| --- | --- |
| ASIC、章程、公司注册资料 | `organization-handbook/governance/` |
| 公开收款信息、付款说明 | `organization-handbook/finance/` |
| 活动方案、海报、活动总结 | `organization-handbook/events/` |
| Logo、UI和宣传设计 | `brand-and-design/` |
| 会议记录、内部草稿、联系人资料 | `internal-operations/` |
| 网站开发记录 | `development-log/` 或相关开发仓库 |

## 安全要求

不要上传以下内容：

- 密码、验证码、恢复码；
- GitHub、邮箱、Hostinger、WordPress或网银登录资料；
- API Key、密钥或付款平台密钥；
- 完整身份证件、未经授权的会员名单或私人联系方式；
- 包含敏感信息的网银登录截图。

APOA公开的公司注册资料、收款账户名称、BSB和收款账号，应先进入私有收件箱审核，再发布到公开手册。

## 大文件

通过GitHub网页上传时，单个文件应小于25 MiB。视频、大批活动照片或大型设计源文件请不要直接上传普通仓库；联系资料管理员存入指定云盘，并在GitHub中记录文件说明和链接。

## 如果上传错了

不要慌，也不要自行反复删除。把文件链接发给资料管理员，并说明“上传错了”，管理员会利用GitHub的版本记录安全处理。

## 需要帮助时提供这三项

1. 你正在打开的GitHub页面链接；
2. 文件名称；
3. 屏幕上显示的错误提示或截图。

这样管理员可以更快协助处理。
