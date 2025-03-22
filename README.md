# Shadowsocks-Rust 安装管理脚本
> 自用

## 使用

```bash
wget -O ss-rust.sh --no-check-certificate https://raw.githubusercontent.com/xqd922/Shadowsocks/master/Shadowsocks-Rust.sh && chmod +x ss-rust.sh && ./ss-rust.sh
```

或者

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/xqd922/Shadowsocks/master/Shadowsocks-Rust.sh)
```

## 功能特性

- 一键安装/更新/卸载
- 支持多种加密方式
  - aes-128-gcm
  - aes-256-gcm
  - chacha20-ietf-poly1305
  - 2022-blake3 系列加密
- TCP Fast Open 支持
- 自动配置系统参数
- 开机自启
- 流量统计功能
- v2ray-plugin 插件支持

## 使用说明

1. 运行脚本后选择 `1` 进行安装
2. 按照提示设置端口、密码和加密方式
3. 安装完成后可以通过菜单进行：
   - 启动/停止/重启服务
   - 修改配置
   - 查看流量统计
   - 更新/卸载

## 注意事项

1. 需要 root 权限运行
2. 支持 CentOS/Debian/Ubuntu 系统
3. 建议使用 AEAD 加密方式
4. 请定期备份配置文件
