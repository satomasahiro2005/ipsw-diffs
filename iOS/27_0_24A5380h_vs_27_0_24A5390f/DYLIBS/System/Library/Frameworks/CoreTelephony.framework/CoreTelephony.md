## CoreTelephony

> `/System/Library/Frameworks/CoreTelephony.framework/CoreTelephony`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d3204` | `0x1d3220` | **`+0x1c`** |
| `__TEXT.__cstring` | `0x21ff8` | `0x21fe8` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x1fa9c` | `0x1faac` | **`+0x10`** |

### Other Changes

```diff

-13478.3.1.3.0
+13482.1.0.0.0

-  Functions: 13083
-  Symbols:   24163
+  Functions: 13084
+  Symbols:   24164
Symbols:
+ -[CTServiceDescriptor hash]
Functions:
~ __ZNK14CSIPhoneNumber26tryParseNANPCallForwardingEv : 576 -> 608
+ -[CTServiceDescriptor hash]
~ -[CTDeviceDataUsage totalDataUsedForPeriod:] : 564 -> 512
CStrings:
+ "13482.1"
+ "13482.1~1"
- "13478.3.1.3"
- "13478.3.1.3~3"
```
