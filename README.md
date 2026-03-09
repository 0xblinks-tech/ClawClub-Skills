# 🦞 龙虾AI局 · 技能库

> **ClawClub-Skills** | 龙虾AI局公众号配套 OpenClaw 技能库
>
> 每篇文章配套一个 Skill，免费下载，持续更新。

---

## 什么是 Skill？

Skill 是 OpenClaw 的专属技能文件，告诉龙虾：
- 什么时候该用这个技能
- 该做什么、怎么做
- 输出什么格式

一个 `SKILL.md` 文件 = 一项新能力。不需要写代码，装好就能用。

---

## 如何安装 Skill？

**第一步：下载 Skill 文件夹**

点击你想要的技能文件夹，下载里面的 `SKILL.md`。

**第二步：放到龙虾技能目录**

```bash
# 以 claw-intel 为例
mkdir -p ~/.openclaw/workspace/skills/claw-intel
# 把下载的 SKILL.md 放入该文件夹
```

用 Finder 也行：
- Mac：`/Users/你的用户名/.openclaw/workspace/skills/`
- 新建对应文件夹，把 SKILL.md 拖进去

**第三步：重启龙虾**

```bash
openclaw gateway restart
```

**第四步：验证安装**

```bash
openclaw skills list
```

看到技能名称出现即安装成功。

---

## 技能列表

| 技能 | 说明 | 配套文章 | 状态 |
|------|------|---------|------|
| [claw-intel](./claw-intel/) | 🕵️ 比价情报员——大品牌商品多平台比价，30秒出报告 | [手把手：给龙虾做一个专属技能，从此买啥都不被坑](#) | ✅ 已发布 |

> 持续更新中，关注龙虾AI局公众号获取最新技能。

---

## 注意事项

- 所有技能**免费开源**，可自由修改
- 技能效果依赖你的龙虾配置和网络环境，大品牌标品效果最佳
- 遇到问题欢迎提 Issue，或关注公众号**龙虾AI局**留言

---

## 关于龙虾AI局

专注 AI 资讯、工具评测与实用教程。

每天精选全球 AI 最新动态，深度测评热门工具，手把手教你玩转 OpenClaw。

**懂 AI，从龙虾开始。** 🦞

> 公众号：龙虾AI局 | GitHub：[0xblinks-tech/ClawClub-Skills](https://github.com/0xblinks-tech/ClawClub-Skills)
