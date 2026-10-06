## tipsd

> `/usr/libexec/tipsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18b94` | `0x18ccc` | **`+0x138`** |
| `__TEXT.__objc_methtype` | `0x1189` | `0x11f9` | **`+0x70`** |
| `__TEXT.__objc_methname` | `0x37c0` | `0x3821` | **`+0x61`** |
| `__TEXT.__oslogstring` | `0x172b` | `0x1755` | **`+0x2a`** |
| `__TEXT.__objc_methlist` | `0xd60` | `0xd88` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x2e40` | `0x2e60` | **`+0x20`** |
| `__DATA.__objc_const` | `0xc60` | `0xc70` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xeb8` | `0xec8` | **`+0x10`** |
| `__TEXT.__const` | `0x36c` | `0x374` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x708` | `0x710` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-866.0.0.0.0
+866.2.2.0.0

-  Functions: 489
+  Functions: 492

-  CStrings:  921
+  CStrings:  926
CStrings:
+ "XPC: fetchELabelURLsForAccessoryModel: %@"
+ "fetchELabelURLsForAccessoryModel:completion:"
+ "fetchELabelURLsForAccessoryModel:completionHandler:"
+ "v24@0:8@?<v@?@\"NSURL\"@\"NSURL\"@\"NSError\">16"
+ "v32@0:8@\"NSString\"16@?<v@?@\"NSURL\"@\"NSURL\"@\"NSError\">24"
```
