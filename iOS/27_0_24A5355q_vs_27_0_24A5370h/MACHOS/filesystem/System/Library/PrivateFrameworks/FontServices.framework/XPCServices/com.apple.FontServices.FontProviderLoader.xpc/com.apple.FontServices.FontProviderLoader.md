## com.apple.FontServices.FontProviderLoader

> `/System/Library/PrivateFrameworks/FontServices.framework/XPCServices/com.apple.FontServices.FontProviderLoader.xpc/com.apple.FontServices.FontProviderLoader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2444` | `0x25fc` | **`+0x1b8`** |
| `__TEXT.__gcc_except_tab` | `—` | `0x98` | **`+0x98`** |
| `__TEXT.__cstring` | `0x405` | `0x491` | **`+0x8c`** |
| `__DATA_CONST.__cfstring` | `0x400` | `0x440` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x430` | `0x450` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x9a0` | `0x9c0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x220` | `0x238` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xf0` | `0x108` | **`+0x18`** |
| `__TEXT.__const` | `0x60` | `0x68` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-167.0.0.0.0
+168.0.0.0.0

-  Symbols:   126
-  CStrings:  242
+  Symbols:   129
+  CStrings:  244
Symbols:
+ __Block_object_dispose
+ __Unwind_Resume
+ ___objc_personality_v0
Functions:
~ sub_100001da0 -> sub_100001df0 : 1252 -> 1392
~ sub_1000022d0 -> sub_1000023ac : 1168 -> 1260
~ sub_1000028d8 -> sub_100002a10 : 848 -> 984
~ sub_100002c28 -> sub_100002de8 : 212 -> 288
~ sub_100002fe8 -> sub_1000031f4 : 476 -> 472
CStrings:
+ "registerFonts received malformed fontsInfo; dropping the connection."
+ "unregisterFonts received malformed fontsInfo; dropping the connection."
```
