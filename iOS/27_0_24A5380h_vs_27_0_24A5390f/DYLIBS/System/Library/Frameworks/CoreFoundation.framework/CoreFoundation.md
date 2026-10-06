## CoreFoundation

> `/System/Library/Frameworks/CoreFoundation.framework/CoreFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d2304` | `0x1d29c0` | **`+0x6bc`** |
| `__DATA.__bss` | `0x894` | `0x85c` | **`-0x38`** |
| `__DATA_DIRTY.__bss` | `0xec0` | `0xef8` | **`+0x38`** |
| `__TEXT.__oslogstring` | `0x59c8` | `0x59f1` | **`+0x29`** |
| `__TEXT.__cstring` | `0x14b349` | `0x14b36c` | **`+0x23`** |
| `__DATA_CONST.__const` | `0x3c89b0` | `0x3c89c0` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x5e20` | `0x5e18` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x6538` | `0x6540` | **`+0x8`** |

### Other Changes

```diff

-5027.0.59.0.0
+5027.0.63.2.0

-  Functions: 8592
-  Symbols:   11458
-  CStrings:  44295
+  Functions: 8601
+  Symbols:   11459
+  CStrings:  44298
Symbols:
+ -[CFPrefsDaemon createQueueForClientWithPID:uid:]
+ -[CFPrefsDaemon createSecondaryQueueForClientWithPID:]
+ __postCFPreferencesChangedDomainsNotification
- -[CFPrefsDaemon createQueueForClientWithPID:secondary:]
- __handleExternalNotification
CStrings:
+ "/usr/bin/security"
+ "/usr/libexec/lsd"
+ "proc_pidpath(%i) error: %{darwin.errno}d"
```
