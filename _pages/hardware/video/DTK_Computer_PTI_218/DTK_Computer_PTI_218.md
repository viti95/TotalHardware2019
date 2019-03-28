---
title: 'DTK Computer PTI-218 V.G.A. CARD'
company: 'DTK Computer'
preview: '/_pages/hardware/video/DTK_Computer_PTI_218/img/preview.jpg'
hardware: 'Videocard'
port: 'ISA 16-bit'
front: '/_pages/hardware/video/DTK_Computer_PTI_218/img/front.jpg'
back: '/_pages/hardware/video/DTK_Computer_PTI_218/img/back.jpg'
---
## DTK Computer
### PTI-218 V.G.A. CARD

[![Front]({{page.front | relative_url}})]({{page.front | relative_url}})
[![Back]({{page.back | relative_url}})]({{page.back | relative_url}})

|**INFORMATION**|
|-|-|
|**Card type**|Video card|
|**Video chipset**|Trident TVGA 8800CS|
|**Video memory**|256KB DRAM (upgradable to 512KB)|
|**Video types supported**|MDA, CGA, EGA, VGA|
|**Data bus**|ISA 16-bit|

|**CONNECTIONS**|
|-|-|
|**Function**|**Label**|
|-|-|
|15-pin analog video port (VGA)|J1|
|9-pin analog video port (Hercules, CGA, EGA)|J2|
|VGA feature connector||

|**SETTINGS**|
|-|-|
|**Function**|**Label**|
|Unknown|SW1|
|Unknown|W2|
|Unknown|W3|
|Unknown|W4|

|**MAIN ICS**|
|-|-|-|
|**Function**|**Label**|**IC**|
|Video bios|U5,U10|ST M27256|
|GPU|U17|Trident TVGA 8800CS|
|Video ram|U1..U16|Mosel Vitelic V53C464AP80|
|Programmable array logic|U30,U31|National Semiconductor PAL16L8ANC| 

|**ROM**|
|-|-|
|**Function**|**Size**|**Download**|
|TVGA BIOS D4-131 Ver 1.10 High|32&nbsp;KB|[U24.bin]({{'/_pages/hardware/video/DTK_Computer_PTI_218/bios/U24.bin' | relative_url}})|
|TVGA BIOS D4-131 Ver 1.10 Low|32&nbsp;KB|[U25.bin]({{'/_pages/hardware/video/DTK_Computer_PTI_218/bios/U25.bin' | relative_url}})|

|**DATASHEETS**|
|-|-|
|**IC**|**Datasheet**|
|Mosel Vitelic V53C464AP80|[Mosel_Vitelic_V53C464A.pdf]({{'/_pages/datasheets/ram/Mosel_Vitelic_V53C464A.pdf' | relative_url}})|
