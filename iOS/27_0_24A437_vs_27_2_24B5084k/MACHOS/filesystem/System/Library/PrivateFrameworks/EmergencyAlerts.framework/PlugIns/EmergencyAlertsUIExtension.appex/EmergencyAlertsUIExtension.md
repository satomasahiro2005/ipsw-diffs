## EmergencyAlertsUIExtension

> `/System/Library/PrivateFrameworks/EmergencyAlerts.framework/PlugIns/EmergencyAlertsUIExtension.appex/EmergencyAlertsUIExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5260` | `0x5414` | **`+0x1b4`** |
| `__TEXT.__oslogstring` | `0x7fa` | `0x843` | **`+0x49`** |
| `__DATA.__objc_const` | `0x6a0` | `0x6c0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x48c` | `0x4a4` | **`+0x18`** |
| `__TEXT.__objc_methname` | `0x1636` | `0x164a` | **`+0x14`** |
| `__DATA.__objc_ivar` | `0x44` | `0x48` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-274.1.0.0.0
+275.0.0.0.0

-  Functions: 99
+  Functions: 103

-  CStrings:  463
+  CStrings:  466
CStrings:
+ "Map snapshot failed to load: %{public}@"
+ "Map snapshot loaded successfully"
+ "isMapSnapshotLoaded"
```
