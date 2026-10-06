## BiometricSupport

> `/System/Library/PrivateFrameworks/BiometricSupport.framework/BiometricSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ee4c` | `0x4ec20` | **`-0x22c`** |
| `__AUTH_CONST.__cfstring` | `0x2200` | `0x2160` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x7043` | `0x6fd1` | **`-0x72`** |
| `__AUTH_CONST.__objc_dictobj` | `0x50` | `—` | **`-0x50`** |
| `__DATA_CONST.__objc_arraydata` | `0x20` | `—` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0x105c` | `0x1074` | **`+0x18`** |
| `__DATA.__bss` | `0x61` | `0x51` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x98` | `0xa8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x830` | `0x828` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1090` | `0x1098` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0x377a` | `0x377b` | **`+0x1`** |

### Other Changes

```diff

-578.40.6.0.0
+578.40.7.0.0

-  Functions: 2033
-  Symbols:   2773
-  CStrings:  1240
+  Functions: 2028
+  Symbols:   2771
+  CStrings:  1232
Symbols:
+ _OBJC_IVAR_$_BiometricKitXPCServer._displayStatusNotifyTokenValid
- _CFDictionaryGetValue
- _OBJC_CLASS_$_NSConstantDictionary
- _OBJC_IVAR_$_BiometricKitXPCServer._backlightService
CStrings:
+ "AssertMacros: %s (value = 0x%lx), version: BiometricKit-578.40.7~110, %s file: %s, line: %d\n\n"
+ "notify_status == 0 "
- "AssertMacros: %s (value = 0x%lx), version: BiometricKit-578.40.6~32, %s file: %s, line: %d\n\n"
- "IODisplayParameters"
- "IOPropertyMatch"
- "_backlightService"
- "backlight-control"
- "brightness"
- "cfBrightnessKey"
- "cfBrightnessValue"
- "cfProperty"
- "value"
```
