## PrivateEvolutionPlugin

> `/System/Library/ExtensionKit/Extensions/PrivateEvolutionPlugin.appex/PrivateEvolutionPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e5ac` | `0x1e6b8` | **`+0x10c`** |
| `__TEXT.__oslogstring` | `0xc40` | `0xc70` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x303` | `0x311` | **`+0xe`** |
| `__DATA_CONST.__const` | `0xb19` | `0xb11` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-42.0.0.0.0
+44.0.0.0.0

-  - /usr/lib/swift/libswiftAppleArchive.dylib

-  Symbols:   168
-  CStrings:  132
+  Symbols:   167
+  CStrings:  133
Symbols:
- __swift_FORCE_LOAD_$_swiftAppleArchive
Functions:
~ sub_1000035c8 -> sub_100003580 : 1564 -> 1832
CStrings:
+ "Text embedding result is missing an embedding."
+ "textEmbedding"
- "embedding"
```
