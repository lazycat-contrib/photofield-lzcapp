# photofield-lzcapp

喵喵社区商店的 PhotoField (https://github.com/SmilyOrg/photofield) 打包（非官方）。

- 镜像：ghcr.io/smilyorg/photofield:v0.25.0（mirror 模式，amd64）
- 单容器，端口 8080；照片目录只读挂载 /app/photos，状态在 /app/data
- 无账号体系 → 不加 public_path，保持平台入口鉴权
- 本包未做实机验证
