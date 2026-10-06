## AppleGameControllerPersonality_development

> `/System/Library/Extensions/AppleGameControllerPersonality.kext/AppleGameControllerPersonality_development`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1edc` | `0x1f44` | **`+0x68`** |
| `__TEXT.__os_log` | `0x27e` | `0x2e3` | **`+0x65`** |
| `__TEXT.__cstring` | `0x235` | `0x24b` | **`+0x16`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`

### Other Changes

```diff

-14.0.19.0.0
+14.0.21.0.0

-  Symbols:   369
-  CStrings:  33
+  Symbols:   370
+  CStrings:  35
Symbols:
+ __ZZN37AppleGCIOHIDEventDriverPropertyMerger5probeEP9IOServicePiE11_os_log_fmt_4
Functions:
~ _OUTLINED_FUNCTION_3 : 16 -> 12
~ __ZN37AppleGCIOHIDEventDriverPropertyMerger5probeEP9IOServicePi : 2064 -> 2172
CStrings:
+ "AppleGCHIDUserEventDriver not matching on <IOHIDDevice %#010llx> with missing GameControllerPointer."
+ "GameControllerPointer"
```
