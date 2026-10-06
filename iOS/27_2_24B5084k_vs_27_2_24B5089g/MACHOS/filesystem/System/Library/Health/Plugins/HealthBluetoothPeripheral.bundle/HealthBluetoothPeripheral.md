## HealthBluetoothPeripheral

> `/System/Library/Health/Plugins/HealthBluetoothPeripheral.bundle/HealthBluetoothPeripheral`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3eee4` | `0x3f0e0` | **`+0x1fc`** |
| `__TEXT.__oslogstring` | `0x595f` | `0x59fb` | **`+0x9c`** |
| `__TEXT.__gcc_except_tab` | `0xaf8` | `0xb0c` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x480` | `0x488` | **`+0x8`** |
| `__TEXT.__const` | `0x1a0` | `0x1a8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7027.1.36.2.7
+7027.1.45.2.4

-  Functions: 1714
-  Symbols:   437
-  CStrings:  2673
+  Functions: 1715
+  Symbols:   438
+  CStrings:  2675
Symbols:
+ _kHKConnectedGymPreferencesNFCDetectionMode
CStrings:
+ "GymKit detection disabled by user; turning off NFC"
+ "GymKit detection mode %ld disagrees with legacy value %ld; preferring the legacy value"
+ "GymKit muted for today; turning off NFC until end of day"
+ "GymKit user default setting (NPSDomainAccessor, paired watch): mode=%{public}@ legacy=%{public}@"
+ "GymKit user default setting (UserDefaults, no paired watch): mode=%{public}@ legacy=%{public}@"
- "GymKit always on user default setting (NPSDomainAccessor, paired watch): %{public}@"
- "GymKit always on user default setting (UserDefaults, no paired watch): %{public}@"
- "GymKit muted for today; disabling always-on NFC until end of day"
```
