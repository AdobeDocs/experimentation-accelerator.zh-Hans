---
solution: Journey Optimizer
product: journey optimizer
title: Journey Optimizer Experimentation Accelerator
description: 提升您高效开展试验并生成洞察的能力
topic: Content Management
role: User
level: Beginner
keywords: 内容、试验、多版本、受众、处理方式
source-git-commit: 4f30411591ab3bec4b749cfb58f437ddb3474ffa
workflow-type: tm+mt
source-wordcount: '507'
ht-degree: 18%

---

# 访问 Journey Optimizer Experimentation Accelerator

在[创建和配置实验](https://experienceleague.adobe.com/zh-hans/docs/journey-optimizer/using/content-management/content-experiment/content-experiment)并将营销活动或历程发送到配置文件后，您可以访问&#x200B;**[!UICONTROL Journey Optimizer Experimentation Accelerator]**&#x200B;以深入了解实验的执行情况。

您可以从[!UICONTROL 试验]下拉菜单的左侧菜单访问&#x200B;**[!UICONTROL Journey Optimizer Experimentation Accelerator]**，也可以通过应用程序切换器访问。 请注意，仅具有Target许可证的用户只能通过应用程序切换器访问它。

![](assets/access.png)

可用的试验取决于您的设置：

* **对于Adobe Journey Optimizer用户**：在您启用的组织的沙盒中设置的试验将自动包含在内。

* **对于具有Journey Optimizer的Adobe Target用户**： Target中的任何A/B活动都会显示在Journey Optimizer的生产沙盒的&#x200B;**[!UICONTROL Journey Optimizer Experimentation Accelerator]**&#x200B;中。

* **对于仅Adobe Target用户**：您的Target组织中的所有A/B活动都包含在Journey Optimizer的生产沙盒中。

要使用&#x200B;**[!UICONTROL Journey Optimizer Experimentation Accelerator]**，您需要访问沙盒和以下相关权限：

* **[!UICONTROL 查看试验]**
* **[!UICONTROL 管理试验元数据]**

+++ 了解如何使用Adobe Experience Platform或Adobe历程优化器许可证分配与试验相关的权限

1. 在&#x200B;**[!DNL Permissions]**&#x200B;产品中，转到&#x200B;**[!UICONTROL 角色]**&#x200B;选项卡并选择所需的&#x200B;**[!UICONTROL 角色]**。

1. 单击&#x200B;**[!UICONTROL 编辑]**，修改权限。

1. 添加&#x200B;**[!UICONTROL 试验加速器]**&#x200B;资源，然后从下拉菜单中选择&#x200B;**[!UICONTROL 查看试验]**&#x200B;和/或&#x200B;**[!UICONTROL 管理试验元数据]**。

   ![](assets/permissions-experiment.png)

1. 单击&#x200B;**[!UICONTROL 保存]**&#x200B;以应用更改。

任何已分配此角色的用户的权限都将自动更新。

要将此角色分配给新用户：

1. 导航到“角色”仪表板中的&#x200B;**[!UICONTROL 用户]**&#x200B;选项卡，然后单击&#x200B;**[!UICONTROL 添加用户]**。

1. 输入用户名、电子邮件地址或从列表中选择，然后单击&#x200B;**[!UICONTROL 保存]**。

   如果之前未创建用户，请参阅[此文档](https://experienceleague.adobe.com/zh-hans/docs/experience-platform/access-control/abac/permissions-ui/users)。

用户将收到一封电子邮件，其中包含访问实例的说明。

+++

</br>

+++ 了解如何使用Adobe Target许可证分配与试验相关的权限

1. 打开&#x200B;**[Admin Console](http://adminconsole.adobe.com/)**。

1. 在&#x200B;**[!UICONTROL 产品]**&#x200B;中，选择&#x200B;**[!UICONTROL Adobe Experience Platform]**。

1. 单击&#x200B;**[!UICONTROL 新建配置文件]**。

   ![](assets/permission-target.png)

1. 输入配置文件的&#x200B;**[!UICONTROL 名称]**&#x200B;和&#x200B;**[!UICONTROL 描述]**，然后单击&#x200B;**[!UICONTROL 保存]**。

1. 打开新创建的&#x200B;**[!UICONTROL 配置文件]**，然后导航到&#x200B;**[!UICONTROL 权限]**&#x200B;选项卡。

1. 单击&#x200B;**[!UICONTROL experimentation-accelerator]**&#x200B;权限旁边的![](assets/do-not-localize/Smock_Edit_18_N.svg)。

   ![](assets/permission-target-1.png)

1. 添加此配置文件应具有的权限，如&#x200B;**[!UICONTROL 查看试验]**&#x200B;和&#x200B;**[!UICONTROL 管理试验元数据]**，然后单击&#x200B;**[!UICONTROL 保存]**。

   >[!TIP]
   >
   > 当用户需要不同的访问级别时，创建单独的配置文件。 例如，创建一个仅包含&#x200B;**[!UICONTROL 查看试验]**&#x200B;的&#x200B;**[!UICONTROL Experimentation Accelerator Viewer]**&#x200B;配置文件，以及一个&#x200B;**[!UICONTROL Experimentation Accelerator Editor]**&#x200B;配置文件，其中同时包含&#x200B;**[!UICONTROL 查看试验]**&#x200B;和&#x200B;**[!UICONTROL 管理试验元数据]**。

   ![](assets/permission-target-2.png)

1. 从&#x200B;**[!UICONTROL 权限]**&#x200B;选项卡中，选择&#x200B;**[!UICONTROL 沙盒]**。

1. 添加用户应能够使用Journey Optimizer Experimentation Accelerator的沙盒，然后单击&#x200B;**[!UICONTROL 保存]**。

1. 打开&#x200B;**[!UICONTROL 用户]**&#x200B;选项卡，然后单击&#x200B;**[!UICONTROL 添加用户]**。

   ![](assets/permission-target-3.png)

1. 添加应接收此访问权限的用户，然后单击&#x200B;**[!UICONTROL 保存]**。

添加到此配置文件的用户现在可以从应用程序切换器访问Journey Optimizer Experimentation Accelerator。

+++


<!--table style="table-layout:fixed"><tr style="border: 0;">
<td><img alt="Overview" href="experiment-accelerator-overview.md" src="assets/do-not-localize/experiments-2.jpeg">
<div align="center"><p><strong><a href="experiment-accelerator-overview.md">Overview</a></strong></p></div></td>
<td><img alt="Experiments" href="experiment-accelerator-monitor.md" src="assets/do-not-localize/experiment-overview.jpeg">
<div align="center"><p><strong><a href="experiment-accelerator-monitor.md">Experiments</a></strong></p></div></td>
<td><img alt="Metrics" href="experiment-accelerator-metrics.md" src="assets/do-not-localize/experiment-metrics.png">
<div align="center"><p><strong><a href="experiment-accelerator-metrics.md">Metrics</a></strong></p></div></td>
</tr></table-->
