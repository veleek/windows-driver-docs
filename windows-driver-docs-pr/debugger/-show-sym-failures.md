---
title: .show\_sym\_failures
description: The .show\_sym\_failures command enables or disables the display of symbol lookup failures and type lookup failures.
ms.assetid: cf0b6cfd-aad2-482f-a382-a3909f5f3cd4
keywords: [".show_sym_failures Windows Debugging"]
ms.author: windowsdriverdev
ms.date: 05/23/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
topic_type:
- apiref
api_name:
- .show_sym_failures
api_type:
- NA
---

# .show\_sym\_failures


The **.show\_sym\_failures** command enables or disables the display of symbol lookup failures and type lookup failures.

```
.show_sym_failures /s 
.show_sym_failures /S
.show_sym_failures /t
.show_sym_failures /T
```

## <span id="Parameters"></span><span id="parameters"></span><span id="PARAMETERS"></span>Parameters


<span id="________s______"></span><span id="________S______"></span> **/s**   
Enables the display of symbol lookup failures.

<span id="________S______"></span><span id="________s______"></span> **/S**   
Disables the display of symbol lookup failures.

<span id="________t______"></span><span id="________T______"></span> **/t**   
Enables the display of type lookup failures.

<span id="________T______"></span><span id="________t______"></span> **/T**   
Disables the display of type lookup failures.

## <span id="Environment"></span><span id="environment"></span><span id="ENVIRONMENT"></span>Environment


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><p><strong>Modes</strong></p></td>
<td align="left"><p>user mode, kernel mode</p></td>
</tr>
<tr class="even">
<td align="left"><p><strong>Targets</strong></p></td>
<td align="left"><p>live, crash dump</p></td>
</tr>
<tr class="odd">
<td align="left"><p><strong>Platforms</strong></p></td>
<td align="left"><p>all</p></td>
</tr>
</tbody>
</table>

 

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20[debugger\debugger]:%20.show_sym_failures%20%20RELEASE:%20%285/15/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")




