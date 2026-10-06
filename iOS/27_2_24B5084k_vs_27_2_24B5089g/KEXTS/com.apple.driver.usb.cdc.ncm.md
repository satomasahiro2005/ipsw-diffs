## com.apple.driver.usb.cdc.ncm

> `com.apple.driver.usb.cdc.ncm`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0xd950` | `0xda40` | **`+0xf0`** |
| `__TEXT.__cstring` | `0x2414` | `0x248b` | **`+0x77`** |

### Other Changes

```diff

-404.0.0.0.0
+404.40.2.0.0

-  CStrings:  239
+  CStrings:  241
Functions:
~ sub_fffffff009bdfa98 -> sub_fffffff009be15e8 : 164 -> 260
~ __ZN15AppleUSBNCMData7armReadEP15InputPipeRecord : 404 -> 548
CStrings:
+ "Patching invalid NCM 1.1 NTB parameter wNdpInAlignment %d\n"
+ "Patching invalid NCM 1.1 NTB parameter wNdpOutAlignment %d\n"
```
