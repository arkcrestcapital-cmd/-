# 清玄 Qingxuan — v0.4.9

此仓库固定保存 **v0.4.9** 这一条基线，不包含 v0.4.10 或更晚版本，也不保留历史版本目录。

本版本对应三个交付包：

- Qingxuan_PC_v0.4.9_Portable.zip
- Qingxuan_H5_v0.4.9_PC_Test.zip
- Qingxuan_Source_v0.4.9_Slim.zip

## 版本校验

- PC: 53b0a8903a27c4cab7858cb85dc2e697180c2fc819e5b7d4cc7e4f0a60011ece
- H5: 3b25f36a270a0425116f9ec3b00f0e3256de884796aaf1f2b974c13c233895bf
- Source: def978ba040af2d4c70388c92140b2cabc10f2161273e571bec2e4aa34449ab0

## 结构

- src/：游戏核心逻辑与渲染
- desktop_launcher/：Windows PC 桌面启动器源码
- server.js：后续多人服务端基线
- assets/*.json：角色、动画、地形资源索引
- tests/：坐标与九霄雷渡测试
- build.py：构建脚本

> 当前通过 ChatGPT GitHub 连接器写入的是 v0.4.9 的代码与配置基线。大型 WebP 二进制美术资源不重复提交进 Git 历史；其精确版本由上面的 v0.4.9 交付包 SHA-256 锁定。