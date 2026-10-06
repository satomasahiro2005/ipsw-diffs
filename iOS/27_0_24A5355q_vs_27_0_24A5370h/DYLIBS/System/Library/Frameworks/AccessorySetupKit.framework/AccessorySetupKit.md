## AccessorySetupKit

> `/System/Library/Frameworks/AccessorySetupKit.framework/AccessorySetupKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22584` | `0x22544` | **`-0x40`** |
| `__AUTH.__objc_data` | `0xac0` | `0xad0` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x2cc` | `0x2dc` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x20e0` | `0x20f0` | **`+0x10`** |
| `__TEXT.__ustring` | `0x14e` | `0x15a` | **`+0xc`** |
| `__AUTH_CONST.__objc_const` | `0x2dd8` | `0x2de0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x19d8` | `0x19e0` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-2700.22.0.0.0
+2700.26.0.0.0

-  Functions: 820
+  Functions: 821
Symbols:
+ _swift_retain_x28
- _swift_retain_x24
CStrings:
+ "This iPhone will always ask to share new local networks with this accessory."
+ "This iPhone will automatically share new local networks with this accessory."
+ "This iPhone won’t share new local networks with this accessory. The accessory will still connect to previously known networks."
- "This iPhone will always ask for your permission to share new networks with this accessory."
- "This iPhone will automatically share new networks with this accessory."
- "This iPhone won’t share new networks with this accessory. The accessory will still connect to previously known networks."
```
