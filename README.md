# QQ音乐 skill

支持音乐搜索、每日推荐、猜你喜欢、排行榜、AI 歌单、听歌解读等功能。

## 配置

### 获取 API Key

1. 访问 <https://y.qq.com/n/ryqq_v2/qqmusic_skills> 获取 API Key。
2. 设置环境变量：`export QQMUSIC_API_KEY=<你的API Key>`，skill 会自动读取该环境变量进行鉴权，需要用户身份的接口会自动识别调用者。
3. 不要写进代码、不要提交到 git
4. 一旦泄露请立即到 https://y.qq.com/n/ryqq_v2/qqmusic_skills 删除或重置 API Key

## 使用示例

- "帮我搜一下周杰伦"
- "今天推荐什么歌"
- "看看最近什么歌最火"
- "今日听歌报告" / "本周听了多少"
- "分析我的听歌风格"
- "我是一个什么样的听众"

## 功能

| 能力    | 说明                  | 文档             |
|-------|---------------------|----------------|
| 搜索    | 搜索歌曲、专辑、歌单、MV、电台、歌手 | `discover.md`  |
| 每日推荐  | 每日 30 首个性化推荐        | `discover.md`  |
| 猜你喜欢  | 猜你喜欢电台              | `discover.md`  |
| AI 歌单 | AI 推荐歌单             | `discover.md`  |
| 排行榜   | 查看各类音乐排行榜           | `charts.md`    |
| 歌单详情  | 查看歌单歌曲列表            | `playlists.md` |
| 听歌报告  | 按日 / 周 / 月聚合的听歌统计   | `me.md`        |
| AI 解读 | 基于你的QQ音乐旅程进行解读      | `assistant.md` |
| 技能升级  | 检查 skill 是否有新版本，由用户决定是否升级 | `version.md`   |

## 版本

当前版本：**0.0.3**

## License

Apache-2.0
