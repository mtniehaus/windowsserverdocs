---
title: Ftp: mdelete_1
description: "Windows Commands"
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: manage-windows-commands
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 8a80a8f5-e880-40a8-abc9-29a41836844f vhorne
author: coreyp-at-msft
ms.author: coreyp
manager: dongill
ms.date: 10/12/2016
---

# Ftp: mdelete_1

>Applies To: Windows Server&reg; 2016, Windows Server&reg; 2012 R2, Windows Server&reg; 2012

Deletes files on the remote computer. For examples of how this command can be used, see [Examples](assetId:///c6d43992-8243-4f0a-8605-3152c8a8fe9a#BKMK_Examples).  
## Syntax  
```  
mdelete <RemoteFile>[…]  
```  
### Parameters  
|Parameter|Description|  
|-------------|---------------|  
|<RemoteFile>|Specifies the remote file to delete.|  
## <a name="BKMK_Examples"></a>Examples  
Delete remote files **a.exe** and **b.exe**.  
```  
mdelete a.exe b.exe  
```  
## Additional references  
-   [Command-Line Syntax Key](Command-Line-Syntax-Key.md)  