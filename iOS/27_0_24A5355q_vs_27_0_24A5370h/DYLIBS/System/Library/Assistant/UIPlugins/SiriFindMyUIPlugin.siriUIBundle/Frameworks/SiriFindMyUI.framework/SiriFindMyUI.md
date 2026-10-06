## SiriFindMyUI

> `/System/Library/Assistant/UIPlugins/SiriFindMyUIPlugin.siriUIBundle/Frameworks/SiriFindMyUI.framework/SiriFindMyUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4d728` | `0x4c250` | **`-0x14d8`** |
| `__TEXT.__eh_frame` | `0xc58` | `0xb18` | **`-0x140`** |
| `__TEXT.__oslogstring` | `0x4f3` | `0x463` | **`-0x90`** |
| `__AUTH_CONST.__const` | `0x22e0` | `0x2268` | **`-0x78`** |
| `__AUTH_CONST.__auth_got` | `0x1890` | `0x1828` | **`-0x68`** |
| `__TEXT.__cstring` | `0x81a` | `0x7ba` | **`-0x60`** |
| `__TEXT.__swift5_typeref` | `0x44b2` | `0x445a` | **`-0x58`** |
| `__TEXT.__const` | `0x46d4` | `0x4694` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x1638` | `0x15f8` | **`-0x40`** |
| `__DATA_CONST.__got` | `0xc40` | `0xc08` | **`-0x38`** |
| `__TEXT.__swift5_capture` | `0x630` | `0x5fc` | **`-0x34`** |
| `__DATA.__data` | `0x22e0` | `0x22b0` | **`-0x30`** |
| `__TEXT.__swift5_reflstr` | `0xabc` | `0xa9c` | **`-0x20`** |
| `__AUTH.__data` | `0x15f0` | `0x15e0` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1048` | `0x103c` | **`-0xc`** |
| `__TEXT.__swift_as_entry` | `0x3c` | `0x34` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x50` | `0x4c` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x34` | `0x30` | **`-0x4`** |

### Other Changes

```diff

-3600.12.3.0.0
+3600.18.2.0.0

-  - /System/Library/PrivateFrameworks/IntelligenceFlow.framework/IntelligenceFlow

-  - /System/Library/PrivateFrameworks/ToolKit.framework/ToolKit

-  Functions: 2087
-  Symbols:   1200
-  CStrings:  86
+  Functions: 2074
+  Symbols:   1193
+  CStrings:  82
Symbols:
- _swift_task_create
- _symbolic SS16bundleIdentifier_SS8typeNamet
- _symbolic SS______t 7ToolKit18ConcreteResolvableO
- _symbolic ScPSg
- _symbolic _____Sg 7ToolKit21DisplayRepresentationV
- _symbolic _____ySS______tG s23_ContiguousArrayStorageC 7ToolKit18ConcreteResolvableO
- _symbolic ytIeAgHr_
CStrings:
- "[ItemLocationSnippet] Failed to build prescribed action: %@"
- "[ItemLocationSnippet] Performing prescribed action for Play Sound"
- "com.apple.siri.findmy.PlayItemSound"
- "{\"domain\":\"findMy\",\"kind\":\"PlayItemSoundTool\"}"
```
