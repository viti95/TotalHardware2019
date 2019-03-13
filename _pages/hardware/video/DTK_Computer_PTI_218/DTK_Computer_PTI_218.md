---
title: 'DTK Computer PTI-218 V.G.A. CARD'
company: 'DTK Computer'
preview: '/_pages/hardware/video/DTK_Computer_PTI_218/img/preview.jpg'
hardware: 'Video cards'
port: 'ISA 16-bit'
---
# DTK Computer
## PTI-218 V.G.A. CARD

![Front]({{'/_pages/hardware/video/DTK_Computer_PTI_218/img/front.jpg' | relative_url}})
![Back]({{'/_pages/hardware/video/DTK_Computer_PTI_218/img/back.jpg' | relative_url}})

|**INFORMATION**|
|-|-|
|**Card type**|Video card|
|**FCC ID**||
|**Video chipset**|Trident TVGA 8800CS|
|**Video memory**|256KB DRAM (upgradable to 512KB)|
|**Video types supported**|Monochrome, CGA, EGA, VGA|
|**Highest Resolution Supported**||
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
|Video ram|U1..U16|NMB Semiconductor 9026 V53C464AP80|
|Programmable array logic|U30,U31|National Semiconductor PAL16L8ANC| 

|**ROM**|
|-|-|
|**Function**|**Size**|**Download**|
|TVGA BIOS D4-131 Ver 1.10 High|32&nbsp;KB|[U24.bin]({{'/_pages/hardware/video/DTK_Computer_PTI_218/bios/U24.bin' | relative_url}})
|TVGA BIOS D4-131 Ver 1.10 Low|32&nbsp;KB|[U25.bin]({{'/_pages/hardware/video/DTK_Computer_PTI_218/bios/U25.bin' | relative_url}})