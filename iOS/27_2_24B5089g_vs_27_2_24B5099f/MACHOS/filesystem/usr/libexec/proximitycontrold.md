## proximitycontrold

> `/usr/libexec/proximitycontrold`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26bfa4` | `0x26c108` | **`+0x164`** |
| `__TEXT.__eh_frame` | `0x70a4` | `0x7114` | **`+0x70`** |
| `__TEXT.__objc_methname` | `0xdf89` | `0xdfb9` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x370b` | `0x373b` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x6df8` | `0x6e10` | **`+0x18`** |
| `__DATA.__objc_const` | `0x18a20` | `0x18a28` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x1da0` | `0x1da8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x29a8` | `0x29b0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-376.10.29.0.0
+376.10.31.0.0

-  Functions: 10425
+  Functions: 10429

-  CStrings:  4191
+  CStrings:  4193
CStrings:
+ "conversationManager:debugSendInterpreterLink:toHandle:"
+ "v40@0:8@\"TUConversationManager\"16@\"NSString\"24@\"NSString\"32"
```
