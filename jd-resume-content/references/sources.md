# 资料来源与采用边界

检索日期：2026-11-07。以下优先采用大学职业中心与招聘方发布的一手指导。它们支持本 skill 的工作方向；具体的优先级判断、交接格式和停止条件是本项目的设计，不代表这些机构制定了统一招聘标准。

## Skill 规范与编排

- [Agent Skills Specification](https://agentskills.io/specification) 规定目录、YAML 元数据和可选参考资料的格式。[Best practices for skill creators](https://agentskills.io/skill-creation/best-practices) 主张从真实任务与纠错提炼程序，控制入口长度，把条件性细节放到按需读取的参考资料，并用真实执行持续修订。本 skill 将共通决策写在入口，将岗位视角另置参考文件。
- [How to add skills support to your agent](https://agentskills.io/client-implementation/adding-skills-support) 说明技能按“元数据—正文—按需资源”逐层加载；这是客户端实现说明，不要求每个任务调用多个技能，也不要求启动子代理。本项目在经历库已经提供时直接进入定向写作；只有原始经历需要整理时才使用上游整理流程。
- [Evaluating skill output quality](https://agentskills.io/skill-creation/evaluating-skills) 建议用真实案例、预期结果及与旧版的对照评估。仅检查 skill 格式或给成稿一个主观总分，都不足以证明招聘表达有效。

## 候选人定位与首屏证据

- [Reactive Resume Content Guide](https://github.com/reactive-resume/reactive-resume/blob/main/plugins/reactive-resume/skills/resume-content-guide/SKILL.md) 提出的“先确定 2—3 个卖点，再看简历开头是否传达”用于本项目的候选人定位与逆读检查。它是社区技能的编辑方法，不是招聘方公布的筛选规则。
- [Build Tailored Resume](https://github.com/chasey-myagi/resume-agent-skill/blob/main/SKILL.md) 的先定主要优势、压低次要素材再写稿，启发本项目在写作前做取舍；不照搬其文件制作和冗长关卡。
- [Resume as Product Coach](https://github.com/BrennanJCollins/UnabatedPM-coaching/blob/main/unabatedpm-career-growth/skills/resume-as-product-coach/SKILL.md) 强调从任务清单中提炼判断和个人贡献。本项目只吸收这一通用问题意识，不把产品经理的叙事框架强加给技术或其他岗位。

## 从 JD 选材与排序

- [MIT CAPD：Resumes](https://capd.mit.edu/resources/resumes/) 建议用职位描述决定纳入哪些经历，选择体现所需技能的工作、实习、研究、领导力或个人项目；技能在经历中呈现更有上下文。本 skill 据此先做“要求—证据”对应，再选择模块和要点。
- [MIT CAPD：Crafting an effective resume](https://capd.mit.edu/resources/career-toolkit-crafting-an-effective-resume/) 建议观察 JD 的关键术语、反复出现的行动和靠前的职责，突出真正相关的经历。本 skill 把这些当优先级线索，但不机械地将排位或词频当唯一标准。
- [清华大学学生职业发展指导中心：简历工作坊](https://career.tsinghua.edu.cn/info/1051/3694.htm) 强调针对不同岗位的能力需要选择素材，突出少数核心亮点。本 skill 因此允许取舍，而不把完整经历库原样塞入简历。
- [宾夕法尼亚大学 Career Services：Write a Resume/CV](https://careerservices.upenn.edu/channels/resume/) 提醒用相关或可迁移技能选择工作、研究、志愿与领导经历，并可按目标调整分区。本 skill 不把实习以外的经历一概排除。
- [加州大学伯克利分校 Career Engagement：Resumes](https://www.career.berkeley.edu/prepare-for-success/resumes/) 建议将具体成就与雇主需求对应，相关技能、工作及项目经历都可以作为材料。本 skill 据此要求每个核心主张至少有可见证据。

## 写出可核实的匹配表达

- [MIT CAPD：Resumes: Writing about your skills](https://capd.mit.edu/resources/resumes-writing-about-your-skills/) 用项目、行动、结果帮助把技能写进具体经历，并建议反映 JD 的真实术语。本 skill 采用“动作、对象、方法、已知结果”的写作检查，不要求每条都有量化成功。
- [MIT CAPD：Career toolkit](https://capd.mit.edu/resources/career-toolkit-crafting-an-effective-resume/) 指出没有确切数字也可清楚交代角色与成果，针对研究等专业经历应让跨专业读者理解工作价值；本 skill 因此采用按岗位变化的证据视角，而不是单一数字模板。
- [微软 Careers：Technical interviewing](https://careers.microsoft.com/v2/global/en/hiring-tips/technical-interviewing.html) 会询问过去如何应用技能及工程生命周期。本 skill 对技术经历要求能解释实际实现与验证，而不把工具熟悉度等同于项目成果。
- [哈佛大学 MCS：Create an Impactful Resume](https://careerservices.fas.harvard.edu/resources/hes-create-impactful-resumes-and-cover-letters/) 建议按岗位与行业定制，语言具体、主动、基于事实且便于快速阅读；并指出并非所有经历都必须直接相关。本 skill 用它约束内容表达，不移植页数或版式规则。
- [微软 Careers：Interview Tips](https://careers.microsoft.com/v2/global/en/hiring-tips/interview-tips) 建议根据 JD 准备能解释情境、本人行动、结果和所学的具体例子。本 skill 用“能否回答后续追问”检查要点，不把面试答案模板搬进简历。

## AI 辅助与事实边界

- [MIT CAPD：Using AI for your resume and CV](https://capd.mit.edu/resources/using-ai-for-your-resume-and-cv/) 建议比较简历与 JD，找直接匹配、被低估的可迁移经历和缺口；只在意思不变时沿用 JD 语言，并警惕 AI 虚构或夸大经验。本 skill 因此要求逐条回溯经历库，未覆盖的要求须明示，不得补造资历。
- [MIT CAPD：Make your resume ATS-friendly](https://capd.mit.edu/resources/make-your-resume-ats-friendly/) 建议有意义地使用岗位术语。本 skill 仅采纳内容层面的“真实对应”，不追求关键词堆砌、臆测筛选算法或保证通过率。

## 不移植的建议

本 skill 暂不规定页数、字体、表格或 Word/PDF 格式；这些属于后续排版和投递场景。也不把某一家招聘方的系统规则当成所有企业的规则，不要求每项经历都有数字、成功结果或固定数量的要点。
