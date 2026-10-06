## CoreData

> `/System/Library/Frameworks/CoreData.framework/CoreData`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3318bc` | `0x331c7c` | **`+0x3c0`** |
| `__TEXT.__cstring` | `0x3bf73` | `0x3bfde` | **`+0x6b`** |
| `__TEXT.__objc_methlist` | `0x108f8` | `0x10958` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x36900` | `0x368af` | **`-0x51`** |
| `__DATA_CONST.__const` | `0x4c38` | `0x4c88` | **`+0x50`** |
| `__AUTH_CONST.__objc_dictobj` | `0x2698` | `0x26c0` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x1fdc0` | `0x1fde0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x6258` | `0x6278` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x25df8` | `0x25e10` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x8860` | `0x8870` | **`+0x10`** |

### Other Changes

```diff

-1629.1.0.0.0
+1632.0.0.0.0

-  Functions: 9344
-  Symbols:   17622
-  CStrings:  8340
+  Functions: 9351
+  Symbols:   17632
+  CStrings:  8341
Symbols:
+ -[NSCloudKitMirroringDelegate newActivityWithIdentifier:earliestStartDate:andVoucher:]
+ -[NSManagedObjectContext(_NSInternalAdditions) returnFaultErrors]
+ -[NSManagedObjectContext(_NSInternalAdditions) setReturnFaultErrors:]
+ -[NSPersistentCloudKitContainerActivity copyWithZone:]
+ -[NSPersistentCloudKitContainerActivity initAsCopyOfActivity:]
+ -[NSPersistentCloudKitContainerEvent initWithCKEvent:originalError:]
+ -[NSPersistentCloudKitContainerEventActivity copyWithZone:]
+ -[NSPersistentCloudKitContainerSetupPhaseActivity copyWithZone:]
+ GCC_except_table244
+ GCC_except_table245
+ GCC_except_table249
+ GCC_except_table262
+ GCC_except_table270
+ GCC_except_table291
+ GCC_except_table292
+ GCC_except_table299
+ GCC_except_table304
+ GCC_except_table305
+ GCC_except_table314
+ GCC_except_table319
+ __OBJC_CLASS_PROTOCOLS_$_NSPersistentCloudKitContainerActivity
+ ___block_descriptor_72_e8_32o40o48o56r_e5_v8?0ls32l8s40l8r56l8s48l8
+ ___block_descriptor_80_e8_32o40o48o56o64r_e5_v8?0ls32l8s40l8s48l8r64l8s56l8
- -[NSCloudKitMirroringDelegate newActivityWithIdentifier:andVoucher:]
- GCC_except_table242
- GCC_except_table243
- GCC_except_table247
- GCC_except_table260
- GCC_except_table268
- GCC_except_table289
- GCC_except_table290
- GCC_except_table296
- GCC_except_table297
- GCC_except_table303
- GCC_except_table312
- GCC_except_table317
CStrings:
+ "CoreData: error: Unhandled error (%@, %ld) occurred during faulting and was ignored: %@\n"
+ "Unhandled error (%@, %ld) occurred during faulting and was ignored: %@"
+ "searchMapping is missing or invalid"
- "CoreData: Unhandled error (%@, %ld) occurred during faulting and was ignored: %@"
- "CoreData: fault: Unhandled error (%@, %ld) occurred during faulting and was ignored: %@\n"
```
