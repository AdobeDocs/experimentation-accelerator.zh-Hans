---
solution: Journey Optimizer
product: journey optimizer
title: Journey Optimizer Experimentation Accelerator
description: 使用Journey Optimizer Experimentation Accelerator的AI中的数据使用
topic: Content Management
role: User
level: Beginner
keywords: 内容、试验、多版本、受众、处理方式
TQID: https://experienceleague.adobe.com/FaQ5-cPzhnIplEoL1HwVh390jot-EA8G5u6JP8CVneI
product_v2: id: cb954087-f4fc-4456-afb9-e939cabcdc79
feature_v2: id: b3538224-471e-4c63-a444-9b19d89ae29cid: b49ca41f-eb7a-4f4b-abeb-a97c06fd0c04id: dc22c819-3f29-4e91-8b7d-5c6719831141
subfeature_v2: id: fb9a80eb-bebc-492f-a0e9-584595621ebb
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2: id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
topic_v2: id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dcid: b5ce8718-c3af-4fdb-a1a9-fca32f83a87cid: bcc5edb5-84c3-4940-9f84-ed88b6c16274id: d095671a-1355-40aa-8b5f-06c33c68080bid: e1e0219c-f879-479f-8427-888ed2a6e9c2id: eb30f47f-d87a-400f-8f78-63ce7979ff56
source-git-commit: 659a4723ac8b7cbaf3ea06c34107bf876612ccb4
workflow-type: tm+mt
source-wordcount: 441
ht-degree: 2%

---

# 使用Journey Optimizer Experimentation Accelerator的AI中的数据使用{#experiment-accelerator-security}

**Adobe Journey Optimizer Journey Optimizer Experimentation Accelerator**&#x200B;允许您自动发现见解并推荐改进您的实验和实验计划的机会。 该解决方案利用AI和机器学习来提供这些推荐。 此语句说明如何在&#x200B;**Journey Optimizer Experimentation Accelerator**&#x200B;中使用客户数据。

## Journey Optimizer Experimentation Accelerator使用哪些数据？

当前&#x200B;**Journey Optimizer Experimentation Accelerator**&#x200B;使用了三种类型的数据：

* **试验元数据**：试验名称、试验中使用的受众定义以及试验中的处理，例如名称、拆分百分比、提供试验的位置或表面。

* **处理性能**：人数、成功量度的平均值和每个处理的标准偏差。

* **治疗的内容**：呈现的HTML和治疗屏幕截图，显示在您网站上的用户眼中。

## Journey Optimizer Experimentation Accelerator会如何处理这些数据？

**Journey Optimizer Experimentation Accelerator**&#x200B;获取每次处理的内容并创建嵌入，即内容的数学表示形式，然后将这些嵌入与处理的性能相关联。 此过程允许提取表现最佳以供将来使用的内容属性。 随后，这些属性会被馈送到托管大型语言模型的Adobe，该模型会将它们转换为人类可读的语句，用于生成见解并提出机会建议。

## Journey Optimizer Experimentation Accelerator对使用的数据有什么限制？

每个客户都被分配到特定的组织和沙盒。 为每个沙盒培训专用模型。 删除沙盒时，将永久删除所有相关数据、信号和模型。

* 我们仅使用客户数据来培训或优化该客户的模型。

* 我们从不混合客户来培训或优化模型。

## Adobe模型或AI是否会自动更改品牌的用户体验？

不是。 **Journey Optimizer Experimentation Accelerator**&#x200B;只推荐可以更改的内容以及更改方式。 只有有权使用Journey Optimizer或Target更改体验的用户才能按照这些建议执行操作。 在推出之前，可以审核并编辑所有推荐。

## 他们的数据或系统稳定性是否存在任何风险？

**Journey Optimizer Experimentation Accelerator**&#x200B;仅摄取和分析数据，产生见解和建议以供将来测试。 它无权修改任何测试设置。 在该工具中生成的所有建议都将发送到Target和Journey Optimizer以供实施，从而确保不会影响客户的当前活动。
