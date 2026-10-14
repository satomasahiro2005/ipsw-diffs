## AnimationKit

> `/System/Library/PrivateFrameworks/AnimationKit.framework/AnimationKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb0af8` | `0xb127c` | **`+0x784`** |
| `__AUTH_CONST.__const` | `0x8050` | `0x8298` | **`+0x248`** |
| `__DATA.__bss` | `0x3290` | `0x3390` | **`+0x100`** |
| `__TEXT.__cstring` | `0x3312` | `0x33f2` | **`+0xe0`** |
| `__DATA.__data` | `0xe60` | `0xf08` | **`+0xa8`** |
| `__TEXT.__const` | `0x5aa8` | `0x5b48` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0x3a10` | `0x3a5c` | **`+0x4c`** |
| `__TEXT.__eh_frame` | `0x670` | `0x6b8` | **`+0x48`** |
| `__AUTH_CONST.__objc_const` | `0x3d28` | `0x3d68` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x2b00` | `0x2b40` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x2cd7` | `0x2d02` | **`+0x2b`** |
| `__DATA_DIRTY.__data` | `0x25c8` | `0x25e8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x26d8` | `0x26b8` | **`-0x20`** |
| `__TEXT.__swift5_capture` | `0x15c0` | `0x15b0` | **`-0x10`** |
| `__AUTH.__data` | `0xc18` | `0xc20` | **`+0x8`** |
| `__AUTH_CONST.__auth_got` | `0xe40` | `0xe48` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xa80` | `0xa88` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x2782` | `0x277a` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x270` | `0x274` | **`+0x4`** |

### Other Changes

```diff

-9127.1.12.1.101
+9127.1.13.1.106

-  Functions: 4311
-  Symbols:   1489
-  CStrings:  296
+  Functions: 4333
+  Symbols:   1492
+  CStrings:  299
Symbols:
+ ___swift_closure_destructor.222Tm
+ ___unnamed_107
+ ___unnamed_19
+ ___unnamed_93
+ ___unnamed_94
+ _symbolic _____ 12AnimationKit09InProcessA5StateC19DecomposedComponent33_40B5E8EE161714FD84B918C9F1C13020LLV
+ _symbolic _____xc 12CoreGraphics7CGFloatV
+ _symbolic ySo13CADisplayLinkC______tcSg 12AnimationKit09InProcessA7ManagerC13ExecutionModeO
+ _type_layout_string l12AnimationKit09InProcessA5StateC19DecomposedComponent33_40B5E8EE161714FD84B918C9F1C13020LLVy_xG
- ___swift_closure_destructor.225Tm
- ___unnamed_105
- ___unnamed_3
- ___unnamed_91
- ___unnamed_92
- _symbolic ySo13CADisplayLinkC___________tcSg 12AnimationKit09InProcessA7ManagerC13ExecutionModeO So16CAFrameRateRangeV
CStrings:
+ "' was requested on layer (delegate "
+ ") while a composite animation is already running on it. Enable decomposition for all\nanimations running simultaneously on this layer."
+ "Decomposition of '"
```
