## intents_helper

> `/System/Library/Frameworks/Intents.framework/XPCServices/intents_helper.xpc/intents_helper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__delay_helper` | `0xdc` | `—` | **`-0xdc`** |
| `__TEXT.__cstring` | `0x3de` | `0x3a5` | **`-0x39`** |
| `__TEXT.__auth_stubs` | `0x360` | `0x350` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x1c0` | `0x1b8` | **`-0x8`** |
| `__DATA.__data` | `0x124` | `0x120` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-4016.0.42.4.0
+4016.0.43.5.0

-  Symbols:   101
-  CStrings:  164
+  Symbols:   100
+  CStrings:  163
Symbols:
- _dlopen
CStrings:
- "/System/Library/Frameworks/IntentsUI.framework/IntentsUI"
```
