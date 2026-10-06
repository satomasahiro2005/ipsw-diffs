## FindMyDeviceSharedConfigurationXPCService

> `/System/Library/PrivateFrameworks/FindMyDevice.framework/XPCServices/FindMyDeviceSharedConfigurationXPCService.xpc/FindMyDeviceSharedConfigurationXPCService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bc50` | `0x1d320` | **`+0x16d0`** |
| `__TEXT.__eh_frame` | `0x6d8` | `0xc80` | **`+0x5a8`** |
| `__TEXT.__const` | `0x968` | `0xaf8` | **`+0x190`** |
| `__TEXT.__unwind_info` | `0x480` | `0x5e8` | **`+0x168`** |
| `__DATA_CONST.__got` | `0x268` | `0x2e0` | **`+0x78`** |
| `__TEXT.__swift5_typeref` | `0x51c` | `0x58a` | **`+0x6e`** |
| `__TEXT.__oslogstring` | `0x9b2` | `0xa10` | **`+0x5e`** |
| `__TEXT.__cstring` | `0x454` | `0x4b1` | **`+0x5d`** |
| `__TEXT.__constg_swiftt` | `0x188` | `0x1e0` | **`+0x58`** |
| `__TEXT.__auth_stubs` | `0xef0` | `0xf40` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x5c` | `0xac` | **`+0x50`** |
| `__TEXT.__swift_as_ret` | `0x24` | `0x5c` | **`+0x38`** |
| `__TEXT.__swift_as_entry` | `0x20` | `0x54` | **`+0x34`** |
| `__TEXT.__swift5_capture` | `0x328` | `0x358` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x1bc` | `0x1ec` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x780` | `0x7a8` | **`+0x28`** |
| `__DATA_CONST.__const` | `0xa00` | `0xa28` | **`+0x28`** |
| `__DATA.__data` | `0x450` | `0x470` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x2d8` | `0x2e0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x24` | `0x2c` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0x2df` | `0x2e5` | **`+0x6`** |
| `__TEXT.__swift5_proto` | `0x4c` | `0x50` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `—` | `0x4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-482.31.6.16.11
+482.31.6.16.16

-  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 380
-  Symbols:   175
-  CStrings:  229
+  Functions: 424
+  Symbols:   171
+  CStrings:  232
Symbols:
+ _swift_arrayInitWithCopy
+ _swift_retain_x22
- _objc_retain_x27
- _os_unfair_lock_lock
- _os_unfair_lock_unlock
- _swift_retain_x23
- _swift_retain_x24
- _swift_retain_x26
CStrings:
+ "getTheftAndLossCoverage(serialNumber:)"
+ "getTheftAndLossCoverage(udid:)"
+ "rdar://187622475 fix build: accepted XPC connection from pid %d"
+ "rdar://187622475: FindMyBase absent -> plain Task fallback"
+ "rdar://187622475: FindMyBase present -> Transaction.asyncTask"
+ "rdar://187622475: getTheftAndLossCoverage(serialNumber:) body entered"
- "Failed to get device coverage for serialNumber: %s"
- "Failed to get device coverage for serialNumber: %s, error: %@"
- "Found device coverage: %{bool}d, for serialNumber: %s"
```
