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
4. 管理员将你的个人 GitHub 账号加入 `volunteers` Team。

`volunteers` 是 APOA 的志愿者团队。这个 Team 已获得私有仓库 `internal-operations` 的 **Write** 权限。管理员只需在新人加入时设置一次，以后不需要为每次上传单独授权或建立目录。

- [查看 APOA volunteers Team](https://github.com/orgs/apoa-org/teams/volunteers)

如果无法进入 Team 或私有仓库，请确认你已经接受 Organization 邀请，并把自己的 GitHub 用户名发给 APOA 资料管理员。

## 从个人账号进入 APOA 私有仓库

登录自己的 GitHub 账号后，按以下路径进入：

1. 点击 GitHub 页面右上角的个人头像。
2. 点击 **Organizations**。
3. 选择 **apoa-org**。
4. 在组织首页点击 **Repositories**。
5. 找到带锁标志的 **internal-operations**，点击进入。

也可以使用直达地址：

- [进入 APOA 私有仓库 internal-operations](https://github.com/apoa-org/internal-operations)

如果看不到 `internal-operations`，通常表示你尚未加入 `volunteers` Team，或者还没有接受 `apoa-org` 邀请。

## 最简单的资料提交方式

所有新加入的协作者统一把待审核资料上传到私有仓库 `internal-operations` 中已经建立好的共享收件箱：

`inbox/incoming/`

不需要管理员为每位志愿者或每个月建立新目录，志愿者也不需要自己创建文件夹。

最快的方式是直接打开上传页面：

- [直接上传资料到 APOA 共享收件箱](https://github.com/apoa-org/internal-operations/upload/main/inbox/incoming)

操作步骤：

1. 点击上面的直达上传链接。
2. 把 PDF、Word、Excel、图片等文件拖入网页，或点击 **Choose your files** 选择文件。
3. 在提交说明中写一句中文，例如：`提交：7月董事会议记录`。
4. 点击 **Commit changes** 完成保存。

为避免多人上传时文件重名，建议将文件命名为：

`YYYY-MM-DD-姓名-文件说明.ext`

例如：`2026-07-30-王昆-中秋活动招商方案.pdf`

这里的 **Commit changes** 可以理解为“保存文件并留下版本记录”。

## 志愿者可以操作的范围

GitHub 的 **Write** 权限会覆盖整个 `internal-operations` 仓库，不能只开放其中一个文件夹。为了避免误改内部资料，志愿者只能：

- 向 `inbox/incoming/` 上传新文件；
- 填写本次上传的提交说明；
- 查看自己需要使用的资料。

未经资料管理员安排，请不要修改、移动或删除仓库中的现有文件，也不要在其他目录新建文件。

## 上传时不需要做什么

在共享收件箱中，你不需要：

- 学习 Git 命令或创建分支；
- 判断最终应该放在哪个目录；
- 判断文件是否可以公开。

资料管理员审核后，再统一改名、分类和发布。

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
