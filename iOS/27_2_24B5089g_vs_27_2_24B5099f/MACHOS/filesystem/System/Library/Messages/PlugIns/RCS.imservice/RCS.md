## RCS

> `/System/Library/Messages/PlugIns/RCS.imservice/RCS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x111a48` | `0x111c78` | **`+0x230`** |
| `__TEXT.__eh_frame` | `0xa9d8` | `0xaa10` | **`+0x38`** |
| `__TEXT.__objc_methname` | `0x61b3` | `0x61d3` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x59a0` | `0x59c0` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x1588` | `0x1570` | **`-0x18`** |
| `__DATA.__data` | `0x3cd8` | `0x3cc8` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x1960` | `0x1968` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x9b0` | `0x9b4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1491.200.73.0.0
+1491.200.95.0.0

-  Functions: 3898
+  Functions: 3899

-  CStrings:  1694
+  CStrings:  1695
CStrings:
+ "generatePreviewForTransfer:attachmentPath:balloonBundleID:senderContext:senderID:replaceExistingPreview:completionBlock:"
+ "messageStatus"
- "generatePreviewForTransfer:attachmentPath:balloonBundleID:senderContext:senderID:completionBlock:"
```
