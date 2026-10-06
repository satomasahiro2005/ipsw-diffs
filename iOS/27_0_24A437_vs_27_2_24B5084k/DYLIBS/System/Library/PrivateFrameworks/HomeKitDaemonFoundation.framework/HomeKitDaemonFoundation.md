## HomeKitDaemonFoundation

> `/System/Library/PrivateFrameworks/HomeKitDaemonFoundation.framework/HomeKitDaemonFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7b834` | `0x7c600` | **`+0xdcc`** |
| `__TEXT.__oslogstring` | `0x10ca` | `0x112a` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x29b0` | `0x29c8` | **`+0x18`** |
| `__DATA_CONST.__const` | `0xc0` | `0xd0` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x684c` | `0x6854` | **`+0x8`** |
| `__TEXT.__swift5_reflstr` | `0x1417` | `0x1413` | **`-0x4`** |

### Other Changes

```diff

-1493.1.5.1.1
+1514.0.0.0.1

+  - /usr/lib/swift/libswiftAccelerate.dylib

+  - /usr/lib/swift/libswiftIntents.dylib

-  Functions: 3715
-  Symbols:   1029
-  CStrings:  237
+  Functions: 3718
+  Symbols:   1033
+  CStrings:  239
Symbols:
+ __swift_FORCE_LOAD_$_swiftAccelerate
+ __swift_FORCE_LOAD_$_swiftAccelerate_$_HomeKitDaemonFoundation
+ __swift_FORCE_LOAD_$_swiftIntents
+ __swift_FORCE_LOAD_$_swiftIntents_$_HomeKitDaemonFoundation
+ _objc_retain_x26
- _objc_retain_x24
CStrings:
+ "Cannot send RVC home while %s"
+ "operationalStateCluster.pause failed with error: %@"
```
