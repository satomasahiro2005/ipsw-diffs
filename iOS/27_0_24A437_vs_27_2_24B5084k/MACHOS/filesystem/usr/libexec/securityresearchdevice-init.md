## securityresearchdevice-init

> `/usr/libexec/securityresearchdevice-init`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f454` | `0x21778` | **`+0x2324`** |
| `__TEXT.__eh_frame` | `0x1dc8` | `0x2008` | **`+0x240`** |
| `__TEXT.__const` | `0x938` | `0x9b8` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x7b8` | `0x830` | **`+0x78`** |
| `__TEXT.__oslogstring` | `0x9bc` | `0xa2c` | **`+0x70`** |
| `__DATA.__data` | `0x538` | `0x568` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x588` | `0x5b0` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x1a4` | `0x1cc` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x178` | `0x19c` | **`+0x24`** |
| `__DATA_CONST.__auth_ptr` | `0x198` | `0x1b0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x208` | `0x220` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0xc8` | `0xdc` | **`+0x14`** |
| `__TEXT.__swift5_capture` | `0x44` | `0x54` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x21c` | `0x228` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x94` | `0xa0` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__cstring`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-274.0.8.0.0
+274.40.9.0.0

-  Functions: 391
-  Symbols:   389
-  CStrings:  134
+  Functions: 409
+  Symbols:   395
+  CStrings:  135
Symbols:
+ _$sScP8rawValues5UInt8Vvg
+ _$sScPMa
+ _$sScS10makeStream2of15bufferingPolicyScSyxG6stream_ScS12ContinuationVyx_G12continuationtxm_AG09BufferingE0Oyx__GtFZ
+ _$sScS12ContinuationV11YieldResultOMn
+ _$sScS12ContinuationV15BufferingPolicyO15bufferingNewestyADyx__GSicAFmlFWC
+ _$sScS12ContinuationV15BufferingPolicyOMn
+ _$sScS12ContinuationV5yieldAB11YieldResultOyyt__GyytRszlF
+ _$sScS12ContinuationVMn
+ _$sScS17makeAsyncIteratorScS0C0Vyx_GyF
+ _$sScS8IteratorV4next9isolationxSgScA_pSgYi_tYaF
+ _$sScS8IteratorV4next9isolationxSgScA_pSgYi_tYaFTu
+ _$sScS8IteratorVMn
+ _$sScT6cancelyyF
+ _$sScTss5NeverORszABRs_rlE11isCancelledSbvgZ
- _$sSo17OS_dispatch_groupC8DispatchE4waityyF
- _dispatch_group_create
- _dispatch_group_enter
- _dispatch_group_leave
- _swift_beginAccess
- _swift_endAccess
- _swift_release_x24
- _swift_retain_x24
CStrings:
+ "Personalize failed on iteration "
+ "device has already been through first unlock"
+ "failed to get lock state, treating as locked: %@"
+ "failed to register for lock status notification, proceeding without waiting"
+ "proceeding while device still appears before first unlock"
- "Personalize failed on iteration: "
- "device appears before first unlock even after notification"
- "failed to get lock state: %@"
- "failed to register for lock status notification"
```
