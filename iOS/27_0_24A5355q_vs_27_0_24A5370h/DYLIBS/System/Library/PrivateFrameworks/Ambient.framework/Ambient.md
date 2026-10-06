## Ambient

> `/System/Library/PrivateFrameworks/Ambient.framework/Ambient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5ab8` | `0x5cb0` | **`+0x1f8`** |
| `__TEXT.__oslogstring` | `0x550` | `0x5ab` | **`+0x5b`** |
| `__AUTH_CONST.__cfstring` | `0x720` | `0x760` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x1ae8` | `0x1b18` | **`+0x30`** |
| `__TEXT.__cstring` | `0x709` | `0x72a` | **`+0x21`** |
| `__TEXT.__objc_methlist` | `0x9b4` | `0x9cc` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0xc0` | `0xd4` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x7f0` | `0x800` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2d8` | `0x2e8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x150` | `0x158` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xcc` | `0xd0` | **`+0x4`** |

### Other Changes

```diff

-101.0.100.0.0
+104.0.0.0.0

-  Functions: 209
-  Symbols:   519
-  CStrings:  106
+  Functions: 212
+  Symbols:   525
+  CStrings:  109
Symbols:
+ -[AMRedModeSettings alwaysActivated]
+ -[AMRedModeSettings setAlwaysActivated:]
+ GCC_except_table28
+ GCC_except_table34
+ _NSProcessInfoPowerStateDidChangeNotification
+ _OBJC_IVAR_$_AMRedModeSettings._alwaysActivated
+ ___65-[AMAmbientPresentationTriggerManager _deviceBatteryStateChanged]_block_invoke
- GCC_except_table33
CStrings:
+ "Always activated"
+ "Red mode should trigger: YES [ PROTOTYPING OVERRIDE ACTIVE; isDarkEnvironment : %{BOOL}u ]"
+ "alwaysActivated"
```
