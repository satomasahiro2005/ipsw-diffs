## DumpPanic

> `/usr/libexec/DumpPanic`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2afa4` | `0x2aee4` | **`-0xc0`** |
| `__TEXT.__objc_methname` | `0x1eeb` | `0x1f55` | **`+0x6a`** |
| `__TEXT.__cstring` | `0x2b3b` | `0x2b9b` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x2560` | `0x25a0` | **`+0x40`** |
| `__DATA.__objc_const` | `0xf80` | `0xfb0` | **`+0x30`** |
| `__DATA.__data` | `0x398` | `0x3b8` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xb98` | `0xb78` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x844` | `0x85c` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0xab8` | `0xac8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x2b0` | `0x2a8` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x90` | `0x94` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-31.0.0.0.0
+34.0.0.0.0

-  Functions: 851
-  Symbols:   401
-  CStrings:  1311
+  Functions: 853
+  Symbols:   400
+  CStrings:  1317
Symbols:
+ __os_log_default
+ _swift_release_x19
- _$ss5NeverON
- _$ss5NeverOs5ErrorsWP
- _swift_willThrowTypedImpl
CStrings:
+ "  -r, --rtkit-crashlog FILE\n              use raw RTKit crashlog binary file\n\n"
+ "T@\"NSURL\",&,V_rtkit_crashlog_binary"
+ "_rtkit_crashlog_binary"
+ "hs:i:p:r:b:e:o:"
+ "rtkit-crashlog"
+ "rtkit_crashlog_binary"
+ "setRtkit_crashlog_binary:"
- "hs:i:p:b:e:o:"
```
