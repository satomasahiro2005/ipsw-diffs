## libswift_Concurrency.dylib

> `/usr/lib/swift/libswift_Concurrency.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x75e1c` | `0x75dec` | **`-0x30`** |
| `__DATA.__bss` | `0x43a0` | `0x4380` | **`-0x20`** |
| `__DATA_DIRTY.__data` | `0x470` | `0x468` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x2c18` | `0x2c10` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-6.4.0.34.1
+6.4.2.1.7

-  Functions: 3046
-  Symbols:   5829
+  Functions: 3045
+  Symbols:   5827
Symbols:
- __ZL19dispatchEnqueueFunc
- __ZL29initializeDispatchEnqueueFuncP16dispatch_queue_sPv11qos_class_t
Functions:
~ _swift_dispatchEnqueueGlobal : 180 -> 172
~ _swift_dispatchEnqueueMain : 32 -> 24
- __ZL29initializeDispatchEnqueueFuncP16dispatch_queue_sPv11qos_class_t
~ _swift_task_enqueueOnDispatchQueue : 32 -> 24
CStrings:
+ "Initialized count must be in 0 ... unsafeUninitializedCapacity."
- "Initialized count set to greater than specified capacity."
```
