---
UID: NF:structuredquery.IConditionGenerator.Initialize
title: IConditionGenerator::Initialize (structuredquery.h)
description: Resets all states of the interface to default values and retrieves any necessary information from the schema.
old-location: search\_search_IConditionGenerator_Initialize.htm
tech.root: search
ms.assetid: VS|search|~\search\wds3x\reference\ifaces\querying\iconditiongenerator\initialize.htm
ms.date: 12/05/2018
ms.keywords: IConditionGenerator interface [search],Initialize method, IConditionGenerator.Initialize, IConditionGenerator::Initialize, Initialize, Initialize method [search], Initialize method [search],IConditionGenerator interface, _search_IConditionGenerator_Initialize, search._search_IConditionGenerator_Initialize, structuredquery/IConditionGenerator::Initialize
f1_keywords:
- structuredquery/IConditionGenerator.Initialize
dev_langs:
- c++
req.header: structuredquery.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP with SP2, Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2003 with SP1 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Structuredquery.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Structuredquery.h
api_name:
- IConditionGenerator.Initialize
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IConditionGenerator::Initialize


## -description


Resets all states of the interface to default values and retrieves any necessary information from the schema.
        


## -parameters




### -param pSchemaProvider [in]

Type: <b><a href="https://docs.microsoft.com/windows/desktop/api/structuredquery/nn-structuredquery-ischemaprovider">ISchemaProvider</a>*</b>

Pointer to the schema to be used.
            


## -returns



Type: <b>HRESULT</b>

If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/structuredquery/ne-structuredquery-condition_creation_options">CONDITION_CREATION_OPTIONS</a>



<a href="https://docs.microsoft.com/windows/win32/api/structuredquerycondition/ne-structuredquerycondition-condition_operation">CONDITION_OPERATION</a>



<a href="https://docs.microsoft.com/windows/win32/api/structuredquerycondition/ne-structuredquerycondition-condition_type">CONDITION_TYPE</a>



<a href="https://docs.microsoft.com/windows/desktop/api/structuredquerycondition/nn-structuredquerycondition-icondition">ICondition</a>



<a href="https://docs.microsoft.com/windows/desktop/api/structuredquerycondition/nn-structuredquerycondition-icondition2">ICondition2</a>



<a href="https://docs.microsoft.com/windows/desktop/api/structuredquery/nn-structuredquery-iconditionfactory">IConditionFactory</a>



<a href="https://docs.microsoft.com/windows/desktop/api/structuredquery/nn-structuredquery-iconditiongenerator">IConditionGenerator</a>



<b>Reference</b>
 

 

