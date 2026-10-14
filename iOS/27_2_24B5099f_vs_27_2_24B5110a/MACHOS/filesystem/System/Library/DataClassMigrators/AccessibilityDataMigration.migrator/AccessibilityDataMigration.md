## AccessibilityDataMigration

> `/System/Library/DataClassMigrators/AccessibilityDataMigration.migrator/AccessibilityDataMigration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x291c` | `0x2a8c` | **`+0x170`** |
| `__TEXT.__oslogstring` | `0x17d` | `0x1e9` | **`+0x6c`** |
| `__TEXT.__cstring` | `0xa1c` | `0xa51` | **`+0x35`** |
| `__TEXT.__auth_stubs` | `0x2f0` | `0x320` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x860` | `0x880` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0xf6b` | `0xf8b` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x10c0` | `0x10e0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x188` | `0x1a0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x188` | `0x194` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x488` | `0x490` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xf8` | `0x100` | **`+0x8`** |
| `__TEXT.__const` | `0x40` | `0x48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3245.8.4.2.0
+3245.8.9.0.0

-  Functions: 34
-  Symbols:   88
-  CStrings:  231
+  Functions: 35
+  Symbols:   92
+  CStrings:  235
Symbols:
+ _AXDeviceIsPhone
+ __AXSHomeButtonRestingUnlock
+ __AXSHomeButtonRestingUnlockPreferredForDevice
+ _kAXSRestingHomeButtonUnlockPreference
Functions:
~ sub_12a0 : 396 -> 404
+ sub_1434
CStrings:
+ "Clearing existing Rest Finger to Open preference."
+ "Device prefers Rest Finger to Open. Currently enabled: %i"
+ "_AccessibilityMigration_MigrateRestFingerToOpen_27_1"
+ "_ravePopMigrateRestFingerToOpen"
```
