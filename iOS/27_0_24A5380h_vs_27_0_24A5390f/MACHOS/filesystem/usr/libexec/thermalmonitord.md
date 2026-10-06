## thermalmonitord

> `/usr/libexec/thermalmonitord`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x568a4` | `0x5740c` | **`+0xb68`** |
| `__TEXT.__oslogstring` | `0x9a88` | `0x9d83` | **`+0x2fb`** |
| `__DATA.__objc_const` | `0xd108` | `0xd1d8` | **`+0xd0`** |
| `__DATA_CONST.__cfstring` | `0x6740` | `0x67e0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x4da2` | `0x4e09` | **`+0x67`** |
| `__DATA.__objc_data` | `0x3660` | `0x36b0` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x83a7` | `0x83da` | **`+0x33`** |
| `__TEXT.__objc_classname` | `0x1461` | `0x1484` | **`+0x23`** |
| `__TEXT.__unwind_info` | `0x12b0` | `0x12d0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x390` | `0x3ac` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0x4254` | `0x426c` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x13c0` | `0x13d0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xa70` | `0xa78` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x9f8` | `0xa00` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x1450` | `0x1458` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x680` | `0x688` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x570` | `0x578` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-2076.0.0.0.0
+2081.0.0.0.1

-  Functions: 2044
-  Symbols:   415
-  CStrings:  3743
+  Functions: 2056
+  Symbols:   416
+  CStrings:  3764
Symbols:
+ _CFDictionaryCreateMutableCopy
CStrings:
+ "<Error> Failed to upgrade NVRAM V2 to V3, resetting persistence"
+ "<Error> getBatteryPackCount: invalid pack count %d; defaulting to 1\n"
+ "<Error> getBatteryPackCount: no AppleSmartBattery service\n"
+ "<Error> getChemIDForPack: BatteryData NULL for PackID %d\n"
+ "<Error> getChemIDForPack: CFNumberCreate failed for PackID %d\n"
+ "<Error> getChemIDForPack: chemIDOut must not be NULL\n"
+ "<Error> getChemIDForPack: pack 0 present but unreadable; using default P0 threshold\n"
+ "<Error> getChemIDForPack: pack 1 present but unreadable; using default P0 threshold\n"
+ "<Notice> BackLightCCSingle: frame-based display power enabled at %d Hz"
+ "<Notice> getBatteryPackCount: %d"
+ "<Notice> getChemIDForPack: no AppleSmartBatteryBank for PackID %d"
+ "<Notice> getChemIDForPack: pack %d success %d chemID %d"
+ "AppleSmartBattery"
+ "BatteryPackCount"
+ "PackID"
+ "_fixedDisplayFrameRate"
+ "_usesFrameBasedDisplayPower"
+ "fixedDisplayFrameRate"
+ "frame_count"
+ "tm5142f10796d37035f25c6c85ab01b420"
+ "usesFrameBasedDisplayPower"
```
