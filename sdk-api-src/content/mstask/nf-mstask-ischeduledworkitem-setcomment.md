---
UID: NF:mstask.IScheduledWorkItem.SetComment
title: IScheduledWorkItem::SetComment (mstask.h)
description: Sets the comment for the work item.
old-location: taskschd\ischeduledworkitem_setcomment.htm
tech.root: taskschd
ms.assetid: c6017aa1-8860-454c-a402-becbc1a4ee5c
ms.date: 12/05/2018
ms.keywords: IScheduledWorkItem interface [Task Scheduler],SetComment method, IScheduledWorkItem.SetComment, IScheduledWorkItem::SetComment, SetComment, SetComment method [Task Scheduler], SetComment method [Task Scheduler],IScheduledWorkItem interface, _msb_ischeduledworkitem_setcomment, mstask/IScheduledWorkItem::SetComment, taskschd.ischeduledworkitem_setcomment
f1_keywords:
- mstask/IScheduledWorkItem.SetComment
dev_langs:
- c++
req.header: mstask.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Mstask.lib
req.dll: Mstask.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Mstask.dll
api_name:
- IScheduledWorkItem.SetComment
targetos: Windows
req.typenames: 
req.redist: Internet Explorer 4.0 or later on Windows NT 4.0 and Windows 95
ms.custom: 19H1
---

# IScheduledWorkItem::SetComment


## -description


<p class="CCE_Message">[[This API may be altered or unavailable in subsequent versions of the operating system or product. Please use the <a href="https://docs.microsoft.com/windows/desktop/TaskSchd/task-scheduler-2-0-interfaces">Task Scheduler 2.0 Interfaces</a> instead.] ]

Sets the comment for the <a href="https://docs.microsoft.com/windows/desktop/TaskSchd/w">work item</a>.


## -parameters




### -param pwszComment [in]

A null-terminated string that specifies the comment for the current work item.


## -returns



The 
<b>SetComment</b> method returns one of the following values.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
The operation was successful.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_INVALIDARG</b></dt>
</dl>
</td>
<td width="60%">
The arguments are not valid.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_OUTOFMEMORY</b></dt>
</dl>
</td>
<td width="60%">
Not enough memory is available.

</td>
</tr>
</table>
 




## -remarks



After setting the comment of a work item, be sure to call <b>IPersistFile::Save</b> to save the modified work item object to disk.


#### Examples

For an example of how to set the comment of a task, see <a href="https://docs.microsoft.com/windows/desktop/TaskSchd/c-c-code-example-setting-task-comment">C/C++ Code Example: Setting Task Comment</a>.

<div class="code"></div>



## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/mstask/nn-mstask-ischeduledworkitem">IScheduledWorkItem</a>



<a href="https://docs.microsoft.com/windows/desktop/api/mstask/nf-mstask-ischeduledworkitem-getcomment">IScheduledWorkItem::GetComment</a>



<a href="https://docs.microsoft.com/windows/desktop/api/mstask/nn-mstask-itask">ITask</a>
 

 

