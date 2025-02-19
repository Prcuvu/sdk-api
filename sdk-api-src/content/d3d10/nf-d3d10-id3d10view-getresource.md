---
UID: NF:d3d10.ID3D10View.GetResource
title: ID3D10View::GetResource (d3d10.h)
description: Get the resource that is accessed through this view.
old-location: direct3d10\id3d10view_getresource.htm
tech.root: direct3d10
ms.assetid: VS|directx_sdk|~\id3d10view_getresource.htm
ms.date: 12/05/2018
ms.keywords: GetResource, GetResource method [Direct3D 10], GetResource method [Direct3D 10],ID3D10View interface, ID3D10View interface [Direct3D 10],GetResource method, ID3D10View.GetResource, ID3D10View::GetResource, affb4f45-35eb-1680-9945-930b6caf601f, d3d10/ID3D10View::GetResource, direct3d10.id3d10view_getresource
f1_keywords:
- d3d10/ID3D10View.GetResource
dev_langs:
- c++
req.header: d3d10.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: D3D10.lib
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- D3D10.lib
- D3D10.dll
api_name:
- ID3D10View.GetResource
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# ID3D10View::GetResource


## -description


Get the resource that is accessed through this view.


## -parameters




### -param ppResource [out]

Type: <b><a href="https://docs.microsoft.com/windows/desktop/api/d3d10/nn-d3d10-id3d10resource">ID3D10Resource</a>**</b>

Address of a pointer to the resource that is accessed through this view. (See <a href="https://docs.microsoft.com/windows/desktop/api/d3d10/nn-d3d10-id3d10resource">ID3D10Resource</a>.)


## -returns



Returns nothing.




## -remarks



This function increments the reference count of the resource by one, so it is necessary to call Release on the returned pointer when the application is done with it. Destroying (or losing) the returned pointer before Release is called will result in a memory leak.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/d3d10/nn-d3d10-id3d10view">ID3D10View Interface</a>
 

 

