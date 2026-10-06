## ParavirtualizedANE

> `/System/Library/PrivateFrameworks/ParavirtualizedANE.framework/ParavirtualizedANE`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fa8c` | `0x1fb48` | **`+0xbc`** |
| `__TEXT.__oslogstring` | `0x645e` | `0x64a6` | **`+0x48`** |
| `__AUTH_CONST.__auth_got` | `0x310` | `0x320` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x3b3c` | `0x3b48` | **`+0xc`** |

### Other Changes

```diff

-382.11.0.0.0
+382.12.0.0.0

-  Functions: 538
-  Symbols:   552
-  CStrings:  558
+  Functions: 539
+  Symbols:   554
+  CStrings:  559
Symbols:
+ _strlcpy
+ _strnlen
Functions:
~ -[_ANEVirtualPlatformClient exchangeBuildVersionInfo:] : 860 -> 944
~ _OUTLINED_FUNCTION_22 : 28 -> 12
~ _OUTLINED_FUNCTION_23 : 12 -> 28
+ -[_ANEVirtualPlatformClient exchangeBuildVersionInfo:].cold.4
CStrings:
+ "%@: buildVersion (%zu bytes) larger than max buffer size %d, truncated\n"
```
