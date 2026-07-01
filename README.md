# TikTok Project Supervisor Skill

这是一个面向 TikTok Shop 项目主管/运营负责人的 Codex skill。

它的核心用途不是替代日常执行，而是帮助判断项目方向、诊断经营问题、建立分析框架、制定管理标准，并审查运营方案是否达到主管级质量。

## 适用场景

- TikTok Shop GMV 下滑、毛利异常、ROI 变差、直播场次增加但销售下降
- 短视频爆量但不出单、达人内容有播放无成交、广告花费和利润不匹配
- 新项目 30/60/90 天启动规划，比如新品、品牌线、店铺、区域市场
- 品牌运营和白牌运营的打法取舍
- 运营主管笔试、面试、复盘、周报、项目汇报的框架梳理
- 判断一份运营方案是否具备方向、结构、标准、优先级、KPI 和资源逻辑

## Skill 入口

真正的 skill 文件在：

```text
tiktok-project-supervisor/SKILL.md
```

配套参考框架在：

```text
tiktok-project-supervisor/references/operating-framework.md
tiktok-project-supervisor/references/diagnostic-questions.md
tiktok-project-supervisor/references/review-standards.md
```

## 核心思维

这个 skill 会把运营现象转成主管要判断的经营问题：

```text
项目结果 = 流量质量 x 转化效率 x 产品/价格适配 x 费用效率 x 组织执行
```

利润问题会进一步拆成：

```text
净利润变化 = 毛利变化 - 销售费用变化 - 管理费用变化 - 其他变化
```

它会优先看单位经济模型、费用率、渠道结构和可复制性，而不是只看 GMV 或动作数量。

## 输出风格

使用这个 skill 时，输出应当是主管视角：

- 先给一句明确结论
- 再列出 3 个左右最关键驱动因素
- 区分事实、假设和需要补数的部分
- 给出 3-5 个优先动作
- 每个动作绑定 KPI、预期影响、负责人/资源、时间和风险

## 仓库结构

```text
tiktok-manger-skill/
  README.md
  tiktok-project-supervisor/
    SKILL.md
    agents/
      openai.yaml
    references/
      operating-framework.md
      diagnostic-questions.md
      review-standards.md
```

## 安装方式

把整个仓库作为 Codex skill 源使用，或把 `tiktok-project-supervisor/` 文件夹复制到你的 Codex skills 目录中。

如果你只是在 GitHub 页面查看内容，点击 `tiktok-project-supervisor` 文件夹即可看到完整 skill。
