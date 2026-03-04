# De-AI Checklist

Run every draft through these 5 passes sequentially. Do not skip.

## Pass 1: Person (人称转换)

Replace third-person abstractions with first/second person.

| Before (AI smell) | After (human) |
|---|---|
| 人们普遍认为 | 我发现 / 你可能也觉得 |
| 研究表明 | 我注意到 / 我看到一个数据 |
| 许多创业者面临 | 我创业第一年 |
| 这一现象值得关注 | 这事儿让我睡不着觉 |

### 🔧 去结构化（新增）

**移除机械结构词**，改为自然过渡：

| Before (AI结构化) | After (人话) |
|---|---|
| 首先 | 说起来 |
| 其次 | 还有 |
| 最后 | 完了 |
| 综上所述 | 说到底 |
| 总的来说 | 其实吧 |

**规则**：一段话不要超过2个"然后/而且/同时"连着用

## Pass 2: Detail (具体化)

Every abstraction gets one concrete anchor.

| Before | After |
|---|---|
| 很多人有类似经历 | 我问了47个人，38个说了几乎一样的话 |
| 我学到了一个道理 | 那是2021年3月的周二，在星巴克里想明白的 |
| 效果很好 | 转化率从2.1%涨到7.8%，三周内 |
| 成本很高 | 一个月烧了$4,200，比我房租还贵 |

## Pass 3: Emotion (情感注入)

Mark 3 emotional beats in the draft. Rewrite them with raw honesty.

| Before (performed) | After (authentic) |
|---|---|
| 这令人深感忧虑 | 看到这数据我真的慌了——说实话，有点生气 |
| 这让人非常激动 | 我当时差点从椅子上跳起来 |
| 这是一个困难的决定 | 我删了又写，写了又删，最后凌晨三点才定下来 |

## Pass 4: Imperfection (不完美化)

Inject humanity. Add at least 2 of these:

- "我不确定这对每个人都适用，但..." 
- "说实话，我可能是错的"
- "（写到这里我犹豫了三分钟要不要发）"
- "这个观点可能会挨骂，但我还是想说"
- "后来证明我当时想多了/想少了"
- 承认运气的作用
- 承认自己不知道的部分

## Pass 5: Read-Aloud (朗读测试)

Read the entire piece out loud. Fix:
- Anything that sounds like a textbook → rewrite conversationally
- Sentences over 40 chars without a breath → split
- Transition words that feel mechanical → remove or replace with natural flow
- Any section where you get bored reading → cut or restructure

### 🔧 重构逻辑（新增）

**故意增加逻辑跳跃和转折**，模拟人类思考过程：

| Before (AI线性逻辑) | After (人话) |
|---|---|
| 价格合理，性价比高 | 价格还行，但上海打本确实比老家贵... |
| 服务好，体验不错 | 服务挺好的——不过我要说一句... |
| 效果显著 | 效果还行吧，反正我是踩了坑才搞明白 |

**技巧**：
- 每段加1-2个"不过"、"但是"、"说白了"
- 可以"突然想到"、"扯远了"、"回来继续说"
- 让结论来的意外一点，不是顺理成章

### 🔧 标点故障（新增）

**故意打破完美标点**，增加随意感：

| Before (AI标准) | After (人话) |
|---|---|
| 店内服务很好，工作人员热情。 | 店内服务很棒~ 工作人员都非常热情！从进门那一刻起... |
| 这是一个很好的选择。 | 这选择...还行吧（。|
| 效果非常好，值得推荐。 | 效果真的很好！值得推荐。。。 |

**技巧**：
- 适当用"～" "。。。" "！"
- 可以一个句子接一个句子不用任何连接词
- 断句可以很奇怪，比如"那天，我，记得，那是个周三"

## AI-Smell Word Blacklist

Replace these on sight:

| 🚫 AI Words | ✅ Human Alternatives |
|---|---|
| 值得注意的是 | 有意思的是 / 说句大实话 |
| 此外 | 还有个坑 / 对了 |
| 然而 | 但说实话 / 不过 |
| 因此 | 所以 / 说白了 |
| 至关重要 | 真的很重要 / 不搞定这个就完了 |
| 显著 | 明显 / 肉眼可见地 |
| 综上所述 | 说到底 / 总之一句话 |
| 不言而喻 | (直接删掉，让事实说话) |
| 深入探讨 | 聊聊 / 说说 |
| 不可否认 | 确实 |

### 🔧 高频词去重（新增）

**AI喜欢重复使用同样的强化词**，批量替换：

| 高频词 | 替换方案 |
|---|---|
| 非常 | 太 / 真的 / 超级 / 贼 / 巨 |
| 真的 | 实话 / 说实话 / 其实 / 讲真 |
| 非常感谢 | 谢了 / 感恩 / 谢谢各位 |
| 非常重要 | 要命 / 关键 / 核心 |

**技巧**：用Ctrl+F全局搜索替换，同一段落同一词不出现2次以上

## Final Sanity Check

After all 5 passes, verify:
- [ ] No paragraph is longer than 4 sentences
- [ ] At least 1 joke, self-deprecation, or aside per 500 words
- [ ] The opening line has zero AI-smell words
- [ ] There is at least one sentence that only YOU could have written (specific personal detail)
- [ ] Reading it cold, you'd believe a human wrote it

### 🔧 多举自己的例子（增强）

每个观点至少配1个**自己的真实例子**：

| 只有观点 | +自己的例子 |
|---|---|
| 做自媒体要坚持 | 我坚持了半年，每天写，现在终于有起色了 |
| AI写作需要调试 | 我那篇爆款改了7遍，第一版简直不能看 |
| 选城市很重要 | 我从北京逃到成都，工资降了但幸福感涨了 |

**技巧**：
- 用"上次"、"去年"、"我有个朋友"
- 越具体越好：日期、地点、人物、对话
- 甚至可以加"具体是谁就不说了"制造神秘感

### 🔧 去专业化：比喻 + 玩梗（新增）

**用通俗比喻解释专业概念**：

| Before (专业) | After (比喻) |
|---|---|
| 现金流断裂 | 钱烧没了，发不出工资 |
| 增长黑客 | 疯狂但有效的增长野路子 |
| 认知差 | 你知道但别人不知道的信息优势 |

**技巧**：
- 加1-2个当下热梗/网络用语（但别过度）
- 用生活中熟悉的事物类比
- 自嘲比直接夸更真实
