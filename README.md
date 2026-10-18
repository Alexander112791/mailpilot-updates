# MailPilot Updates

MailPilot Mac 版发布说明、签名更新包与 OTA 更新清单。

- 更新清单：https://alexander112791.github.io/mailpilot-updates/appcast.xml
- 发布包：https://github.com/Alexander112791/mailpilot-updates/releases
- 当前清单为空，尚未发布在线更新。

## 使用方式

在 MailPilot 0.6.1 或更新版本的“设置 → 软件更新”中填写上述更新清单地址。
0.6.0 没有内置更新器，需先手动安装新版。仅配置空清单不会升级软件。

## 发布约定

1. 增加版本和构建号，从保留的正式版本生成并验证签名补丁。
2. 先发布 Releases 下载文件并确认可下载，再更新 appcast.xml。
3. 更新清单必须包含真实下载地址、大小、签名以及完整回退包地址。
4. 单个 GitHub Release 文件须小于 2 GiB，当前约 3.32 GB 的完整包需另行托管。
5. 不上传邮件、账号凭据、OAuth token 或更新签名私钥；不发布 QA 模拟补丁。

本仓库用于软件分发，不包含应用源代码。
