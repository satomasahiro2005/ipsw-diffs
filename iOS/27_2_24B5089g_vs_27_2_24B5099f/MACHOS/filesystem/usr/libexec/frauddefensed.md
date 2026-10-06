## frauddefensed

> `/usr/libexec/frauddefensed`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10cf64` | `0x10e7f4` | **`+0x1890`** |
| `__DATA_CONST.__const` | `0x9d90` | `0xa180` | **`+0x3f0`** |
| `__DATA.__bss` | `0xee40` | `0xf1c0` | **`+0x380`** |
| `__TEXT.__eh_frame` | `0xcda8` | `0xd120` | **`+0x378`** |
| `__TEXT.__const` | `0xcb98` | `0xce18` | **`+0x280`** |
| `__TEXT.__cstring` | `0xa17c` | `0xa35c` | **`+0x1e0`** |
| `__TEXT.__swift5_capture` | `0xbc0` | `0xd10` | **`+0x150`** |
| `__DATA.__objc_const` | `0x2140` | `0x2040` | **`-0x100`** |
| `__TEXT.__swift5_fieldmd` | `0x4d0c` | `0x4de8` | **`+0xdc`** |
| `__DATA.__data` | `0x54c0` | `0x53f0` | **`-0xd0`** |
| `__TEXT.__swift_as_cont` | `0xc1c` | `0xb58` | **`-0xc4`** |
| `__TEXT.__unwind_info` | `0x45c0` | `0x4628` | **`+0x68`** |
| `__TEXT.__swift5_typeref` | `0x27d4` | `0x2832` | **`+0x5e`** |
| `__TEXT.__constg_swiftt` | `0x32a4` | `0x3248` | **`-0x5c`** |
| `__TEXT.__objc_classname` | `0x82d` | `0x7dd` | **`-0x50`** |
| `__TEXT.__swift_as_ret` | `0x5c0` | `0x570` | **`-0x50`** |
| `__TEXT.__auth_stubs` | `0x25e0` | `0x25a0` | **`-0x40`** |
| `__TEXT.__swift_as_entry` | `0x390` | `0x368` | **`-0x28`** |
| `__DATA_CONST.__auth_got` | `0x12f8` | `0x12d8` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x35c5` | `0x35e5` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x82c` | `0x848` | **`+0x1c`** |
| `__TEXT.__swift5_assocty` | `0x4a8` | `0x4c0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x670` | `0x680` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x16d2` | `0x16c2` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x8c0` | `0x8c8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x128` | `0x120` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x418` | `0x41c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-104.0.0.0.0
+106.0.0.0.0

-  Functions: 4567
-  Symbols:   949
-  CStrings:  1223
+  Functions: 4572
+  Symbols:   946
+  CStrings:  1229
Symbols:
+ _$s10Foundation8URLErrorVAA21_BridgedStoredNSErrorAAMc
+ _$s10Foundation8URLErrorVMa
+ _$s10Foundation8URLErrorVs5ErrorAAMc
+ _swift_retain_x1
- _$sScCMa
- _$sScTss5NeverORszABRs_rlE17checkCancellationyyKFZ
- _$sScTss5NeverORszABRs_rlE5sleep5until9tolerance5clocky7InstantQyd___8DurationQyd__Sgqd__tYaKs5ClockRd__lFZ
- _$sScTss5NeverORszABRs_rlE5sleep5until9tolerance5clocky7InstantQyd___8DurationQyd__Sgqd__tYaKs5ClockRd__lFZTu
- _$sScg9cancelAllyyF
- _$ss15ContinuousClockV7InstantV3nowADvgZ
- _$ss15ContinuousClockV7InstantV8advanced2byADs8DurationV_tF
CStrings:
+ "Applied look-up scheme to handle. { scheme="
+ "Failed to decode report. { error="
+ "Failed to serialize report. { error="
+ "Failed to setup signature analysis decisioning component. { error="
+ "Handle already carries a look-up scheme."
+ "Operation failed. { error="
+ "Operation was cancelled."
+ "Request handling failed. { error="
+ "Request handling timed out."
+ "Request handling timed out. { timeout="
+ "callerCallDirectoryLabel"
+ "callerLiveLookupLabel"
+ "callerMapKitPlaceLookup"
+ "performWithTimeout(of:timerDidFinish:_:)"
- "Operation timed out."
- "_TtC13frauddefensedP33_0198525CB4AEBBD0F3388E1C055BF9D38Executor"
- "callerDirectoryLabel"
- "callerLiveLookUpLabel"
- "callerMapKitPlaceLookUp"
- "shouldExecute"
- "value"
- "withTimeout(isolation:_:_:)"
```
