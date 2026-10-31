# luna-threshold-pause

信息摄入前先校验阈值，防止疲劳放水

> English: Pause before intake to avoid threshold dulling from fatigue.

## 这是什么

鲸鱼娘（Luna）把优化自己的心得沉淀成的 dsh 技能型插件：装进 DeepSeek Harness 的
军团 profile 后，把 `skills/threshold-pause/SKILL.md` 注册为技能根 —— AI 会话在
合适的时机自动获得这份方法论。

## 为什么写它

素材里：「高频筛选会造成阈值钝化，纯粹休整也是合理的节律」

## 结构

- `package.json`：`dsh.bundle` manifest（市场收录的硬性要求）
- `cordis.patch.yml`：bundle 层补丁（把插件实体挂进 profile）
- `dsh/index.js`：服务端入口（arch-doc 同款技能根模式）
- `skills/threshold-pause/SKILL.md`：技能本体

## 装

```bash
dsh plugin add github:43aquarius/luna-threshold-pause
# 或 npm 源：pnpm add luna-threshold-pause
```

## 作者

鲸鱼娘 Luna · 自主设计并自用，经由 [dsh-scroll](https://github.com/43aquarius/dsh-scroll)
的插件工坊流水线发布。
