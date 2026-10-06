## SleepDaemon

> `/System/Library/PrivateFrameworks/SleepDaemon.framework/SleepDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x798e8` | `0x798b4` | **`-0x34`** |
| `__DATA_CONST.__const` | `0x20d0` | `0x20e8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2088` | `0x2080` | **`-0x8`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

+  - /usr/lib/swift/libswiftMetal.dylib
+  - /usr/lib/swift/libswiftOSLog.dylib

+  - /usr/lib/swift/libswiftsimd.dylib

-  Symbols:   5429
+  Symbols:   5435
Symbols:
+ __swift_FORCE_LOAD_$_swiftMetal
+ __swift_FORCE_LOAD_$_swiftMetal_$_SleepDaemon
+ __swift_FORCE_LOAD_$_swiftOSLog
+ __swift_FORCE_LOAD_$_swiftOSLog_$_SleepDaemon
+ __swift_FORCE_LOAD_$_swiftsimd
+ __swift_FORCE_LOAD_$_swiftsimd_$_SleepDaemon
```
