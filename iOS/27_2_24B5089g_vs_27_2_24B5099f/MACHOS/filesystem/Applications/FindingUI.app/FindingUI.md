## FindingUI

> `/Applications/FindingUI.app/FindingUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x60edc` | `0x61964` | **`+0xa88`** |
| `__DATA.__bss` | `0x3380` | `0x3500` | **`+0x180`** |
| `__DATA_CONST.__const` | `0x2268` | `0x2370` | **`+0x108`** |
| `__TEXT.__const` | `0x2bf4` | `0x2c94` | **`+0xa0`** |
| `__TEXT.__swift5_capture` | `0x840` | `0x8c8` | **`+0x88`** |
| `__TEXT.__objc_methname` | `0x3139` | `0x31b9` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x1d6a` | `0x1dda` | **`+0x70`** |
| `__TEXT.__objc_stubs` | `0xf60` | `0xfc0` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0xeb0` | `0xe8c` | **`-0x24`** |
| `__TEXT.__cstring` | `0x8f4` | `0x8d4` | **`-0x20`** |
| `__TEXT.__eh_frame` | `0x3198` | `0x3178` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0x14a4` | `0x14c4` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x920` | `0x938` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0xd8` | `0xf0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1470` | `0x1480` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x10f0` | `0x10fe` | **`+0xe`** |
| `__TEXT.__swift5_proto` | `0x1a0` | `0x1ac` | **`+0xc`** |
| `__DATA.__data` | `0x2878` | `0x2880` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x590` | `0x598` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x2d8` | `0x2d0` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0xd4` | `0xd0` | **`-0x4`** |
| `__TEXT.__swift5_reflstr` | `0xe29` | `0xe2b` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-104.31.6.16.9
+104.31.6.16.13

-  Functions: 1391
-  Symbols:   818
-  CStrings:  839
+  Functions: 1404
+  Symbols:   819
+  CStrings:  847
Symbols:
+ _$ss6HasherV8_combineyys5UInt8VF
+ _OBJC_CLASS_$__LSOpenConfiguration
- _$s9FindingUI0A11DisplayModeO2eeoiySbAC_ACtFZ
CStrings:
+ "Failed to open %s"
+ "Missing source bundle, returning to SpringBoard"
+ "Missing workspace, returning to SpringBoard"
+ "Not returning to source bundle"
+ "Opened %s"
+ "Returning to %s"
+ "Scene destruction failed with error %{public}@"
+ "constraintGreaterThanOrEqualToAnchor:"
+ "constraintLessThanOrEqualToAnchor:"
+ "openApplicationWithBundleIdentifier:usingConfiguration:completionHandler:"
+ "setPriority:"
+ "v20@?0B8@\"NSError\"12"
- "Destruction completed with error %{public}@"
- "Not returning to Find My"
- "Returning to Find My"
- "openApplicationWithBundleID:"
```
