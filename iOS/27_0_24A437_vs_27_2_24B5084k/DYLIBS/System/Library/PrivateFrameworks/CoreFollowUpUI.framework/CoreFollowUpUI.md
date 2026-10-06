## CoreFollowUpUI

> `/System/Library/PrivateFrameworks/CoreFollowUpUI.framework/CoreFollowUpUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb3a0` | `0xb4ec` | **`+0x14c`** |
| `__TEXT.__oslogstring` | `0x953` | `0x999` | **`+0x46`** |
| `__AUTH_CONST.__cfstring` | `0x580` | `0x5a0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x634` | `0x64f` | **`+0x1b`** |
| `__DATA_CONST.__objc_selrefs` | `0xa08` | `0xa20` | **`+0x18`** |
| `__DATA.__bss` | `0x190` | `0x1a0` | **`+0x10`** |
| `__TEXT.__const` | `0x1c2` | `0x1d2` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x3d0` | `0x3d8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xa7c` | `0xa84` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3e0` | `0x3e8` | **`+0x8`** |

### Other Changes

```diff

-2027.0.6.0.0
+2027.1.2.0.0

-  Functions: 277
-  Symbols:   743
-  CStrings:  123
+  Functions: 279
+  Symbols:   746
+  CStrings:  125
Symbols:
+ -[FLExtensionContext _hostIsEntitled]
+ __os_log_fault_impl
+ _flReportedUnentitledHost
CStrings:
+ "Refusing FollowUp extension logic for host pid %d: missing %{public}@"
+ "com.apple.private.followup"
```
