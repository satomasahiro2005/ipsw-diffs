## ospredictiond

> `/usr/libexec/ospredictiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x68834` | `0x690c4` | **`+0x890`** |
| `__TEXT.__oslogstring` | `0x7327` | `0x7474` | **`+0x14d`** |
| `__TEXT.__objc_stubs` | `0x98c0` | `0x9960` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x153ff` | `0x15478` | **`+0x79`** |
| `__DATA_CONST.__const` | `0x1180` | `0x11c0` | **`+0x40`** |
| `__DATA.__bss` | `0x200` | `0x228` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x3d78` | `0x3da0` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x9388` | `0x93a0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x14e8` | `0x1500` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x4b8` | `0x4c8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x910` | `0x920` | **`+0x10`** |
| `__TEXT.__const` | `0x458` | `0x468` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x498` | `0x4a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-  Functions: 3330
-  Symbols:   285
-  CStrings:  4793
+  Functions: 3339
+  Symbols:   287
+  CStrings:  4806
Symbols:
+ _MGIsDeviceOneOfType
+ _OBJC_CLASS_$_CBClient
CStrings:
+ "CBClient activate failed, reading lux from the system: %{public}@"
+ "Multiple displays: %{BOOL}d"
+ "No per-display lux: %{public}@"
+ "No valid per-display lux %{public}@"
+ "Only %lu display client(s), reading lux from the system"
+ "Per-display lux %{public}@, using max %d"
+ "Reading lux from %lu displays"
+ "activateWithError:"
+ "copyPropertyForKey:error:"
+ "luxReadingsFromDisplays:"
+ "newDisplayClientForID:%lu failed: %{public}@"
+ "newDisplayClientForID:withError:"
+ "perDisplayClients"
```
