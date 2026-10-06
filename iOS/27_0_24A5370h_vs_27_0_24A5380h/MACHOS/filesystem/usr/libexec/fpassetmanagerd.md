## fpassetmanagerd

> `/usr/libexec/fpassetmanagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d230` | `0x1e0ac` | **`+0xe7c`** |
| `__TEXT.__oslogstring` | `0x1818` | `0x1978` | **`+0x160`** |
| `__TEXT.__eh_frame` | `0x8ec` | `0xa04` | **`+0x118`** |
| `__TEXT.__auth_stubs` | `0xe00` | `0xe90` | **`+0x90`** |
| `__DATA_CONST.__const` | `0x8c8` | `0x918` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x708` | `0x750` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x420` | `0x460` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x1a0` | `0x1d8` | **`+0x38`** |
| `__TEXT.__cstring` | `0x96f` | `0x98f` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x5c8` | `0x5e8` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x420` | `0x440` | **`+0x20`** |
| `__DATA.__data` | `0x520` | `0x530` | **`+0x10`** |
| `__TEXT.__const` | `0x5f8` | `0x608` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x24` | `0x34` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x1d8` | `0x1e0` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x28` | `0x30` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x24` | `0x28` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1.3.0.0.0
+1.5.0.0.0

-  Functions: 308
-  Symbols:   336
-  CStrings:  277
+  Functions: 322
+  Symbols:   350
+  CStrings:  285
Symbols:
+ _$sScT6cancelyyF
+ _$sScTss5NeverORszABRs_rlE11isCancelledSbvgZ
+ _$sScTss5NeverORszABRs_rlE17checkCancellationyyKFZ
+ _$ss15ContinuousClockV7InstantVMa
+ _$ss15ContinuousClockV7InstantVs0C8ProtocolsMc
+ _$ss15ContinuousClockVMa
+ _$ss15ContinuousClockVs0B0sMc
+ _$ss15InstantProtocolP8advanced2byx8DurationQz_tFTj
+ _$ss5ClockP3now7InstantQzvgTj
+ _$ss5ClockP5sleep5until9tolerancey7InstantQz_8DurationQzSgtYaKFTj
+ _$ss5ClockP5sleep5until9tolerancey7InstantQz_8DurationQzSgtYaKFTjTu
+ _$ss5ClockPss010ContinuousA0VRszrlE10continuousADvgZ
+ _$ss5NeverON
+ _$ss5NeverOs5ErrorsWP
CStrings:
+ "Boot refresh cancelled due to expiration"
+ "HasBGSTExpiryTesting"
+ "HasBGSTExpiryTesting has been set to true. Sleeping for 1800 seconds"
+ "HasBGSTExpiryTesting has not been set to true"
+ "On-boot task expired by system, cancelling async work"
+ "Periodic refresh cancelled due to expiration"
+ "Periodic task expired by system, cancelling async work"
+ "setExpirationHandler:"
```
