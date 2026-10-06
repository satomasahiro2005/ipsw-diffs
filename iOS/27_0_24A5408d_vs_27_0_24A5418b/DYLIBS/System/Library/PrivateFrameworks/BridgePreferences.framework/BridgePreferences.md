## BridgePreferences

> `/System/Library/PrivateFrameworks/BridgePreferences.framework/BridgePreferences`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x4eb0` | `0x4f80` | **`+0xd0`** |
| `__TEXT.__oslogstring` | `0x1f98` | `0x2018` | **`+0x80`** |
| `__AUTH.__objc_data` | `0x1528` | `0x1578` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x3260` | `0x32a8` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x44e0` | `0x44a0` | **`-0x40`** |
| `__AUTH_CONST.__const` | `0xb20` | `0xb40` | **`+0x20`** |
| `__DATA_CONST.__const` | `0xee0` | `0xf00` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a68` | `0x2a88` | **`+0x20`** |
| `__TEXT.__cstring` | `0x47a2` | `0x4782` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x7b8` | `0x7d0` | **`+0x18`** |
| `__TEXT.__text` | `0x39708` | `0x396f0` | **`-0x18`** |
| `__TEXT.__const` | `0x1944` | `0x1954` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1b8` | `0x1c0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xc0` | `0xc8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2d8` | `0x2dc` | **`+0x4`** |

### Other Changes

```diff

-1359.7.0.0.0
+1359.9.0.0.0

-  Functions: 1416
-  Symbols:   2554
+  Functions: 1422
+  Symbols:   2572
Symbols:
+ -[BPSBridgeAppContext watchSupportsAlwaysListeningHeySiri]
+ -[BPSSetupContentView .cxx_destruct]
+ -[BPSSetupContentView layoutObserver]
+ -[BPSSetupContentView layoutSubviews]
+ -[BPSSetupContentView setLayoutObserver:]
+ _BPSIsPhoneAppStoreAutoUpdateEnabled
+ _BPSSetPhoneAppStoreAutoUpdate
+ _OBJC_CLASS_$_ASDUpdatesService
+ _OBJC_CLASS_$_BPSSetupContentView
+ _OBJC_IVAR_$_BPSSetupContentView._layoutObserver
+ _OBJC_METACLASS_$_BPSSetupContentView
+ __OBJC_$_INSTANCE_METHODS_BPSSetupContentView
+ __OBJC_$_INSTANCE_VARIABLES_BPSSetupContentView
+ __OBJC_$_PROP_LIST_BPSSetupContentView
+ __OBJC_CLASS_RO_$_BPSSetupContentView
+ __OBJC_METACLASS_RO_$_BPSSetupContentView
+ ___BPSSetPhoneAppStoreAutoUpdate_block_invoke
+ ___block_descriptor_32_e29_v24?0"NSArray"8"NSError"16l
+ _kCFBooleanFalse
+ _kCFBooleanTrue
- _BPSIsAppStoreAccountAutoUpdateEnabled
- _BPSSetAppStoreAccountAutoUpdate
CStrings:
+ "(AppStoreAutoUpdate) FAILED to persist itunesstored AutoUpdatesEnabled=%{BOOL}d (synchronized=%{BOOL}d readBackExists=%{BOOL}d readBack=%{BOOL}d)"
+ "(AppStoreAutoUpdate) itunesstored AutoUpdatesEnabled exists=%{BOOL}d value=%{BOOL}d -> resolved=%{BOOL}d"
+ "(AppStoreAutoUpdate) set itunesstored AutoUpdatesEnabled=%{BOOL}d (verified)"
+ "(AppStoreAutoUpdate) updates reload after toggle failed: %{public}@"
+ "(AppStoreAutoUpdate) updates reload after toggle found %lu update(s)"
+ "com.apple.itunesstored"
- "(AppStoreAutoUpdate) appstored AutoSettingsData ActiveDSID=%{public}@ AutoUpdatesEnabled=%{public}@ -> resolved=%{BOOL}d"
- "(AppStoreAutoUpdate) appstored AutoSettingsData has no ActiveDSID; cannot set per-account AutoUpdatesEnabled"
- "(AppStoreAutoUpdate) set appstored AutoSettingsData[%{public}@].AutoUpdatesEnabled=%{BOOL}d and pushed to Watch"
- "ActiveDSID"
- "AutoSettingsData"
- "com.apple.appstored"
```
