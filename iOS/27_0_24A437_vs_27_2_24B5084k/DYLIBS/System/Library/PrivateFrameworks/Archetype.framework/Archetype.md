## Archetype

> `/System/Library/PrivateFrameworks/Archetype.framework/Archetype`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa90d0` | `0xab9c0` | **`+0x28f0`** |
| `__DATA.__bss` | `0x24700` | `0x24a80` | **`+0x380`** |
| `__TEXT.__const` | `0x150c8` | `0x152e0` | **`+0x218`** |
| `__AUTH_CONST.__const` | `0xc3f8` | `0xc568` | **`+0x170`** |
| `__TEXT.__eh_frame` | `0x48e0` | `0x4a20` | **`+0x140`** |
| `__TEXT.__unwind_info` | `0x4790` | `0x4838` | **`+0xa8`** |
| `__DATA.__data` | `0x3150` | `0x31e8` | **`+0x98`** |
| `__AUTH.__data` | `0x660` | `0x6e0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x2d64` | `0x2de4` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x32d4` | `0x3344` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x3aeb` | `0x3b5b` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0x9a8` | `0x9f0` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x4dc8` | `0x4e10` | **`+0x48`** |
| `__TEXT.__swift5_proto` | `0x14b8` | `0x14d4` | **`+0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0x170` | `0x180` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x23c` | `0x24c` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x39c` | `0x3a8` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x518` | `0x524` | **`+0xc`** |
| `__AUTH_CONST.__objc_const` | `0xe68` | `0xe70` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x1b20` | `0x1b28` | **`+0x8`** |
| `__TEXT.__swift5_reflstr` | `0x27ba` | `0x27c1` | **`+0x7`** |
| `__TEXT.__swift_as_cont` | `0xd0` | `0xd4` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x94` | `0x98` | **`+0x4`** |

### Other Changes

```diff

-41.11.0.0.0
+41.13.0.0.0

-  Functions: 7898
-  Symbols:   179
-  CStrings:  431
+  Functions: 7982
+  Symbols:   180
+  CStrings:  433
Symbols:
+ _OBJC_CLASS_$_NSRegularExpression
CStrings:
+ "Archetype/LanguageUtilities.swift"
+ "[\\p{L}&&[^\\p{scx=Han}\\p{scx=Hiragana}\\p{scx=Katakana}\\p{scx=Hangul}]]"
```
