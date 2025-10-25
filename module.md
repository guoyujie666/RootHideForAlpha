# 测试版须知
此版本为 _**测试版**_ ，**可能**隐藏效果不如老版本，如您**继续安装**则代表您不在意此问题。
如测试版出现**无法隐藏**现象，请自行寻找原因。~~绝对不是因为我在上学~~
# v3.7-Beta2 更新日志
- 更新 Tricky Store v1.4.0 by @5ec1cff
- 修复 安装时补全 Zygisk Next 缺失功能时总是失败_（但愿有用）_
- 更改 action.sh 中 “切换 Zygisk Next 黑/白名单” 运行后默认切换排除列表策略为 仅还原挂载
# v3.7-Beta 更新日志
- 更新 Zygisk Next v1.3.0-RC3 by @Dr-TSNG
- 移除 Shamiko 模块
- 自动补全 Zygisk Next 缺失的 prop 隐藏功能
- 更改 action.sh 中 “切换 Shamiko 黑/白名单” 为 “切换 Zygisk Next 黑/白名单”（运行后会将排除列表策略改为 强制，从老版本升级上来务必先切换为白名单）
- 在 action.sh 中添加 “切换 Zygisk Next 排除列表策略”，仅支持切换 强制/仅还原挂载
