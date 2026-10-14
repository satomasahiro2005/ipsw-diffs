## BackgroundAssets

> `/System/Library/Frameworks/BackgroundAssets.framework/BackgroundAssets`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa9f48` | `0xab098` | **`+0x1150`** |
| `__TEXT.__eh_frame` | `0x4f48` | `0x50e8` | **`+0x1a0`** |
| `__DATA.__bss` | `0x3c80` | `0x3d00` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x21d0` | `0x2240` | **`+0x70`** |
| `__TEXT.__const` | `0x3228` | `0x3298` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x1e98` | `0x1f00` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0x5ee8` | `0x5e88` | **`-0x60`** |
| `__TEXT.__swift5_typeref` | `0x144f` | `0x1487` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0xcd8` | `0xd08` | **`+0x30`** |
| `__TEXT.__cstring` | `0x439a` | `0x43ca` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x888` | `0x8b4` | **`+0x2c`** |
| `__DATA_CONST.__got` | `0x700` | `0x718` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x15a0` | `0x15b8` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x8c` | `0xa0` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x11c8` | `0x11d8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xbb8` | `0xbc8` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0xa20` | `0xa30` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x2c8` | `0x2d4` | **`+0xc`** |
| `__DATA.__data` | `0x1448` | `0x1440` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x154` | `0x15c` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x194` | `0x19c` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1e0` | `0x1e4` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0xc0` | `0xc4` | **`+0x4`** |

### Other Changes

```diff

-279.40.6.0.0
+279.40.8.0.0

-  Functions: 2163
-  Symbols:   1576
-  CStrings:  666
+  Functions: 2181
+  Symbols:   1579
+  CStrings:  667
Symbols:
+ ___swift_closure_destructor.102Tm
+ ___swift_closure_destructor.107Tm
+ ___swift_closure_destructor.111Tm
+ ___swift_closure_destructor.268Tm
+ ___swift_closure_destructor.306Tm
+ ___swift_closure_destructor.85Tm
+ _symbolic _____ So23BASizeCalculationMethodV
+ _symbolic _____So7NSErrorCSgIeyBhyy_ s5Int64V
+ _symbolic ___________pSgIeghyg_ s5Int64V s5ErrorP
- ___swift_closure_destructor.104Tm
- ___swift_closure_destructor.108Tm
- ___swift_closure_destructor.246Tm
- ___swift_closure_destructor.295Tm
- ___swift_closure_destructor.82Tm
- ___swift_closure_destructor.99Tm
CStrings:
+ "BackgroundAssets/SizeCalculationMethod.swift"
+ "Local size of asset pack with ID: %{public}s calculation method: %{public}s"
+ "Local version of asset pack with ID: %{public}s"
- "Rescheduling the essential download with the ID “%{public}s” as an optional download…"
- "The essential download with the ID “%{public}s” couldn’t be rescheduled as an optional download: %{public}@"
```
