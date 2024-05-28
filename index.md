---
layout: default
title: Home
seo:
  type: Course
  name: {{ site.title }}
nav_order: 1
---

# {{ site.tagline }}

<!--{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}-->

大规模语言模型

自然语言处理（NLP）领域已经被大规模预训练语言模型彻底改变了。它们构成了各种任务中最先进的系统的基础，并显示出生成流畅文本和进行少量学习的强大能力。同时，这些模型难以理解，并引发新的伦理和可扩展性挑战。在本课程中，学生们将学习有关大型语言模型的建模、理论、伦理和系统方面的基础知识，并获得与它们一起工作的实践经验。

## 团队

{% assign instructors = site.staffers | sort: 'index' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## 安排

**地点**：默认情况下，课程将在[200-002](https://goo.gl/maps/8ADRSg7nJ9xZC2Zd7)（历史角）进行面对面授课。前两周将远程授课（根据大学政策）；[Zoom信息](https://canvas.stanford.edu/courses/149841/external_tools/5384)发布在Canvas上。

**时间**：课程时间为周一和周三下午3:15至4:45（太平洋标准时间）。

**链接**：
- [Ed](https://canvas.stanford.edu/courses/149841/external_tools/24287?display=borderless)：这是你和教学团队沟通的主要方式：我们将在这里发布所有重要公告，你应该在这里提出所有与课程相关的问题。对于你不希望在私人Ed帖子中公开的个人事务，你可以发送电子邮件至教学团队[cs324-win2122-staff@lists.stanford.edu](mailto:cs324-win2122-staff@lists.stanford.edu)。
- [Canvas](https://canvas.stanford.edu/courses/149841)：课程Canvas页面包含只有学生才能访问的链接和资源（远程课程的[Zoom链接](https://canvas.stanford.edu/courses/149841/external_tools/5384)）。
- [Gradescope](https://www.gradescope.com/courses/342794)：我们使用Gradescope来管理课程作业（提交作业，返回成绩）。请使用你的@stanford.edu邮箱注册Gradescope账户。

**视频访问声明**：部分课堂活动将在Zoom中进行并录制。为了方便，你可以通过登录课程Canvas网站来访问这些录像。这些录像可能会在其他斯坦福课程中重复使用，被其他斯坦福学生、教师或工作人员观看，或用于其他教育和研究目的。如果你有疑问，请通过[cs324-win2122-staff@lists.stanford.edu](mailto:cs324-win2122-staff@lists.stanford.edu)联系教学团队成员。

## 课程

每节课分为两部分：

1. **讲座**（45分钟）：讲师就一个主题进行标准讲座（见[日历](/calendar)上的课题列表）。讲座将基于[这些讲义](/lectures)。

2. **讨论**（45分钟）：学生小组讨论在[日历](/calendar)上发布的必读材料。

## 作业

你的成绩基于两项活动：

1. 论文评论和讨论（20%）
2. 项目（2 x 40% = 80%）

### 1. 论文评论和讨论

[**论文评论**](paper-reviews)。在每节课之前，你会被分配1-2篇论文。你应该仔细阅读这些论文并撰写评论。
你的评论应该是几段话（以会议评论的风格，比如ACL或NeurIPS）。

论文评论的截止时间是讲座当天的**上午11:00（太平洋标准时间）在[Gradescope](https://www.gradescope.com/courses/342794)**上。

[**论文讨论**](paper-discussions)。在每节课的讨论中，有一个4-5名学生的小组（你应该至少报名参加两个小组）。学生小组成员在讲师的主持下引导讨论。其他人应该通过向小组提问来参与。

### 2. 项目

有两个[项目](projects)，让你能够亲身体验大型语言模型。

- [**项目1**](projects/project1)是关于**评估**语言模型。你将获得访问GPT-3等模型的权限，并被要求批判性地思考它们的能力与风险。你需要确定一个你想要更深入探索的**焦点属性**。

- [**项目2**](projects/project2)是关于**构建**语言模型。你将获得一定的计算预算，允许你训练像BERT-base这样的模型，以更系统地评估、理解和改进你在项目1中确定的焦点属性的语言模型。

项目应该由**1-2名学生组成的小组**完成。
每个项目都应该清晰简洁地撰写；如果你的写作不清晰或不必要地复杂，你可能会丢失分数。项目必须使用LaTeX、Microsoft Word、Mac的Pages或等效程序排版，并以PDF形式提交。我们强烈鼓励你使用LaTeX：有像[Overleaf](https://www.overleaf.com/)这样的用户友好的网络界面。

项目截止时间是截止日期的**晚上11:00（不是11:59）太平洋标准时间在[Gradescope](https://www.gradescope.com/courses/342794)**上。

### 提交课程作业

**提交**：所有课程作业都通过[Gradescope](https://www.gradescope.com/courses/342794)在截止日期前提交。
不要通过电子邮件提交你的课程作业。如果有任何问题，请在Ed上提问或联系课程助理。如果你需要注册Gradescope账户，请使用你的@stanford.edu邮箱。你可以在截止日期前提交任意次数：我们只会评阅最后一次提交。提交部分工作总比不提交任何工作要好。如果你在小组中完成作业，请确保**所有小组成员都在Gradescope上作为提交的一部分被选中。**

**逾期天数**：如果作业在截止日期后d天提交，则认为作业晚了⌈d⌉天（请注意，这意味着如果你晚1秒钟，⌈d⌉=1，它就晚了1天）。**你总共有3天的逾期天数，可以无罚分地分配到作业中。** 之后，每天最高可能的分数会减少25%（所以如果你d=1，最好的成绩是75%；如果你没有逾期天数，论文评论如果晚交将被视为不及格）。例如，如果你没有逾期天数并且晚交一天，90分将被限制在75分，但72分不会改变。**请注意，我们每个作业只允许最多d=2天的逾期天数。**

**重新评分**：如果你认为课程工作人员在评分中犯了客观错误，你可以提交重新评分的请求。**重新评分的请求只有在初始成绩发布后一周内通过Gradescope才会被接受。**
请注意，我们可能会重新评分你的整个提交，所以根据你的提交，你实际上可能会失去比获得更多的分数。
