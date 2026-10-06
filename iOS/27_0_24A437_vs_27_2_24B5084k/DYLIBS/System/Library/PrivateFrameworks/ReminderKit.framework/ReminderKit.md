## ReminderKit

> `/System/Library/PrivateFrameworks/ReminderKit.framework/ReminderKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13bfac` | `0x13c148` | **`+0x19c`** |
| `__TEXT.__cstring` | `0xe51d` | `0xe5a3` | **`+0x86`** |
| `__AUTH_CONST.__cfstring` | `0xe660` | `0xe6a0` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x24820` | `0x24830` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x2a40` | `0x2a50` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x7bb0` | `0x7bb8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x15c10` | `0x15c18` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x6af0` | `0x6af8` | **`+0x8`** |

### Other Changes

```diff

-4046.11.0.0.0
+4076.0.0.0.0

-  Functions: 8808
-  Symbols:   14307
-  CStrings:  2973
+  Functions: 8809
+  Symbols:   14310
+  CStrings:  2975
Symbols:
+ -[REMAutoCategorizationActivity allReminderIDs]
+ _RDGrocerySectionCoalesceOperationAuthor
+ _RDStoreControllerCoalesceGrocerySectionsMigrationAuthor
Functions:
~ ___59+[REMChangeTracking internalTransactionAuthorKeysToExclude]_block_invoke : 544 -> 592
+ -[REMAutoCategorizationActivity allReminderIDs]
CStrings:
+ "com.apple.remindd.RDGrocerySectionCoalesceOperation.author"
+ "com.apple.remindd.RDStoreController.CoalesceGrocerySectionsMigrationAuthor"
```
