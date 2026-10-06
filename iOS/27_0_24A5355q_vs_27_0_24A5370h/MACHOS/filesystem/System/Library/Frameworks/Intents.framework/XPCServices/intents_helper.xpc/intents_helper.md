## intents_helper

> `/System/Library/Frameworks/Intents.framework/XPCServices/intents_helper.xpc/intents_helper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__delay_helper` | `—` | `0xdc` | **`+0xdc`** |
| `__TEXT.__cstring` | `0x3a5` | `0x3de` | **`+0x39`** |
| `__TEXT.__auth_stubs` | `0x350` | `0x360` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1b8` | `0x1c0` | **`+0x8`** |
| `__TEXT.__text` | `0x1b18` | `0x1b10` | **`-0x8`** |
| `__DATA.__data` | `0x120` | `0x124` | **`+0x4`** |

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

-4016.0.41.16.102
+4016.0.42.4.0

-  Symbols:   100
-  CStrings:  163
+  Symbols:   101
+  CStrings:  164
Symbols:
+ _dlopen
Functions:
~ sub_10000190c -> sub_10000195c : 1020 -> 1016
~ sub_100001fe0 -> sub_10000202c : 616 -> 612
CStrings:
+ "/System/Library/Frameworks/IntentsUI.framework/IntentsUI"
```
