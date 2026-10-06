## HID

> `/System/Library/PrivateFrameworks/HID.framework/HID`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13464` | `0x134cc` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x968` | `0x998` | **`+0x30`** |
| `__DATA.__data` | `0x19f0` | `0x19e0` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x150` | `0x158` | **`+0x8`** |

### Other Changes

```diff

-2353.0.0.0.1
+2360.0.2.0.0

-  Functions: 977
-  Symbols:   1589
+  Functions: 978
+  Symbols:   1586
Symbols:
+ OBJC_IVAR_$_HIDEventService._service
+ __IOHIDServiceCreateVirtualNoInit
+ __IOHIDServiceInitVirtual
+ ___HIDVirtualServiceLoadDelegate
+ ___block_descriptor_48_e5_v8?0l
- _IOHIDSessionGetEventSystem
- __IOHIDServiceCreateVirtual
- __IOHIDServiceGetOwner
- ___block_descriptor_40_e5_v8?0l
- _delegateObjectKey
- _objc_getAssociatedObject
- _objc_setAssociatedObject
- _virtualEventServiceIdentifierKey
```
