## storagekitd

> `/usr/libexec/storagekitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2cda8` | `0x2ce70` | **`+0xc8`** |
| `__DATA_CONST.__got` | `0x528` | `0x568` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x275f` | `0x2784` | **`+0x25`** |
| `__TEXT.__cstring` | `0x2ea6` | `0x2ec6` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xc40` | `0xc50` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x630` | `0x638` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1076.0.0.0.0
+1076.0.1.0.0

-  Functions: 922
-  Symbols:   375
-  CStrings:  2154
+  Functions: 923
+  Symbols:   376
+  CStrings:  2156
Symbols:
+ _DARegisterExitCallback
CStrings:
+ "%s: Received DA daemon exit callback"
+ "void DaemonExitCallback(void *)"
```
