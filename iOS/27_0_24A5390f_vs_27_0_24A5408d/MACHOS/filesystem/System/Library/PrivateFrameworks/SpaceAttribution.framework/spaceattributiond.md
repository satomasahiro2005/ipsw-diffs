## spaceattributiond

> `/System/Library/PrivateFrameworks/SpaceAttribution.framework/spaceattributiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3fac4` | `0x3fa58` | **`-0x6c`** |
| `__TEXT.__cstring` | `0x35e4` | `0x359d` | **`-0x47`** |
| `__DATA_CONST.__cfstring` | `0x2da0` | `0x2d80` | **`-0x20`** |
| `__TEXT.__oslogstring` | `0x57cf` | `0x57e6` | **`+0x17`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-493.0.0.502.1
+496.0.1.0.0

-  CStrings:  2775
+  CStrings:  2774
Functions:
~ sub_10000ff2c : 492 -> 524
~ sub_10001d828 -> sub_10001d848 : 596 -> 456
CStrings:
+ "%s: Removing %@ - no registered paths remaining"
- "%s: Removing %@ app path"
- "bundleIDs %@ cache size: %llu is greater than existing data size: %llu"
```
