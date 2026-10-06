## spaceattributiond

> `/System/Library/PrivateFrameworks/SpaceAttribution.framework/spaceattributiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3fa34` | `0x3fd88` | **`+0x354`** |
| `__TEXT.__oslogstring` | `0x57e6` | `0x592a` | **`+0x144`** |
| `__TEXT.__objc_stubs` | `0x7680` | `0x7700` | **`+0x80`** |
| `__TEXT.__cstring` | `0x35f4` | `0x3636` | **`+0x42`** |
| `__TEXT.__objc_methname` | `0x8a2a` | `0x8a6b` | **`+0x41`** |
| `__DATA_CONST.__cfstring` | `0x2dc0` | `0x2e00` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x2320` | `0x2340` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x2f50` | `0x2f60` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
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
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-499.40.3.0.0
+499.40.4.0.0

-  Functions: 1471
+  Functions: 1474

-  CStrings:  2776
+  CStrings:  2789
CStrings:
+ "END: VCC Details"
+ "START: VCC Details"
+ "Skipping VCC details, capacity (%ld) exceeds the sized total (%llu)"
+ "Skipping VCC details, capacity: %ld"
+ "VCC bundle not present in results, skipping VCC details"
+ "VCC details - capacity: %ld, system reserved: %llu, total: %llu"
+ "VCC is supported but sharedStorage is nil, skipping VCC details"
+ "addToVCCDetails:key:"
+ "addVCCDetails"
+ "com.apple.camera.vcc.capacity"
+ "com.apple.camera.vcc.systemReserved"
+ "initialCapacity"
+ "sharedStorage"
```
