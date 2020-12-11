<<<<<<< HEAD:wdk-ddi-src/content/nblapi/nf-nblapi-ndisgetpoolfromnetbufferlist.md
---
UID: NF:nblapi.NdisGetPoolFromNetBufferList
title: NdisGetPoolFromNetBufferList
ms.date: 11/30/2020
ms.topic: language-reference
targetos: Windows
description: Call the NdisGetPoolFromNetBufferList function to get the NET_BUFFER_LIST structure pool handle that is associated with a specified NET_BUFFER_LIST structure.
tech.root: netvista
req.assembly: 
req.construct-type: function
req.ddi-compliance: Irql_NetBuffer_Function
req.dll: 
req.header: ndis/nblapi.h
req.idl: 
req.include-header: ndis.h
req.irql: <= DISPATCH_LEVEL
req.kmdf-ver: 
req.lib: Ndis.lib
req.max-support: 
req.namespace: 
req.redist: 
req.target-min-winverclnt: Supported in NDIS 6.0 and later.
req.target-min-winversvr: 
req.target-type: Universal
req.type-library: 
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - LibDef
api_location:
 - nblapi.h
api_name:
 - NdisGetPoolFromNetBufferList
f1_keywords:
 - NdisGetPoolFromNetBufferList
 - nblapi/NdisGetPoolFromNetBufferList
dev_langs:
 - c++
---

# NdisGetPoolFromNetBufferList function


## -description

Call the 
  <b>NdisGetPoolFromNetBufferList</b> function to get the 
  <a href="/windows-hardware/drivers/ddi/nbl/ns-nbl-net_buffer_list">NET_BUFFER_LIST</a> structure pool handle that is
  associated with a specified NET_BUFFER_LIST structure.

## -parameters

### -param NetBufferList 

[in]
A pointer to a previously allocated 
     <a href="/windows-hardware/drivers/ddi/nbl/ns-nbl-net_buffer_list">NET_BUFFER_LIST</a> structure.

## -returns

<b>NdisGetPoolFromNetBufferList</b> returns a handle to the NET_BUFFER_LIST structure pool that is
     associated with the specified NET_BUFFER_LIST structure.

## -remarks

The handle that 
    <b>NdisGetPoolFromNetBufferList</b> returns is a required parameter in calls to NDIS functions that
    manipulate the 
    <a href="/windows-hardware/drivers/ddi/nbl/ns-nbl-net_buffer_list">NET_BUFFER_LIST</a> structures that are from the
    associated NET_BUFFER_LIST structure pool.

## -see-also

<a href="/windows-hardware/drivers/ddi/nbl/ns-nbl-net_buffer_list">NET_BUFFER_LIST</a>
=======
---
UID: NF:ndis.NdisGetPoolFromNetBufferList
title: NdisGetPoolFromNetBufferList function (ndis.h)
description: Call the NdisGetPoolFromNetBufferList function to get the NET_BUFFER_LIST structure pool handle that is associated with a specified NET_BUFFER_LIST structure.
old-location: netvista\ndisgetpoolfromnetbufferlist.htm
tech.root: netvista
ms.date: 05/02/2018
keywords: ["NdisGetPoolFromNetBufferList function"]
ms.keywords: NdisGetPoolFromNetBufferList, NdisGetPoolFromNetBufferList function [Network Drivers Starting with Windows Vista], ndis/NdisGetPoolFromNetBufferList, ndis_netbuf_functions_ref_c93c9420-04fb-42f7-9844-29c3b2052b82.xml, netvista.ndisgetpoolfromnetbufferlist
req.header: ndis.h
req.include-header: Ndis.h
req.target-type: Universal
req.target-min-winverclnt: Supported in NDIS 6.0 and later.
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: Irql_NetBuffer_Function
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Ndis.lib
req.dll: 
req.irql: <= DISPATCH_LEVEL
targetos: Windows
req.typenames: 
f1_keywords:
 - NdisGetPoolFromNetBufferList
 - ndis/NdisGetPoolFromNetBufferList
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - LibDef
api_location:
 - ndis.lib
 - ndis.dll
api_name:
 - NdisGetPoolFromNetBufferList
---

# NdisGetPoolFromNetBufferList function


## -description

Call the 
  <b>NdisGetPoolFromNetBufferList</b> function to get the 
  <a href="/windows-hardware/drivers/ddi/ndis/ns-ndis-_net_buffer_list">NET_BUFFER_LIST</a> structure pool handle that is
  associated with a specified NET_BUFFER_LIST structure.

## -parameters

### -param NetBufferList 

[in]
A pointer to a previously allocated 
     <a href="/windows-hardware/drivers/ddi/ndis/ns-ndis-_net_buffer_list">NET_BUFFER_LIST</a> structure.

## -returns

<b>NdisGetPoolFromNetBufferList</b> returns a handle to the NET_BUFFER_LIST structure pool that is
     associated with the specified NET_BUFFER_LIST structure.

## -remarks

The handle that 
    <b>NdisGetPoolFromNetBufferList</b> returns is a required parameter in calls to NDIS functions that
    manipulate the 
    <a href="/windows-hardware/drivers/ddi/ndis/ns-ndis-_net_buffer_list">NET_BUFFER_LIST</a> structures that are from the
    associated NET_BUFFER_LIST structure pool.

## -see-also

<a href="/windows-hardware/drivers/ddi/ndis/ns-ndis-_net_buffer_list">NET_BUFFER_LIST</a>
>>>>>>> release-iron:wdk-ddi-src/content/ndis/nf-ndis-ndisgetpoolfromnetbufferlist.md