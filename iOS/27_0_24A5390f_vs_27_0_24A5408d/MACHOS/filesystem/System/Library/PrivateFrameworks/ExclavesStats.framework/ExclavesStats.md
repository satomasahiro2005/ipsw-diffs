## ExclavesStats

> `/System/Library/PrivateFrameworks/ExclavesStats.framework/ExclavesStats`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13db4` | `0x13ecc` | **`+0x118`** |
| `__TEXT.__cstring` | `0x6c3` | `0x703` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x850` | `0x870` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x430` | `0x440` | **`+0x10`** |

### Same-size Content Changes

- `__AUTH.__data`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__DATA_CONST.__objc_selrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-10848.0.13.0.0
+10848.0.14.0.0

+  - /usr/lib/libMobileGestalt.dylib

-  Symbols:   954
-  CStrings:  71
+  Symbols:   956
+  CStrings:  72
Symbols:
+ _MGGetBoolAnswer
+ _MGIsQuestionValid
Functions:
~ _$s13ExclavesStats0aB8SyscallsC17exclavesAvailableSbvgZ : 28 -> 308
CStrings:
+ "ExclaveCapability"
+ "PerfUtils.ExclavesStatsServer.exclaves_stats"
- "exclaves.stats"
```
