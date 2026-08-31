# 使用前须知 / Before You Use

感谢使用 **Universal Copy Editor**。  
Thank you for using **Universal Copy Editor**.

这是一套用于内容审校、润色、逻辑检查、事实核查辅助与发布前质量控制（QC）的 Skill。为了避免误用，请在使用前阅读以下说明。  
This Skill is designed for proofreading, editing, logic review, fact-checking assistance, and pre-publication quality control (QC). Please read the following notes before use.

---

## 1. 它是编辑助手，不是最终责任人  
## 1. It is an editorial assistant, not the final authority

本 Skill 可以帮助发现：  
This Skill can help identify:

- 错别字、语病、标点问题  
  Typos, grammar issues, and punctuation errors
- 重复表达和结构问题  
  Repetition and structural problems
- 前后矛盾  
  Internal inconsistencies
- 逻辑跳跃  
  Logical gaps
- 数据与单位问题  
  Problems with numbers and units
- 宣传腔、模板化表达  
  Promotional or overly templated wording
- 需要进一步核查的事实  
  Claims that may require further verification
- 潜在发布风险  
  Potential publication risks

但最终的编辑、发布和内容责任仍由使用者承担。  
However, final editorial, publication, and content responsibility remains with the user.

对于新闻、法律、医疗、财经、政策、企业公告以及涉及个人或机构声誉的内容，建议发布前进行人工复核。  
For journalism, legal, medical, financial, policy, corporate, or reputation-sensitive content, human review is recommended before publication.

---

## 2. “事实核查”不等于绝对正确  
## 2. Fact-checking does not guarantee absolute correctness

Pro 版在具备联网或检索能力时，可以对重要事实进行外部核查。  
The Pro edition may verify important claims using external sources when browsing or retrieval tools are available.

但核查结果仍可能受到以下因素影响：  
Results may still be affected by:

- 信息源不完整  
  Incomplete source coverage
- 官方信息更新滞后  
  Delayed official updates
- 不同来源口径不同  
  Conflicting definitions or methodologies
- 地区、版本、时间点不同  
  Regional, version, or timing differences
- 原始资料无法访问  
  Unavailable primary sources
- 搜索结果本身存在错误  
  Errors in search results or secondary reporting

因此，Skill 会尽量区分：  
The Skill will try to distinguish between:

- 已外部验证 / Externally verified
- 需要核查 / Needs verification
- 来源冲突 / Source conflict
- 可能已过时 / Possibly outdated

请不要把自动核查结果视为法律、医疗、财经或出版意义上的最终认证。  
Do not treat automated verification as legal, medical, financial, or publication-grade certification.

---

## 3. 它不是 AI 文本检测器  
## 3. It is not an AI-authorship detector

“模板化表达风险”仅分析可观察到的写作特征，例如：  
“Templated-writing risk” only evaluates observable writing traits, such as:

- 套话过多  
  Excessive stock phrases
- 段落结构过于机械  
  Overly mechanical paragraph structure
- 反复使用固定转折  
  Repetitive transitions
- 空泛总结  
  Generic summaries
- 句式高度重复  
  Highly repetitive sentence patterns

它不能证明一篇文字是否由 AI 生成。  
It cannot prove whether a text was written by AI.

---

## 4. 多语言支持有边界  
## 4. Multilingual support has limits

本 Skill 可以处理中文、英文、日文、西班牙文、法文、德文、意大利文、葡萄牙文、韩文等多种语言，并默认使用原文语言进行审校。  
This Skill supports multiple languages, including Chinese, English, Japanese, Spanish, French, German, Italian, Portuguese, and Korean, and will normally review text in the source language.

但多语言支持并不意味着：  
However, multilingual support does not mean:

- 所有语言都等同于母语编辑水平  
  Native-editor-level quality in every language
- 所有地区方言和行业术语都能完全覆盖  
  Complete coverage of all regional variants and industry terminology
