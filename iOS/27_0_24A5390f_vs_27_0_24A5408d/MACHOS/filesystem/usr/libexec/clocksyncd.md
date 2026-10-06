## clocksyncd

> `/usr/libexec/clocksyncd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3b028` | `0x3b364` | **`+0x33c`** |
| `__TEXT.__oslogstring` | `0x5853` | `0x592c` | **`+0xd9`** |
| `__TEXT.__cstring` | `0x27e0` | `0x2835` | **`+0x55`** |
| `__DATA_CONST.__cfstring` | `0x1ee0` | `0x1f00` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x59e0` | `0x5a00` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x9192` | `0x919d` | **`+0xb`** |
| `__DATA.__objc_selrefs` | `0x1d98` | `0x1da0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xe78` | `0xe80` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1501.5.0.0.0
+1501.6.0.0.0

-  Functions: 1528
+  Functions: 1532

-  CStrings:  2453
+  CStrings:  2459
CStrings:
+ "1501.6"
+ "IOTimeSync"
+ "_isAllowedRegistryRead(service, key)"
+ "_isAllowedRegistryRead(service, nil)"
+ "hasPrefix:"
+ "propertiesForRegistryEntryID rejected: entryID=0x%llx class=%{public}@ (not in TimeSync object graph)"
+ "propertyForRegistryEntryID rejected: entryID=0x%llx key=%{public}@ class=%{public}@ (not in TimeSync object graph)"
- "1501.5"
```
