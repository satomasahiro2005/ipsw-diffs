## BridgePreferences

> `/System/Library/PrivateFrameworks/BridgePreferences.framework/BridgePreferences`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x392ac` | `0x39708` | **`+0x45c`** |
| `__TEXT.__oslogstring` | `0x1e48` | `0x1f98` | **`+0x150`** |
| `__AUTH_CONST.__cfstring` | `0x4420` | `0x44e0` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x4712` | `0x47a2` | **`+0x90`** |
| `__DATA_CONST.__const` | `0xed0` | `0xee0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a58` | `0x2a68` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xde0` | `0xde8` | **`+0x8`** |

### Other Changes

```diff

-1359.3.0.0.0
+1359.7.0.0.0

-  Functions: 1414
-  Symbols:   2550
-  CStrings:  846
+  Functions: 1416
+  Symbols:   2554
+  CStrings:  855
Symbols:
+ _BPSAppStoreAutoUpdateFollowUpPendingKey
+ _BPSAppStoreAutoUpdateFollowUpShownKey
+ _BPSIsAppStoreAccountAutoUpdateEnabled
+ _BPSSetAppStoreAccountAutoUpdate
CStrings:
+ "(AppStoreAutoUpdate) appstored AutoSettingsData ActiveDSID=%{public}@ AutoUpdatesEnabled=%{public}@ -> resolved=%{BOOL}d"
+ "(AppStoreAutoUpdate) appstored AutoSettingsData has no ActiveDSID; cannot set per-account AutoUpdatesEnabled"
+ "(AppStoreAutoUpdate) set appstored AutoSettingsData[%{public}@].AutoUpdatesEnabled=%{BOOL}d and pushed to Watch"
+ "ActiveDSID"
+ "AutoSettingsData"
+ "AutoUpdatesEnabled"
+ "COSAppStoreAutoUpdateFollowUpHasShown"
+ "COSAppStoreAutoUpdateFollowUpPending"
+ "com.apple.appstored"
```
