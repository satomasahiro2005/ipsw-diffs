## backboardd

> `/usr/libexec/backboardd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x56dd8` | `0x56f34` | **`+0x15c`** |
| `__TEXT.__objc_methname` | `0xd851` | `0xd8c9` | **`+0x78`** |
| `__TEXT.__objc_methtype` | `0x2dec` | `0x2e2e` | **`+0x42`** |
| `__TEXT.__objc_methlist` | `0x48fc` | `0x4924` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x858` | `0x878` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x9c60` | `0x9c80` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x3048` | `0x3058` | **`+0x10`** |
| `__DATA.__objc_const` | `0xac98` | `0xaca0` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x728` | `0x730` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1570` | `0x1578` | **`+0x8`** |

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

### Other Changes

```diff

-866.0.0.0.0
+868.0.0.0.0

-  Functions: 1879
+  Functions: 1880

-  CStrings:  4035
+  CStrings:  4039
CStrings:
+ "_sensorModes:replicatingMainKeyToDisplayUUID:"
+ "getClientTaskNamePort:clientConnectionIdentifier:forTargetID:displayUUID:"
+ "v44@0:8o^I16o^Q24{?=I}32@\"NSString\"36"
+ "v44@0:8o^I16o^Q24{?=I}32@36"
```
