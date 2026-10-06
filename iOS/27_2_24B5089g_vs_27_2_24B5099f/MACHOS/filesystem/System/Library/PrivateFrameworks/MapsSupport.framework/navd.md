## navd

> `/System/Library/PrivateFrameworks/MapsSupport.framework/navd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4af70` | `0x4d4f4` | **`+0x2584`** |
| `__DATA_CONST.__const` | `0x36f8` | `0x38c0` | **`+0x1c8`** |
| `__TEXT.__oslogstring` | `0x5692` | `0x5812` | **`+0x180`** |
| `__TEXT.__eh_frame` | `0xf38` | `0x1058` | **`+0x120`** |
| `__TEXT.__const` | `0xc04` | `0xcc4` | **`+0xc0`** |
| `__DATA.__objc_data` | `0x1160` | `0x1210` | **`+0xb0`** |
| `__TEXT.__auth_stubs` | `0x1710` | `0x17b0` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x17c0` | `0x1850` | **`+0x90`** |
| `__TEXT.__swift5_capture` | `0x190` | `0x21c` | **`+0x8c`** |
| `__DATA.__bss` | `0xc30` | `0xcb0` | **`+0x80`** |
| `__DATA.__data` | `0x11c8` | `0x1238` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x5fe` | `0x652` | **`+0x54`** |
| `__DATA_CONST.__auth_got` | `0xba0` | `0xbf0` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x120` | `0x170` | **`+0x50`** |
| `__TEXT.__cstring` | `0x4f70` | `0x4fc0` | **`+0x50`** |
| `__DATA.__objc_const` | `0x6a90` | `0x6ad8` | **`+0x48`** |
| `__TEXT.__objc_methname` | `0xbdc5` | `0xbe0b` | **`+0x46`** |
| `__TEXT.__objc_methlist` | `0x3028` | `0x3068` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x7dc0` | `0x7e00` | **`+0x40`** |
| `__TEXT.__objc_classname` | `0x988` | `0x9b4` | **`+0x2c`** |
| `__DATA_CONST.__cfstring` | `0x29c0` | `0x29e0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x970` | `0x990` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0xfc` | `0x11c` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x28e1` | `0x28f4` | **`+0x13`** |
| `__DATA.__objc_selrefs` | `0x2ac8` | `0x2ad8` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x3b0` | `0x3c0` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x98` | `0xa8` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x74` | `0x80` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x1b0` | `0x1b8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x70` | `0x78` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x54` | `0x58` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`

### Other Changes

```diff

-2972.31.6.17.20
+2972.31.6.17.31

-  Functions: 1323
-  Symbols:   823
-  CStrings:  3360
+  Functions: 1362
+  Symbols:   837
+  CStrings:  3374
Symbols:
+ _$s8Dispatch0A13WorkItemFlagsVMa
+ _$s8Dispatch0A13WorkItemFlagsVMn
+ _$s8Dispatch0A13WorkItemFlagsVs10SetAlgebraAAMc
+ _$s8Dispatch0A3QoSV11unspecifiedACvgZ
+ _$s8Dispatch0A3QoSVMa
+ _$s8Dispatch0A4TimeV3nowACyFZ
+ _$s8Dispatch0A4TimeVMa
+ _$s8Dispatch1poiyAA0A4TimeVAD_SdtF
+ _$sSayxGSTsMc
+ _$sSo13os_log_type_ta0A0E5debugABvgZ
+ _$sSo17OS_dispatch_queueC8DispatchE10asyncAfter8deadline3qos5flags7executeyAC0D4TimeV_AC0D3QoSVAC0D13WorkItemFlagsVyyXBtF
+ _$sSo17OS_dispatch_queueC8DispatchE4mainABvgZ
+ _$ss10SetAlgebraPyxqd__ncSTRd__7ElementQyd__ACRtzlufCTj
+ _OBJC_CLASS_$_OS_dispatch_queue
+ _swift_retain_x24
- _swift_retain_x27
CStrings:
+ "AppIntents"
+ "Fetching current Parked Car from CR on navd bootup"
+ "No parked car available"
+ "ParkedCarDonationSeedRetryInterval"
+ "Registering query"
+ "Seed found a parked car on attempt %ld"
+ "Seed found no parked car after %ld attempts, clearing"
+ "Seed found no parked car on attempt %ld, retrying"
+ "Seeding parked car, attempt %ld"
+ "Starting NavdParkedCarDonationManager."
+ "_TtC4navd24NavdParkedCarQueryBridge"
+ "_startParkedCarDonationManagerIfUnlocked"
+ "registerQuery(routineManager:)"
+ "registerWithDonationManager:"
```
