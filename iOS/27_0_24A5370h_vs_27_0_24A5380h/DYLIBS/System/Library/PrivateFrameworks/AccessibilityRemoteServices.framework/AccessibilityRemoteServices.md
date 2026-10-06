## AccessibilityRemoteServices

> `/System/Library/PrivateFrameworks/AccessibilityRemoteServices.framework/AccessibilityRemoteServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ba8` | `0x4c3c` | **`+0x94`** |
| `__TEXT.__gcc_except_tab` | `0x17c` | `0x1a8` | **`+0x2c`** |
| `__AUTH_CONST.__cfstring` | `0xfc0` | `0xfa0` | **`-0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x78` | `0x90` | **`+0x18`** |
| `__TEXT.__cstring` | `0xd61` | `0xd4c` | **`-0x15`** |
| `__DATA_CONST.__got` | `0xd0` | `0xd8` | **`+0x8`** |

### Other Changes

```diff

-3232.3.0.0.0
+3234.5.0.0.0

+  - /System/Library/Frameworks/SystemConfiguration.framework/SystemConfiguration

-  Symbols:   355
+  Symbols:   357
Symbols:
+ _RPOptionStatusFlags
+ _SCDynamicStoreCopyComputerName
Functions:
~ -[AXRemoteReceiver initWithEventID:delegate:] : 920 -> 1068
CStrings:
+ "Q"
- "UserAssignedDeviceName"
```
