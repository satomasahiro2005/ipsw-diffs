## tursd

> `/usr/libexec/tursd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methtype` | `0x948` | `0x984` | **`+0x3c`** |
| `__TEXT.__objc_methname` | `0x3b13` | `0x3b4a` | **`+0x37`** |
| `__TEXT.__objc_methlist` | `0x1144` | `0x1150` | **`+0xc`** |
| `__DATA.__objc_const` | `0x17c8` | `0x17d0` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0xd00` | `0xd08` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-  CStrings:  757
+  CStrings:  759
CStrings:
+ "conversationManager:debugSendInterpreterLink:toHandle:"
+ "v40@0:8@\"TUConversationManager\"16@\"NSString\"24@\"NSString\"32"
```
