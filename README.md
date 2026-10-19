# 时简记 · Android 版本发布

这里**只发布公开的 APK 和版本清单**，不存放应用源码、个人记录、API Key、电脑配对凭证或签名私钥。

- [查看最新版本](https://github.com/bigwu2024/shijianji-releases/releases/latest)
- 升级前先在旧版导出 JSON 备份；选择与旧安装证书匹配的 Android Debug 或 TimeKeeper 签名 APK。
- 如果提示签名不一致，**不要卸载旧版或清除数据**；返回选另一证书包。
- 应用内只在打开时每天至多检查一次公开版本信息，显示提示后由用户手动下载、安装。普通 Android 应用不能静默覆盖安装。
- 如果所在网络无法访问 GitHub，请稍后重试或从已验证的本地交付目录获取对应安装包。

构建、测试、Lint、证书与哈希校验全部通过后，使用时间快记项目的 `tools/release-shijianji.ps1 -Version x.y.z` 自动发布新版本到此仓库；已有版本禁止覆盖。

联系邮箱：tech@yongai8.com。

