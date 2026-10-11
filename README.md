# 宋韵封面师 Song-Style Cover

一个 Agent Skill：为文章、博客、公众号、小红书、视频生成**宋代美学风格**的封面图。

三大铁律：**留白即主角，少即是精准，意境重于形。**

- 天青 × 鎏金低饱和配色
- 六大意象模板：水面涟漪、回音壁、山脊线条、笔触墨痕、建筑意象、器物留影
- 自动适配公众号、小红书、博客、视频、Instagram 等尺寸
- 先给 2–3 个封面方向，确认后出高质量 PNG，可一键衍生多尺寸

## 安装

把本仓库放进你所用客户端的 Skills 目录，例如：

```bash
git clone https://github.com/Joyzhang0923/song-style-cover.git ~/.codex/skills/song-style-cover
```

或者把下面这段话发给能读写文件的 AI Agent：

```text
请帮我安装这个 Agent Skill：https://github.com/Joyzhang0923/song-style-cover
安装完成后确认 song-style-cover 可以使用。
```

客户端需要支持 Agent Skills；要直接出图，还需要图像生成工具。没有图像工具时，它会输出完整提示词和尺寸方案。

## 用法示例

```text
用宋韵封面师，给我的公众号文章《慢下来的勇气》做封面，直接出图。
```

```text
主题：长期主义。给我 3 个封面方向，要小红书和公众号两个尺寸。
```

## 文件结构

```text
SKILL.md                 技能主文件
references/templates.md  六大意象模板详解
```

## License

MIT
