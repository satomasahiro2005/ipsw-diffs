## tvremoted

> `/usr/libexec/tvremoted`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11174` | `0x110c8` | **`-0xac`** |
| `__DATA_CONST.__cfstring` | `0x900` | `0x960` | **`+0x60`** |
| `__TEXT.__objc_methtype` | `0xfa2` | `0xf7a` | **`-0x28`** |
| `__DATA_CONST.__const` | `0x6b0` | `0x6c8` | **`+0x18`** |
| `__TEXT.__cstring` | `0xb53` | `0xb5d` | **`+0xa`** |
| `__TEXT.__objc_methname` | `0x32b1` | `0x32b7` | **`+0x6`** |
| `__TEXT.__oslogstring` | `0x26cc` | `0x26cb` | **`-0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-625.0.0.0.0
+627.0.9.0.0

-  CStrings:  939
+  CStrings:  938
CStrings:
+ "'%@' find my remote support: %@"
+ "Full"
+ "Legacy"
+ "None"
+ "device:updatedFindMyRemoteSupport:"
- "'%@' supports find my remote: %s"
- "device:supportsFindMyRemote:"
- "no"
- "v28@0:8@\"TVRXDevice\"16B24"
- "v28@0:8@16B24"
- "yes"
```
