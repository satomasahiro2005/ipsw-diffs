## fmflocatord

> `/usr/libexec/fmflocatord`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38450` | `0x38624` | **`+0x1d4`** |
| `__TEXT.__oslogstring` | `0x42c4` | `0x4384` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x2049` | `0x2071` | **`+0x28`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-101.30.3.1.1
+103.30.6.7.1

-  Functions: 1554
+  Functions: 1557

-  CStrings:  2602
+  CStrings:  2606
CStrings:
+ "TrueMe"
+ "checkIfThisDeviceIsBeingUsedToShareLocation: error: %@"
+ "checkIfThisDeviceIsBeingUsedToShareLocation: isMeOrCompanionToMe=%d"
+ "checkIfThisDeviceIsBeingUsedToShareLocation: not a location sharing device"
```
