## ActivityBridgeSetup

> `/System/Library/NanoPreferenceBundles/SetupBundles/ActivityBridgeSetup.bundle/ActivityBridgeSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x548f4` | `0x551a8` | **`+0x8b4`** |
| `__TEXT.__oslogstring` | `0xc20` | `0xc80` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x22b0` | `0x22d8` | **`+0x28`** |
| `__TEXT.__const` | `0x3510` | `0x34f0` | **`-0x20`** |
| `__DATA.__data` | `0x2170` | `0x2188` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1288` | `0x12a0` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x4bc` | `0x4cc` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x8f8` | `0x900` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1328` | `0x1330` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methname`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2027.0.123.1.9
+2027.0.123.1.10

-  Functions: 1610
+  Functions: 1617

-  CStrings:  1195
+  CStrings:  1196
CStrings:
+ "%s holdBeforeDisplaying: isTinkerPairing %{bool}d isTinkerHealthSharingEnabled %{bool}d"
```
