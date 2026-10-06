## SiriIdentityInternal

> `/System/Library/PrivateFrameworks/SiriIdentityInternal.framework/SiriIdentityInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x48768` | `0x48af4` | **`+0x38c`** |
| `__TEXT.__eh_frame` | `0x34d8` | `0x3570` | **`+0x98`** |
| `__TEXT.__cstring` | `0xe53` | `0xdd3` | **`-0x80`** |
| `__TEXT.__oslogstring` | `0x2523` | `0x2563` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1728` | `0x1760` | **`+0x38`** |
| `__AUTH_CONST.__const` | `0x1b40` | `0x1b68` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x3dc` | `0x3ec` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x1022` | `0x102e` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x1030` | `0x1038` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x258` | `0x25c` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x274` | `0x278` | **`+0x4`** |

### Other Changes

```diff

-3600.5.1.0.0
+3605.2.1.0.0

-  Functions: 1916
-  Symbols:   906
-  CStrings:  263
+  Functions: 1926
+  Symbols:   908
+  CStrings:  262
Symbols:
+ _swift_retain_x1
+ _symbolic S2SSgIeggo_
CStrings:
+ "Missing switch target in userData; defaulting to disambiguation"
+ "siriSharedUserId"
+ "switch-by-disambiguation: no specific target, presenting profile picker"
- "Either the homeUserId or name must be provided"
- "Either the homeUserId or name must be provided."
- "SiriIdentityInternal/IdentityDirectInvocationConverter.swift"
- "switch-by-disambiguation"
```
