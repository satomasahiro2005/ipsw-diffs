## ProximityReaderNFCExtension

> `/System/Library/ExtensionKit/Extensions/ProximityReaderNFCExtension.appex/ProximityReaderNFCExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x46dc` | `0x4cf0` | **`+0x614`** |
| `__TEXT.__cstring` | `0x1a6` | `0x1f6` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x348` | `0x380` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x660` | `0x670` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x338` | `0x340` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x178` | `0x180` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x14` | `0x18` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-150.35.0.0.0
+151.2.0.0.0

-  Functions: 59
+  Functions: 60

-  CStrings:  119
+  CStrings:  120
Symbols:
+ _swift_retain_x8
- _swift_retain_x28
CStrings:
+ "Merchant requested web relay via NDEF (rl=1) — engaging daemon relay"
```
