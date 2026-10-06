## powerd

> `/System/Library/CoreServices/powerd.bundle/powerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77f20` | `0x78230` | **`+0x310`** |
| `__TEXT.__oslogstring` | `0xe213` | `0xe258` | **`+0x45`** |
| `__DATA_CONST.__cfstring` | `0x76c0` | `0x7700` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x2c6c` | `0x2c8c` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x720c` | `0x722c` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x5900` | `0x5920` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1698` | `0x16b0` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x4fc` | `0x50c` | **`+0x10`** |
| `__TEXT.__cstring` | `0x6ead` | `0x6ebc` | **`+0xf`** |
| `__DATA.__bss` | `0xdd8` | `0xdd0` | **`-0x8`** |
| `__DATA.__data` | `0xbbc` | `0xbb4` | **`-0x8`** |
| `__DATA.__objc_const` | `0x56b0` | `0x56b8` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x1c30` | `0x1c38` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0xaa0` | `0xaa4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
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

-2043.2.2.0.0
+2043.40.43.0.0

-  Functions: 2649
+  Functions: 2652

-  CStrings:  4074
+  CStrings:  4077
CStrings:
+ "@24@0:8^{?=IIb1b1b1b1b1iiiiiiQiiiiiiQIiiQiii@@@qi@@QI^{?}}16"
+ "Failed to retrieve feature flags (packId=%u status=0x%x)"
+ "FeatureFlags"
+ "IONVRAM-SYNCNOW-PROPERTY"
+ "Retrieved feature flags (packId=%u flags=0x%llx status=0x%x)"
+ "Sender not entitled to read battery heatmap data\n"
+ "Sender not entitled to read cycle count data\n"
+ "i32@0:8@\"NSDictionary\"16^{?=IIb1b1b1b1b1iiiiiiQiiiiiiQIiiQiii@@@qi@@QI^{?}}24"
+ "i32@0:8@16^{?=IIb1b1b1b1b1iiiiiiQiiiiiiQIiiQiii@@@qi@@QI^{?}}24"
+ "i32@0:8^{?=IIb1b1b1b1b1iiiiiiQiiiiiiQIiiQiii@@@qi@@QI^{?}}16^@24"
+ "serviceStateFusionGetFromPacks:"
- "@24@0:8^{?=IIb1b1b1b1b1iiiiiiQiiiiiiQIiiQiii@@@qi@@I^{?}}16"
- "AppleARMPMUPowerSource"
- "Setting NCCP cycle count based filtering to %d\n"
- "Setting NCCP cycle count based filtering to false\n"
- "failed to read battery feature flags rc:0x%x\n"
- "i32@0:8@\"NSDictionary\"16^{?=IIb1b1b1b1b1iiiiiiQiiiiiiQIiiQiii@@@qi@@I^{?}}24"
- "i32@0:8@16^{?=IIb1b1b1b1b1iiiiiiQiiiiiiQIiiQiii@@@qi@@I^{?}}24"
- "i32@0:8^{?=IIb1b1b1b1b1iiiiiiQiiiiiiQIiiQiii@@@qi@@I^{?}}16^@24"
```
