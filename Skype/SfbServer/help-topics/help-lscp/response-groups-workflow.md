---
title: "Response Groups Workflow"
ms.reviewer: 
ms.author: v-cichur
author: cichur
manager: serdars
ms.date: 11/17/2018
audience: ITPro
ms.topic: article
f1.keywords:
- CSH
ms.custom:
- ms.lync.lscp.RgsWorkFlowMain
ms.prod: skype-for-business-itpro
ms.localizationpriority: medium
ms.assetid: e4ee8abb-e1e5-413c-919d-cd3fb7193840
description: "Response groups consist of agent groups, queues, and workflows. Response Group workflows define the actions that are taken when the Response Group application receives a phone call."
---

# Response Groups Workflow

Response groups consist of agent groups, queues, and workflows. Response Group workflows define the actions that are taken when the Response Group application receives a phone call.

The **Response Groups** - **Workflow** page displays a list of all the Response Group workflows that are defined for your organization.

## Tasks you can perform

You can perform the following tasks from the **Response Groups** - **Workflow** page:

- Create or change a hunt group workflow

- Create or change an interactive workflow

## UI Reference

The following list describes the commands on the page.

- **Create or edit a workflow** Opens the Response Group Configuration Tool for creating or editing a workflow.

- **Refresh** Refreshes the list of workflows.

The following list describes the fields on the page.

- **Name** The unique name that is assigned to the workflow.

- **Service** The **ApplicationServer** service that hosts the workflow.

- **SIP address** The SIP address of the group that will answer calls to the workflow.

- **Telephone** The phone number that is called to reach this response group.

- **Language** The language that is used for speech recognition and text-to-speech.

- **IVR** Indicates whether the workflow is a hunt group or an interactive workflow.

- **Enabled** Indicates whether the workflow is activated to receive calls.

For details about Response Group features and capabilities, see [Plan for the Response Group application in Skype for Business Server 2015](../../plan-your-deployment/enterprise-voice-solution/response-group.md) in the Planning documentation. For details about working with Response Group workflows, see [Managing Response Group Workflows](/previous-versions/office/lync-server-2013/lync-server-2013-managing-response-group-workflows) in the Operations documentation.