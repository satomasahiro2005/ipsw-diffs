## HomeKitDiagnosticExtension

> `/System/Library/Frameworks/HomeKit.framework/PlugIns/HomeKitDiagnosticExtension.appex/HomeKitDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2465c` | `0x246b4` | **`+0x58`** |
| `__TEXT.__objc_stubs` | `0x3a40` | `0x3a80` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x428` | `0x448` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x3ead` | `0x3ec8` | **`+0x1b`** |
| `__DATA.__objc_const` | `0x4588` | `0x4598` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x12e0` | `0x12f0` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x1f8c` | `0x1f9c` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x740` | `0x748` | **`+0x8`** |

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
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-1479.0.0.1.0
+1484.2.0.0.0

-  Functions: 627
+  Functions: 628

-  CStrings:  1599
+  CStrings:  1601
Functions:
~ sub_1000136fc : 144 -> 88
+ sub_100013754
CStrings:
+ "contactGivenName"
+ "givenName"
```
