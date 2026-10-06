## OrderExtractionDiagnosticExtension

> `/System/Library/ExtensionKit/Extensions/OrderExtractionDiagnosticExtension.appex/OrderExtractionDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x111e4` | `0x11828` | **`+0x644`** |
| `__DATA.__bss` | `0x1270` | `0x15a0` | **`+0x330`** |
| `__TEXT.__const` | `0xabe` | `0xc26` | **`+0x168`** |
| `__DATA.__data` | `0x588` | `0x640` | **`+0xb8`** |
| `__DATA_CONST.__const` | `0x460` | `0x4f0` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x4d0` | `0x520` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x398` | `0x3e8` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x1bc` | `0x208` | **`+0x4c`** |
| `__TEXT.__swift5_typeref` | `0x34d` | `0x38f` | **`+0x42`** |
| `__TEXT.__eh_frame` | `0x550` | `0x588` | **`+0x38`** |
| `__TEXT.__cstring` | `0x9b2` | `0x982` | **`-0x30`** |
| `__TEXT.__auth_stubs` | `0xeb0` | `0xe90` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x542` | `0x562` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x88` | `0xa0` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x760` | `0x750` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x198` | `0x1a0` | **`+0x8`** |
| `__TEXT.__objc_methname` | `0x6b1` | `0x6a9` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x2c` | `0x34` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__got`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`

### Other Changes

```diff

-366.1.0.0.0
+376.0.1.0.0

-  Functions: 263
-  Symbols:   129
-  CStrings:  104
+  Functions: 286
+  Symbols:   126
+  CStrings:  103
Symbols:
- _NSLocalizedDescriptionKey
- _OBJC_CLASS_$_NSError
- _objc_retain_x28
CStrings:
+ "RawOrderEmailExtractions"
+ "foundInMailItemObject"
- "Failed to encode JSON string as UTF-8"
- "RawBiomeOrderEmails"
- "initWithDomain:code:userInfo:"
```
