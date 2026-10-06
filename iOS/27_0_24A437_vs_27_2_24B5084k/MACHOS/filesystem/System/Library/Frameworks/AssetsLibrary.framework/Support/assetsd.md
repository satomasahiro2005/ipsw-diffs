## assetsd

> `/System/Library/Frameworks/AssetsLibrary.framework/Support/assetsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b3c8` | `0x1b538` | **`+0x170`** |
| `__TEXT.__oslogstring` | `0x46bb` | `0x473d` | **`+0x82`** |
| `__TEXT.__objc_stubs` | `0x5380` | `0x53c0` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x780` | `0x7b0` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x5fc3` | `0x5fe8` | **`+0x25`** |
| `__DATA.__objc_selrefs` | `0x16c0` | `0x16d0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xbc0` | `0xbd0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x5f0` | `0x5f8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-912.0.235.0.0
+916.40.110.0.0

-  Symbols:   442
-  CStrings:  1398
+  Symbols:   443
+  CStrings:  1402
Symbols:
+ _PLPlatformVisualIntelligenceSyncSupported
Functions:
~ sub_100008c68 : 1448 -> 1808
~ sub_10000b34c -> sub_10000b4b4 : 744 -> 752
CStrings:
+ "File Provider cache cleanup: removed empty directory %@"
+ "File Provider cache cleanup: removed empty domain root directory %@"
+ "Ignoring requested moment rebuild because moments not supported on platform"
+ "descriptionWithPath:"
+ "standardizedURL"
- "Ignoring requested moment rebuild because of outstanding transactions"
```
