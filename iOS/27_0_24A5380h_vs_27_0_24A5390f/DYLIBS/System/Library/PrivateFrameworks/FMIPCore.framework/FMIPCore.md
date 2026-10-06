## FMIPCore

> `/System/Library/PrivateFrameworks/FMIPCore.framework/FMIPCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c79ac` | `0x1d052c` | **`+0x8b80`** |
| `__TEXT.__eh_frame` | `0x4428` | `0x49e8` | **`+0x5c0`** |
| `__AUTH_CONST.__const` | `0x12c91` | `0x12f59` | **`+0x2c8`** |
| `__TEXT.__const` | `0x13cbc` | `0x13ebc` | **`+0x200`** |
| `__AUTH_CONST.__objc_const` | `0xf0c0` | `0xf250` | **`+0x190`** |
| `__AUTH.__data` | `0x4e38` | `0x4fb8` | **`+0x180`** |
| `__TEXT.__unwind_info` | `0x4e38` | `0x4f78` | **`+0x140`** |
| `__TEXT.__swift5_typeref` | `0x42c1` | `0x43c9` | **`+0x108`** |
| `__TEXT.__constg_swiftt` | `0x690c` | `0x69e8` | **`+0xdc`** |
| `__TEXT.__swift5_capture` | `0x2794` | `0x286c` | **`+0xd8`** |
| `__AUTH_CONST.__auth_got` | `0x1408` | `0x14b0` | **`+0xa8`** |
| `__DATA.__data` | `0x1a58` | `0x1af0` | **`+0x98`** |
| `__TEXT.__cstring` | `0x54cc` | `0x555c` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x607c` | `0x6100` | **`+0x84`** |
| `__DATA.__bss` | `0x13780` | `0x13800` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0xa9f0` | `0xaa60` | **`+0x70`** |
| `__TEXT.__swift_as_cont` | `0x120` | `0x184` | **`+0x64`** |
| `__DATA_DIRTY.__data` | `0x5998` | `0x59d8` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x15d8` | `0x15f8` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x5551` | `0x5571` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x88` | `0xa4` | **`+0x1c`** |
| `__TEXT.__swift5_builtin` | `0x17c` | `0x190` | **`+0x14`** |
| `__TEXT.__swift5_mpenum` | `0x1c` | `0x30` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x54` | `0x68` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x350` | `0x360` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x5f4` | `0x600` | **`+0xc`** |
| `__TEXT.__swift5_proto` | `0xeb4` | `0xeb8` | **`+0x4`** |

### Other Changes

```diff

-470.30.6.14.10
+470.30.6.14.19

+  - /System/Library/PrivateFrameworks/FindMySecureEnvironment.framework/FindMySecureEnvironment

-  Functions: 8834
-  Symbols:   419
-  CStrings:  1418
+  Functions: 8929
+  Symbols:   424
+  CStrings:  1422
Symbols:
+ _OBJC_CLASS_$_SPBeaconManagerSimpleBeaconUpdateInterface
+ _OBJC_CLASS_$_SPInternalSimpleBeacon
+ _swift_task_addCancellationHandler
+ _swift_task_future_wait_throwing
+ _swift_task_removeCancellationHandler
CStrings:
+ "FMEnableSecureEnvironment"
+ "FMIPManager: triggering targeted location refresh for %ld newly-added beacon(s): %{private,mask.hash}s"
+ "fetch(deviceUDID:timeout:)"
+ "https://findmy-asset.corp.apple.com/fmipmobile/deviceImages-4.0/"
```
