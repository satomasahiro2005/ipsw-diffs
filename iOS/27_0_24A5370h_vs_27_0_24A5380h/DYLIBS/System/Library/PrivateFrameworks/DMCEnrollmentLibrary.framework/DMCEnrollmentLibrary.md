## DMCEnrollmentLibrary

> `/System/Library/PrivateFrameworks/DMCEnrollmentLibrary.framework/DMCEnrollmentLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b834` | `0x2bb98` | **`+0x364`** |
| `__TEXT.__oslogstring` | `0x469e` | `0x46f3` | **`+0x55`** |
| `__TEXT.__cstring` | `0x270d` | `0x2753` | **`+0x46`** |
| `__TEXT.__gcc_except_tab` | `0x84c` | `0x86c` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0xb10` | `0xb28` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x1d0c` | `0x1d1c` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x968` | `0x978` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1350` | `0x1358` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x550` | `0x558` | **`+0x8`** |

### Other Changes

```diff

-107.0.0.0.0
+111.0.0.0.0

-  Functions: 848
-  Symbols:   1484
-  CStrings:  614
+  Functions: 851
+  Symbols:   1488
+  CStrings:  616
Symbols:
+ -[DMCMigrationFlowController _ensureNetworkConnection]
+ GCC_except_table14
+ ___54-[DMCMigrationFlowController _ensureNetworkConnection]_block_invoke
+ ___54-[DMCMigrationFlowController _ensureNetworkConnection]_block_invoke_2
CStrings:
+ "-[DMCMigrationFlowController _ensureNetworkConnection]_block_invoke_2"
+ "ensureNetworkConnection returned error, proceeding with migration anyway: %{public}@"
```
