## proximitycontrold

> `/usr/libexec/proximitycontrold`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x265aec` | `0x2642e8` | **`-0x1804`** |
| `__TEXT.__oslogstring` | `0x7eae` | `0x7d0e` | **`-0x1a0`** |
| `__TEXT.__swift5_typeref` | `0xf156` | `0xf2ea` | **`+0x194`** |
| `__TEXT.__auth_stubs` | `0x3640` | `0x3570` | **`-0xd0`** |
| `__TEXT.__cstring` | `0x7d99` | `0x7d29` | **`-0x70`** |
| `__TEXT.__eh_frame` | `0x6704` | `0x6694` | **`-0x70`** |
| `__DATA_CONST.__auth_got` | `0x1b28` | `0x1ac0` | **`-0x68`** |
| `__TEXT.__unwind_info` | `0x6c30` | `0x6be8` | **`-0x48`** |
| `__TEXT.__const` | `0x21648` | `0x21618` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x15480` | `0x154a8` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x4220` | `0x4200` | **`-0x20`** |
| `__TEXT.__swift5_capture` | `0x347c` | `0x349c` | **`+0x20`** |
| `__DATA.__common` | `0x8a8` | `0x890` | **`-0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x1a60` | `0x1a50` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0xdf29` | `0xdf39` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x1da8` | `0x1db0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xea8` | `0xea0` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0xd7e4` | `0xd7ec` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-376.0.6.0.0
+376.0.10.0.0

-  Functions: 10340
-  Symbols:   1646
-  CStrings:  4184
+  Functions: 10330
+  Symbols:   1631
+  CStrings:  4174
Symbols:
+ _RPOptionStatusFlags
- _$s15Synchronization5MutexVMa
- _$sSh5IndexV8_asCocoas02__C3SetVAAVvM
- _$sSh5IndexVMn
- _$sSy10FoundationE15appendingFormatySSqd___s7CVarArg_pdtSyRd__lF
- _$ss10__CocoaSetV10startIndexAB0D0Vvg
- _$ss10__CocoaSetV5IndexV16handleBitPatternSuvg
- _$ss10__CocoaSetV5IndexV3ages5Int32Vvg
- _$ss10__CocoaSetV5IndexV7elementyXlvg
- _$ss10__CocoaSetV7element2atyXlAB5IndexV_tF
- _$ss10__CocoaSetV9formIndex5after8isUniqueyAB0D0Vz_SbtF
- _NSSelectorFromString
- __xpc_event_key_name
- _objc_retainAutorelease
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
- _xpc_dictionary_get_string
CStrings:
- "### RPCompanionLinkDevice: No selector for 'publicBluetoothAddress'"
- "%s: key=%s"
- "(Non-communal, r1CapableNearby="
- "CBDevices changed, count=%ld"
- "No edge for state input: %s, state=%s"
- "Received xpc stream event: %s"
- "Sending state input %s"
- "Should start ranging = %{bool}d %s"
- "Should start ranging = %{bool}d (Communal, candidates=%ld), allowGuests=%{bool}d"
- "State after receiving %s: %s"
```
