# Slide Story Architect：先把故事讲通，再打开 PowerPoint

大多数演示文稿的问题不是“不够好看”，而是每页都在放资料，却没有一条能让观众跟下去的逻辑线。

`slide-story-architect` 是一个面向汇报、路演、课程和提案的开源 Agent Skill。它先建立观众决策和叙事骨架，再为每一页定义唯一工作、证据和适合的视觉形式。

## 使用示例

```text
用 $slide-story-architect 把这份调研材料整理成 12 页管理层汇报。
观众要决定是否投入下一阶段预算，每页只承担一个任务。
```

## 你会得到

- 一句话演示目标
- 开场、张力、证据、方案和行动的叙事线
- 每页标题、核心结论、证据和视觉建议
- 可删除内容和附录建议
- 讲者备注中的过渡句

## 安装

```bash
cp -R skills/slide-story-architect ~/.codex/skills/
```

## 方法参考

本项目独立实现。AI 演示文稿工作流的问题域参考了 [hugohe3/ppt-master](https://github.com/hugohe3/ppt-master)，该项目采用 MIT License。本项目不包含其 PPTX 生成代码、模板、图标、形状数据、导出流程或原文说明。

## License

MIT License。
