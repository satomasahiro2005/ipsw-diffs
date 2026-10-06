## BackTapUIServer

> `/System/Library/AccessibilityBundles/BackTapUIServer.axuiservice/BackTapUIServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa644` | `0xa89c` | **`+0x258`** |
| `__TEXT.__objc_stubs` | `0xa00` | `0xa80` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x1124` | `0x1194` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0x16a8` | `0x16f8` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x239` | `0x276` | **`+0x3d`** |
| `__DATA.__objc_selrefs` | `0x410` | `0x430` | **`+0x20`** |
| `__TEXT.__const` | `0x7d0` | `0x7e8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x698` | `0x6b0` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0xcb0` | `0xcc0` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x50c` | `0x51c` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x668` | `0x670` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x380` | `0x388` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0xf8` | `0xfc` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x160` | `0x164` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3245.8.2.0.0
+3245.8.4.2.0

-  Functions: 284
+  Functions: 287

-  CStrings:  249
+  CStrings:  254
CStrings:
+ "Register with client policy %lu, supported action policy %lu"
+ "_supportedActionPolicyOption"
+ "backTapEnabled"
+ "hasBackTapDoubleTapAction"
+ "hasBackTapTripleTapAction"
```
