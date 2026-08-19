# my-aivid-prompt

把已经确认的视频策略、脚本、分镜，或 `my-vidwatch` 的 `report.md` + contact sheets，转换成低风险、重视参考图一致性的 AI 视频镜头清单与生成提示词。使用 `my-vidwatch` 输入时不要求用户另写分镜：先推导镜头清单并确认，再写逐镜 Prompt。

默认优先适配：可灵 3.0。

## 与 my-vidwatch 的关系

`my-aivid-prompt` 最初作为 `my-vidwatch` 的下游提示词生成阶段设计：读取其 `report.md` 与 contact sheets，把视频分析结果转换成经用户确认的镜头方案与可执行 AI 视频 Prompt。它不是 `my-vidwatch` 的 fork；两者是上下游 workflow。没有 `my-vidwatch` 时，也可以直接使用已确认的脚本、广告结构、分镜或镜头清单作为输入。

- 主文件：`SKILL.md`
- 测试场景：`TEST_CASES.md`
