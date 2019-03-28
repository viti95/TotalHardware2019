---
title: 'Unknown GW-V16A Rev 2.1'
company: 'Unknown'
preview: '/_pages/hardware/video/Unknown_GW_V16A_R21/img/preview.jpg'
hardware: 'Videocard'
port: 'ISA 16-bit'
front: '/_pages/hardware/video/Unknown_GW_V16A_R21/img/front.jpg'
back: '/_pages/hardware/video/Unknown_GW_V16A_R21/img/back.jpg'
---
## Unknown
### GW-V16A Rev 2.1

[![Front]({{page.front | relative_url}})]({{page.front | relative_url}})
[![Back]({{page.back | relative_url}})]({{page.back | relative_url}})

|**INFORMATION**|
|-|-|
|**Card type**|Video card|
|**Video chipset**|Chips F82C450|
|**Video types supported**|MDA, CGA, EGA, VGA|
|**Highest Resolution Supported**|1024x768 4 bit color|
|**Data bus**|ISA 16-bit|

|**CONNECTIONS**|
|-|-|
|**Function**|**Label**|
|-|-|
|15-pin analog video port (VGA)|J1|

|**SETTINGS**|
|-|-|
|**Function**|**Label**|
|Unknown|JP1|
|Unknown|JP2|
|Unknown|JP3|
|Unknown|JP4|
|Unknown|JP5|
|Unknown|JP6|


|**MAIN ICS**|
|-|-|-|
|**Function**|**Label**|**IC**|
|Video bios|U5,U10|Texas Instruments TMS27C256|
|GPU|U8|Chips F82C450|
|Video ram|U1,U2,U6,U7|NMB Semiconductor AAA1M304P-07|
|Programmable array logic|U9|National Semiconductor PAL16L8ANC| 

|**ROM**|
|-|-|
|**Function**|**Size**|**Download**|
|Extended BIOS (16 bit)|32&nbsp;KB|[U5.bin]({{'/_pages/hardware/video/Unknown_GW_V16A_R21/bios/U5.bin' | relative_url}})
|Chips 450 VGA BIOS Version 1.0.1|32&nbsp;KB|[U10.bin]({{'/_pages/hardware/video/Unknown_GW_V16A_R21/bios/U10.bin' | relative_url}})|