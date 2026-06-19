---
name: AI Tools Evaluator (AI工具评估器)
version: v1.0.0
tags: ai-tools, tool-comparison, software-evaluation, productivity-tools, ai-adoption
---

--- 
name: ai-tools-evaluator
description: AI工具评估器 - Evaluate and compare AI tools for specific use cases. Use when user asks about AI工具比较、AI产品评测、工具推荐、ChatGPT替代, or wants to find the best AI tool for their needs. Provides structured evaluation and recommendations.
--- 
# AI Tools Evaluator (AI工具评估器)

## Overview

This skill helps users evaluate, compare, and select AI tools for their specific needs. It provides structured evaluation criteria, compares popular AI tools across different dimensions, and recommends the best options based on use cases. Designed to help users make informed decisions about AI tool adoption.

## When to Use This Skill

- Choosing an AI tool for a specific task
- Comparing multiple AI tools
- Evaluating if a tool meets their needs
- Finding alternatives to current tools
- Understanding AI tool capabilities and limitations
- Making purchasing/subscription decisions

## What This Skill Evaluates

### 1. Core Capabilities
- Language understanding and generation
- Task performance (coding, writing, analysis, etc.)
- Multimodal abilities (vision, audio, etc.)
- Context window and memory
- Knowledge cutoff and freshness

### 2. Practical Factors
- Ease of use and learning curve
- Integration options (API, plugins, etc.)
- Pricing and cost structure
- Privacy and data handling
- Speed and latency

### 3. Use Case Fit
- Best suited tasks
- Strengths and weaknesses
- Competition comparison
- Alternative tools

## Evaluation Dimensions

| Dimension | Criteria | Weight (Adjustable) |
|-----------|----------|---------------------|
| **Performance** | Task accuracy, quality of output | High |
| **Ease of Use** | UI, learning curve, documentation | Medium |
| **Integration** | API, plugins, third-party support | Medium |
| **Cost** | Pricing model, value for money | High |
| **Privacy** | Data handling, security | High |
| **Speed** | Response time, rate limits | Medium |
| **Reliability** | Uptime, consistency | Medium |

## Supported Tool Categories

| Category | Examples |
|----------|----------|
| **LLMs** | GPT-4, Claude, Gemini, Llama, Mistral |
| **Coding AI** | GitHub Copilot, Cursor, Codeium |
| **Writing AI** | Jasper, Copy.ai, Writesonic |
| **Image AI** | Midjourney, DALL-E, Stable Diffusion |
| **Audio AI** | ElevenLabs, Murf, Descript |
| **Research AI** | Perplexity, Consensus, SciSpace |
| **All-in-One** | ChatGPT, Claude, Google Gemini |

## Evaluation Framework

### For LLM Selection

```
Consider:
1. Primary use case (coding, writing, analysis, conversation)
2. Required capabilities (reasoning, creativity, speed)
3. Budget constraints
4. Privacy requirements
5. Integration needs
```

### For Specialized Tasks

```
Consider:
1. Task-specific performance benchmarks
2. Domain-specific fine-tuning
3. Output quality for your use case
4. Learning resources available
```

## Workflow

1. **Use Case Definition** — Understand what the user needs to accomplish
2. **Requirement Gathering** — Identify must-have vs. nice-to-have features
3. **Tool Identification** — List relevant tools for the use case
4. **Dimension Evaluation** — Score each tool on evaluation dimensions
5. **Comparison** — Side-by-side comparison of top candidates
6. **Recommendation** — Recommend best fit with rationale

## Usage Examples

### Tool Selection
```
"帮我选一个写代码的AI工具"
"哪个AI聊天机器人最适合分析文档?"
"有什么好的AI写作工具推荐?"
```

### Comparison
```
"GPT-4和Claude哪个更好?"
"比较一下这几个AI工具"
"Cursor和GitHub Copilot有什么区别?"
```

### Evaluation
```
"这个AI工具适合我的需求吗?"
"帮我评估一下这个产品"
"这个工具的优缺点是什么?"
```

## Output Format

```yaml
## Evaluation Request: [Use Case/Tool(s)]

### Requirements Analysis
- **Primary Need**: [User's main requirement]
- **Must Have**: [Essential features]
- **Nice to Have**: [Optional features]
- **Constraints**: [Budget, privacy, etc.]

### Tools Considered
| Tool | Performance | Ease of Use | Cost | Privacy | Overall |
|------|-------------|-------------|------|---------|---------|
| Tool A | 8/10 | 9/10 | 7/10 | 8/10 | 8.0/10 |
| Tool B | 9/10 | 7/10 | 9/10 | 9/10 | 8.5/10 |

### Detailed Analysis

#### Tool A
- **Pros**: [Strengths]
- **Cons**: [Weaknesses]
- **Best For**: [Use cases]
- **Pricing**: [Cost structure]

#### Tool B
...

### Recommendation
**[Recommended Tool]**

**Rationale**:
1. [Reason 1]
2. [Reason 2]
3. [Reason 3]

### Alternatives
- [Option for different needs]
- [Option for budget constraints]
```

## Limitations

- Cannot provide real-time pricing or feature updates
- Performance varies based on specific prompts/tasks
- Subjective evaluation components exist
- May not cover all niche or new tools
- Cannot test actual usage in user's context
- Evaluations may become outdated


## Usage Scenarios

1. **User input:** "Compare ChatGPT Plus, Claude Pro, and Gemini Advanced for technical writing, code review, and meeting summaries."
→ **Expected output:** Use-case-weighted comparison matrix — coding (Claude strengths), long-form writing (ChatGPT strengths), meeting summaries (Gemini multi-modal strengths), with per-task accuracy benchmarks, cost-per-task analysis, and recommended stack.
2. **User input:** "Our marketing team of 12 wants an AI tool for content creation. Evaluate the top 5."
→ **Expected output:** Team-adoption evaluation — comparison of Jasper, Copy.ai, Writer, ChatGPT Team, Claude Team on content quality, brand-voice consistency, collaboration features, enterprise security, API extensibility, pricing at 12 seats, and pilot-program design.
3. **User input:** "Build an AI-tool evaluation framework our company can reuse for every new tool purchase."
→ **Expected output:** Reusable evaluation framework — needs-definition template, vendor-shortlisting criteria (security, pricing, integration, support), trial-period scoring rubric, stakeholder-feedback collection process, and build-vs-buy decision flowchart.



### Scenario 2: 这么多AI工具到底哪个好用
**User input:** "市面上AI工具太多了，ChatGPT、文心一言、通义千问、Kimi、豆包、智谱清言……我到底该用哪个？每个要干的事不一样。"
**Expected output:** 国产AI大模型选择指南——日常聊天/写作/创意：豆包（免费+速度快+生活化）、Kimi（长文档阅读超强）；代码/技术问题：通义千问（代码能力强、API便宜）、智谱清言（结构化好）；内容创作/写文章：文心一言（中文理解好但应答较慢）；翻译/英文内容：ChatGPT（但需要科学上网）、Kimi（免费版翻译也不错）。建议方案：日常用豆包+Kimi双开，写代码用通义千问，翻译用Kimi，每月花20元开一个豆包Pro就够用。关键：不要贪多，固定用1-2个主力。

## Acceptance Criteria

1. ✓ Clearly defines evaluation dimensions
2. ✓ Can evaluate tools across multiple categories
3. ✓ Provides structured comparison framework
4. ✓ Offers practical recommendations
5. ✓ Explains trade-offs between tools
6. ✓ Updates as new tools emerge
7. ✓ Helps users find best fit for their use case