- 可以替代当地专业人士处理高风险内容  
  It can replace qualified local professionals for high-stakes content

对于正式发布、高风险或专业性很强的内容，建议进行母语人工复核。  
For high-stakes, specialist, or formal publication, a qualified native-language reviewer is recommended.

---

## 5. 不要上传不应公开的敏感信息  
## 5. Avoid uploading sensitive or confidential information

如果内容包含以下信息，请先确认使用环境是否适合，并尽量脱敏：  
If your content contains any of the following, confirm that your environment is appropriate and redact sensitive details where possible:

- 身份证件信息  
  Government identification information
- 银行账户或支付信息  
  Banking or payment details
- 密码、密钥、Token  
  Passwords, API keys, or tokens
- 未公开商业机密  
  Confidential business information
- 客户或员工隐私  
  Customer or employee personal data
- 医疗隐私  
  Medical or health information
- 保密合同或内部文件  
  Confidential contracts or internal documents

---

## 6. 不会为了“显得专业”而故意挑错  
## 6. It will not invent problems just to appear thorough

本 Skill 的目标是发现真实问题，而不是为了让报告看起来更专业而强行挑错。  
The goal is to identify real issues, not to manufacture problems just to make the review look more sophisticated.

如果文本没有明显问题，它应该直接告诉你可以使用，而不是硬凑修改建议。  
If the text is already in good shape, it should say so rather than forcing unnecessary edits.

---

## 7. 默认不会整篇重写  
## 7. Full rewrites are not the default

除非你明确要求：  
Unless you explicitly ask for:

- 直接改 / Direct revision
- 重写 / Rewrite
- 润色成最终版 / Polish into a final version
- 给我可发布版本 / Make it publication-ready

否则 Skill 会优先采用：  
The Skill will normally prioritize:

**指出问题 → 解释原因 → 给出建议**  
**Identify the issue → Explain why it matters → Suggest a fix**

这样可以最大程度保留原作者的表达风格。  
This helps preserve the author's original voice and intent.

---

## 8. 推荐使用方式  
## 8. Recommended prompts

### 日常检查 / Everyday review

> 帮我检查一下这篇稿子，不要重写，只告诉我问题。  
> Review this draft. Do not rewrite it; just point out the issues.

### 专业审稿 / Professional review

> 做一次 Deep QC，重点检查事实、数字、逻辑和发布风险。  
> Run a Deep QC review, focusing on facts, numbers, logic, and publication risk.

### 多语言 / Multilingual review

> Review this article in English and keep the original tone.

> この文章を日本語のまま校正してください。書き直しは最小限にしてください。

---

## 9. Free 与 Pro 的区别  
## 9. Free vs Pro

### Free

适合：  
Best for:

- 日常写作 / Everyday writing
- 错别字和语病 / Typos and grammar
- 可读性 / Readability
- 基础逻辑 / Basic logic
- 前后矛盾 / Internal consistency
- 轻度润色 / Light editing

### Pro

在 Free 基础上增加：  
Adds to the Free edition:

- Deep QC
- 外部事实核查 / External fact-checking
- 行业 Profile / Industry-specific profiles
- 多语言增强规则 / Enhanced multilingual review
- 100 分编辑评分 / 100-point editorial scoring
- 数字与计算专项审核 / Numeric and calculation review
- 发布准备度 / Publication-readiness assessment
- 发布与声誉风险检查 / Publication and reputation risk review
- Style Profile
- 高级 Rewrite + QC / Advanced rewrite + QC workflow

---

## 10. 免责声明  
## 10. Disclaimer

使用本 Skill 即表示你理解：  
By using this Skill, you acknowledge that:

**它是辅助编辑与质量控制工具，而不是法律、医疗、金融、出版或其他专业责任的替代者。**  
**It is an editorial and quality-control assistant, not a substitute for legal, medical, financial, publishing, or other professional judgment.**
