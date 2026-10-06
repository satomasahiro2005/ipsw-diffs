## DataCollector

> `/System/Library/PrivateFrameworks/DataCollector.framework/DataCollector`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2fccc` | `0x2ff70` | **`+0x2a4`** |
| `__AUTH_CONST.__const` | `0x2391` | `0x2419` | **`+0x88`** |
| `__DATA_DIRTY.__bss` | `0x580` | `0x600` | **`+0x80`** |
| `__TEXT.__const` | `0x2e00` | `0x2e50` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x108c` | `0x10c0` | **`+0x34`** |
| `__TEXT.__eh_frame` | `0x2518` | `0x24f0` | **`-0x28`** |
| `__TEXT.__constg_swiftt` | `0x13d4` | `0x13f8` | **`+0x24`** |
| `__AUTH_CONST.__objc_const` | `0x1450` | `0x1470` | **`+0x20`** |
| `__DATA.__data` | `0xa30` | `0xa10` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0xf7a` | `0xf9a` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0xd08` | `0xd18` | **`+0x10`** |
| `__DATA.__common` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x1137` | `0x113d` | **`+0x6`** |
| `__TEXT.__swift5_proto` | `0x1b0` | `0x1b4` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x108` | `0x10c` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x18c` | `0x190` | **`+0x4`** |

### Other Changes

```diff

-3600.15.1.0.0
+3600.15.3.0.0

-  Functions: 1675
-  Symbols:   772
+  Functions: 1678
+  Symbols:   768
Symbols:
+ ___swift_closure_destructor.10Tm
+ _symbolic _____ 13DataCollector13ServiceConfigV
+ _symbolic _____yScCyx______pGSgG 15Synchronization5MutexVAARi_zrlE s5ErrorP
+ _symbolic _____y_____yx_GG 15Synchronization5MutexVAARi_zrlE 13DataCollector9Connector33_7464FF206B3FBAD9AAA66F8F184B0F6DLLC5StateV
+ _type_layout_string 13DataCollector13ServiceConfigV
- ___swift_closure_destructor.12Tm
- _get_type_metadata 15Synchronization5MutexVy13DataCollector15UploaderContext_pSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVy19UnilogCommonLibrary6ClientOG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDy10Foundation3URLV13DataCollector18AttestedRPCChannel_pGG noncopyable
- _get_type_metadata 15Synchronization6AtomicVySbG noncopyable
- _get_type_metadata 15Synchronization6AtomicVySuG noncopyable
- _get_type_metadata s8SendableRzl15Synchronization5MutexVy13DataCollector9Connector33_7464FF206B3FBAD9AAA66F8F184B0F6DLLC5StateVyx_GG noncopyable
- _get_type_metadata s8SendableRzl15Synchronization5MutexVyScCyxs5Error_pGSgG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
```
