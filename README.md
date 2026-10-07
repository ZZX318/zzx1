# test-repo

这是我的第一个 Git 仓库，用来验证本机的 Git 环境是否跑得通。

## 本机环境

- Git for Windows **2.55.0**，安装位置 `F:\zzx-mofa\git\Git`
- GitHub 账号：[@ZZX318](https://github.com/ZZX318)
- 克隆位置：`F:\zzx-mofa\git\zzx1`
- 认证方式：Git Credential Manager，首次推送时弹浏览器登录，之后凭据存在 Windows 凭据管理器
- 代理：GitHub 直连速度太慢，已给 git 配置 `http.proxy = http://127.0.0.1:10808`

## 日常用的几条命令

```bash
git status                 # 看当前有哪些改动
git add -A                 # 把所有改动放进暂存区
git commit -m "提交说明"     # 提交
git push                   # 推送到 GitHub
```

## 提交身份

```bash
git config --global user.name   # 查看提交用的名字
git config --global user.email  # 查看提交用的邮箱
```
