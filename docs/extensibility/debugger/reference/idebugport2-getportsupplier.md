---
title: "IDebugPort2::GetPortSupplier | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "IDebugPort2::GetPortSupplier"
helpviewer_keywords: 
  - "IDebugPort2::GetPortSupplier"
ms.assetid: 7a7b0615-df6b-4726-ab35-39dfa1ebed8f
caps.latest.revision: 10
author: "gregvanl"
ms.author: "gregvanl"
manager: ghogen
ms.workload: 
  - "vssdk"
---
# IDebugPort2::GetPortSupplier
Gets the port supplier for this port.  
  
## Syntax  
  
```cpp  
HRESULT GetPortSupplier(   
   IDebugPortSupplier2** ppSupplier  
);  
```  
  
```csharp  
int GetPortSupplier(   
   out IDebugPortSupplier2 ppSupplier  
);  
```  
  
#### Parameters  
 `ppSupplier`  
 [out] Returns an [IDebugPortSupplier2](../../../extensibility/debugger/reference/idebugportsupplier2.md) object represents the port supplier for a port.  
  
## Return Value  
 If successful, returns `S_OK`; otherwise, returns an error code.  
  
## See Also  
 [IDebugPort2](../../../extensibility/debugger/reference/idebugport2.md)   
 [IDebugPortSupplier2](../../../extensibility/debugger/reference/idebugportsupplier2.md)