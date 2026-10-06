## visionhwserverd

> `/usr/libexec/visionhwserverd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x450` | `0x4d8` | **`+0x88`** |
| `__DATA_CONST.__cfstring` | `—` | `0x40` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `—` | `0x40` | **`+0x40`** |
| `__TEXT.__objc_methname` | `—` | `0x27` | **`+0x27`** |
| `__TEXT.__auth_stubs` | `0x190` | `0x1b0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x58` | `0x74` | **`+0x1c`** |
| `__DATA_CONST.__auth_got` | `0xd0` | `0xe8` | **`+0x18`** |
| `__TEXT.__cstring` | `0xbc` | `0xd4` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0xa2` | `0xb8` | **`+0x16`** |
| `__DATA.__objc_selrefs` | `—` | `0x10` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x28` | `0x30` | **`+0x8`** |
| `__TEXT.__const` | `0x28` | `0x30` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-4.4.9.0.0
+4.4.10.0.0

-  Symbols:   33
-  CStrings:  11
+  Symbols:   38
+  CStrings:  15
Symbols:
+ _OBJC_CLASS_$_NSBundle
+ ___CFConstantStringClassReference
+ _objc_claimAutoreleasedReturnValue
+ _objc_msgSend
+ _objc_release_x20
Functions:
~ sub_1000031b8 -> sub_1000032f8 : 880 -> 1016
CStrings:
+ "CFBundleVersion"
+ "mainBundle"
+ "objectForInfoDictionaryKey:"
+ "unknown"
+ "visionhwserverd (version: %{public}@) is launching..."
- "visionhwserverd is launching..."
```
