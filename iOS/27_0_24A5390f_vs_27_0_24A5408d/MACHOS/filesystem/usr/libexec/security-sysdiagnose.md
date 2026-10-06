## security-sysdiagnose

> `/usr/libexec/security-sysdiagnose`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methtype` | `0x17e` | `0x1a7` | **`+0x29`** |
| `__TEXT.__objc_methname` | `0x411` | `0x42d` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0xd0` | `0xdc` | **`+0xc`** |
| `__DATA.__objc_const` | `0x190` | `0x198` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x190` | `0x198` | **`+0x8`** |
| `__TEXT.__const` | `0x70` | `0x68` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-62460.0.55.0.1
+62460.2.1.0.0

-  CStrings:  210
+  CStrings:  212
CStrings:
+ "resetMetricsForTopic:reply:"
+ "v32@0:8@\"NSString\"16@?<v@?B@\"NSError\">24"
```
