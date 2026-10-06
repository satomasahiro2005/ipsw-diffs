## WatchListKit

> `/System/Library/PrivateFrameworks/WatchListKit.framework/WatchListKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x19a0` | `0x1810` | **`-0x190`** |
| `__DATA_DIRTY.__objc_data` | `0x1c20` | `0x1db0` | **`+0x190`** |
| `__TEXT.__text` | `0x66b84` | `0x66ba0` | **`+0x1c`** |

### Other Changes

```diff

-952.0.0.0.0
+952.0.1.0.0

-  Functions: 2785
-  Symbols:   5615
+  Functions: 2784
+  Symbols:   5616
Symbols:
+ _dispatch_block_create_with_qos_class
Functions:
~ +[WLKAppLibrary defaultAppLibrary] : 68 -> 116
- +[WLKLocationManager defaultLocationManager].cold.1
```
