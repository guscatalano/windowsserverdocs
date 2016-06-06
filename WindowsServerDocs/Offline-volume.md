---
title: Offline volume
ms.custom: na
ms.prod: windows-server-2012
ms.reviewer: na
ms.suite: na
ms.technology: 
  - techgroup-storage
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: b8f7192f-ea38-47d0-9d4e-58ef68336ae6
author: JasonGerend
---
# Offline volume
Takes the online volume with focus to the offline state.  
  
> [!IMPORTANT]  
> This DiskPart command is not available in any edition of [!INCLUDE[nextref_vista](includes/nextref_vista_md.md)].  
  
## Syntax  
  
```  
offline volume [noerr]  
```  
  
## Parameters  
  
|Parameter|Description|  
|-------------|---------------|  
|noerr|For scripting only. When an error is encountered, DiskPart continues to process commands as if the error did not occur. Without this parameter, an error causes DiskPart to exit with an error code.|  
  
## Remarks  
  
-   A volume must be selected for this to succeed. Use the **select volume** command to select a disk and shift the focus to it.  
  
## <a name="BKMK_examples"></a>Examples  
To take the disk with focus offline, type:  
  
```  
offline volume  
```  
  
#### Additional references  
[Command-Line Syntax Key](Command-Line-Syntax-Key.md)  
  
[Diskpart \[LH\]](assetId:///26a4a166-95fa-4faf-95bc-2d5345f4a57a)  
  
