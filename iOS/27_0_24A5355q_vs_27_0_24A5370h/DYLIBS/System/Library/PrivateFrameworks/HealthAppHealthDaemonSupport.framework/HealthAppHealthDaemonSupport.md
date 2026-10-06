## HealthAppHealthDaemonSupport

> `/System/Library/PrivateFrameworks/HealthAppHealthDaemonSupport.framework/HealthAppHealthDaemonSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11ec4` | `0x11ef0` | **`+0x2c`** |
| `__DATA_CONST.__const` | `0x88` | `0xa0` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x550` | `0x548` | **`-0x8`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

+  - /usr/lib/swift/libswiftMetal.dylib
+  - /usr/lib/swift/libswiftOSLog.dylib

+  - /usr/lib/swift/libswiftsimd.dylib

-  Symbols:   332
+  Symbols:   337
Symbols:
+ __swift_FORCE_LOAD_$_swiftMetal
+ __swift_FORCE_LOAD_$_swiftMetal_$_HealthAppHealthDaemonSupport
+ __swift_FORCE_LOAD_$_swiftOSLog
+ __swift_FORCE_LOAD_$_swiftOSLog_$_HealthAppHealthDaemonSupport
+ __swift_FORCE_LOAD_$_swiftsimd
+ __swift_FORCE_LOAD_$_swiftsimd_$_HealthAppHealthDaemonSupport
- _swift_retain_x25
Functions:
~ sub_227fb2548 -> sub_229946608 : 140 -> 152
~ sub_227fb5620 -> sub_2299496ec : 280 -> 276
~ sub_227fb8114 -> sub_22994c1dc : 1224 -> 1240
~ sub_227fb8864 -> sub_22994c93c : 1228 -> 1244
~ sub_227fbda20 -> sub_229951b08 : 408 -> 420
~ sub_227fbdd6c -> sub_229951e60 : 552 -> 540
~ sub_227fc1dc4 -> sub_229955eac : 328 -> 324
~ ___swift_closure_destructor.11Tm : 136 -> 144
```
