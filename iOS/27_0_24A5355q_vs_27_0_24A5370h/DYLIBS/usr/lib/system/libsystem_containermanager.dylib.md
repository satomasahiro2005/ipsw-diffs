## libsystem_containermanager.dylib

> `/usr/lib/system/libsystem_containermanager.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f870` | `0x2ffc4` | **`+0x754`** |
| `__TEXT.__oslogstring` | `0x56e5` | `0x5939` | **`+0x254`** |
| `__DATA_CONST.__const` | `0x1cb8` | `0x1d08` | **`+0x50`** |
| `__TEXT.__cstring` | `0x3c1b` | `0x3c41` | **`+0x26`** |
| `__TEXT.__unwind_info` | `0x6f8` | `0x700` | **`+0x8`** |

### Other Changes

```diff

-826.0.0.0.1
+833.0.0.0.0

-  Functions: 621
-  Symbols:   1001
-  CStrings:  895
+  Functions: 626
+  Symbols:   1008
+  CStrings:  904
Symbols:
+ _CONTAINER_TRAVERSE_ATTR_ENTRY_LENGTH_FIELD_SIZE
+ ___WAITING_TO_RETRY_CONTAINER_FETCH_FROM_CONTAINER_MANAGER__
+ ___container_notify_register_generation_handler_block_invoke
+ ___container_notify_register_generation_handler_block_invoke_2
+ _container_notify_cancel_generation_handler
+ _container_notify_register_generation_handler
+ _sleep
CStrings:
+ "%s: SPI MISUSE: handler block cannot be NULL"
+ "@(#)VERSION:Container Manager: Jun  9 2026 15:46:05; MobileContainerManager_system-833~119/arm64e"
+ "Failed to cancel generation dispatch handler; token = %d, status = %u"
+ "Failed to get state in generation dispatch handler; token = %d, status = %u"
+ "Failed to register generation dispatch handler; container_class = %llu, status = %u"
+ "Generation dispatch handler fired; token = %d, generation = %llu, container_class = %llu"
+ "Insufficient room (%zu bytes) to read length of entry %hu in [%s]; need %zu"
+ "Insufficient room (%zu bytes) to read length of skip entry %hu in [%s]; need %zu"
+ "Registered generation dispatch handler; token = %d, container_class = %llu"
+ "container_notify_register_generation_handler"
- "@(#)VERSION:Container Manager: May 22 2026 05:10:36; MobileContainerManager_system-826.0.0.0.1~39/arm64e"
```
