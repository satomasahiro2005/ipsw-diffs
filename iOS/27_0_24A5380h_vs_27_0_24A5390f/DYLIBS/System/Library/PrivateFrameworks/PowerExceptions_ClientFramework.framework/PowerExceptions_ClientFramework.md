## PowerExceptions_ClientFramework

> `/System/Library/PrivateFrameworks/PowerExceptions_ClientFramework.framework/PowerExceptions_ClientFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10850` | `0x11424` | **`+0xbd4`** |
| `__TEXT.__oslogstring` | `0x16d5` | `0x176c` | **`+0x97`** |
| `__TEXT.__objc_methlist` | `0xd58` | `0xdb8` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x6b0` | `0x700` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x5d0` | `0x618` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x8b0` | `0x8f0` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0xf88` | `0xfa8` | **`+0x20`** |

### Other Changes

```diff

-174.0.0.0.0
+177.0.8.502.1

-  Functions: 425
-  Symbols:   620
-  CStrings:  186
+  Functions: 441
+  Symbols:   632
+  CStrings:  190
Symbols:
+ -[ComputeSafeguardsManagingClient addBoostWatchForPid:name:reason:error:]
+ -[ComputeSafeguardsManagingClient getBoostObservationsForPid:error:]
+ -[ComputeSafeguardsManagingClient removeBoostWatchForPid:reason:error:]
+ -[ComputeSafeguardsManagingClient resetBoostCountersForPid:error:]
+ GCC_except_table204
+ GCC_except_table207
+ GCC_except_table210
+ GCC_except_table213
+ ___66-[ComputeSafeguardsManagingClient resetBoostCountersForPid:error:]_block_invoke
+ ___68-[ComputeSafeguardsManagingClient getBoostObservationsForPid:error:]_block_invoke
+ ___71-[ComputeSafeguardsManagingClient removeBoostWatchForPid:reason:error:]_block_invoke
+ ___73-[ComputeSafeguardsManagingClient addBoostWatchForPid:name:reason:error:]_block_invoke
CStrings:
+ "addBoostWatchForPid: XPC error %@"
+ "getBoostObservationsForPid: XPC error %@"
+ "removeBoostWatchForPid: XPC error %@"
+ "resetBoostCountersForPid: XPC error %@"
```
