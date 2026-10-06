## Charts

> `/System/Library/Frameworks/Charts.framework/Charts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x9e00` | `0xafe8` | **`+0x11e8`** |
| `__AUTH.__data` | `0x3500` | `0x2a78` | **`-0xa88`** |
| `__DATA.__data` | `0x54e8` | `0x4c30` | **`-0x8b8`** |
| `__DATA_DIRTY.__bss` | `0xe6b0` | `0xef30` | **`+0x880`** |
| `__DATA.__bss` | `0xb090` | `0xa820` | **`-0x870`** |
| `__TEXT.__text` | `0x2edacc` | `0x2edfdc` | **`+0x510`** |
| `__AUTH.__objc_data` | `0x498` | `0x168` | **`-0x330`** |
| `__DATA_DIRTY.__objc_data` | `0x1a8` | `0x4d8` | **`+0x330`** |
| `__AUTH_CONST.__const` | `0x1c8b0` | `0x1ca00` | **`+0x150`** |
| `__TEXT.__const` | `0x3fd48` | `0x3fe88` | **`+0x140`** |
| `__TEXT.__eh_frame` | `0x44a8` | `0x4418` | **`-0x90`** |
| `__TEXT.__unwind_info` | `0x71b0` | `0x7170` | **`-0x40`** |
| `__TEXT.__cstring` | `0x2b06` | `0x2b36` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x100` | `0x120` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0xfd48` | `0xfd30` | **`-0x18`** |
| `__TEXT.__swift5_fieldmd` | `0xb9f8` | `0xba10` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x10a0` | `0x1090` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x7a0` | `0x7b0` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x102f7` | `0x10307` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2920` | `0x2928` | **`+0x8`** |
| `__DATA.__common` | `0x1e8` | `0x1e1` | **`-0x7`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-5.0.40.0.0
+5.0.44.0.0

-  Functions: 12707
-  Symbols:   352
-  CStrings:  230
+  Functions: 12696
+  Symbols:   355
+  CStrings:  232
Symbols:
+ _OBJC_CLASS_$_NSUserDefaults
+ __NSConcreteGlobalBlock
+ _dispatch_once
+ _os_variant_allows_internal_security_policies
+ _os_variant_has_internal_content
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
CStrings:
+ "com.apple.Charts.AcceleratedDSL"
+ "v8@?0"
```
