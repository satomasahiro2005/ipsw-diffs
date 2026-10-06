## Pasteboard

> `/System/Library/PrivateFrameworks/Pasteboard.framework/Pasteboard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27d1c` | `0x27eac` | **`+0x190`** |
| `__AUTH_CONST.__objc_const` | `0x30c8` | `0x30f8` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x11e0` | `0x1200` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x22a0` | `0x22c0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1550` | `0x1568` | **`+0x18`** |
| `__TEXT.__cstring` | `0x1b97` | `0x1ba8` | **`+0x11`** |
| `__TEXT.__unwind_info` | `0xe68` | `0xe78` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1598` | `0x15a0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1ac` | `0x1b0` | **`+0x4`** |

### Other Changes

```diff

-9127.0.78.0.0
+9127.0.84.1.102

-  Functions: 1071
-  Symbols:   1812
-  CStrings:  313
+  Functions: 1075
+  Symbols:   1819
+  CStrings:  314
Symbols:
+ -[PBItemCollection itemQueue_shutdown]
+ -[PBSaveResponse initWithNotificationState:changeCount:sharingToken:removedItemUUIDs:]
+ -[PBSaveResponse removedItemUUIDs]
+ GCC_except_table114
+ GCC_except_table120
+ _OBJC_IVAR_$_PBSaveResponse._removedItemUUIDs
+ _PBItemQueueIsCurrentQueue
+ _PBItemQueueSpecificKey
+ _dispatch_get_specific
+ _dispatch_queue_set_specific
- GCC_except_table100
- GCC_except_table112
- GCC_except_table118
CStrings:
+ "\""
+ "removedItemUUIDs"
- "!"
```
