## DoNotDisturbServer

> `/System/Library/PrivateFrameworks/DoNotDisturbServer.framework/DoNotDisturbServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc2a34` | `0xc2e78` | **`+0x444`** |
| `__TEXT.__oslogstring` | `0x11900` | `0x119a0` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x2a38` | `0x2a50` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x4e08` | `0x4e18` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xf00` | `0xf08` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xab14` | `0xab1c` | **`+0x8`** |

### Other Changes

```diff

-508.0.0.0.0
+511.0.0.0.0

-  Functions: 3942
-  Symbols:   7238
-  CStrings:  2291
+  Functions: 3950
+  Symbols:   7242
+  CStrings:  2294
Symbols:
+ -[DNDSCoreDataBackingStore _purgeLegacyPersistentHistoryAtURL:model:]
+ GCC_except_table13
+ GCC_except_table9
+ _OBJC_CLASS_$_NSPersistentStoreCoordinator
+ ___69-[DNDSCoreDataBackingStore _purgeLegacyPersistentHistoryAtURL:model:]_block_invoke
- GCC_except_table11
CStrings:
+ "Legacy history purge: deleteHistory failed: %@"
+ "Legacy history purge: failed to open store with tracking on: %@"
+ "Legacy history purge: failed to remove store: %@"
```
