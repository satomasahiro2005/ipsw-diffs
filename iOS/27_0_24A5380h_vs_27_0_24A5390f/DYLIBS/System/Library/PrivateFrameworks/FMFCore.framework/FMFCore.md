## FMFCore

> `/System/Library/PrivateFrameworks/FMFCore.framework/FMFCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12ec10` | `0x131868` | **`+0x2c58`** |
| `__DATA_DIRTY.__bss` | `0x2f80` | `0x2d00` | **`-0x280`** |
| `__TEXT.__eh_frame` | `0x5d50` | `0x5f60` | **`+0x210`** |
| `__TEXT.__const` | `0x9e28` | `0x9c68` | **`-0x1c0`** |
| `__DATA.__bss` | `0xa400` | `0xa280` | **`-0x180`** |
| `__AUTH_CONST.__objc_const` | `0xcc20` | `0xcab8` | **`-0x168`** |
| `__AUTH_CONST.__const` | `0x8b89` | `0x8a59` | **`-0x130`** |
| `__DATA_DIRTY.__data` | `0x3d98` | `0x3c68` | **`-0x130`** |
| `__TEXT.__constg_swiftt` | `0x4490` | `0x43ac` | **`-0xe4`** |
| `__TEXT.__cstring` | `0x3776` | `0x3696` | **`-0xe0`** |
| `__AUTH_CONST.__auth_got` | `0x1668` | `0x1708` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x3980` | `0x3908` | **`-0x78`** |
| `__TEXT.__oslogstring` | `0x5c9e` | `0x5d0e` | **`+0x70`** |
| `__DATA.__data` | `0x1310` | `0x1368` | **`+0x58`** |
| `__DATA_DIRTY.__objc_data` | `0x8d8` | `0x888` | **`-0x50`** |
| `__TEXT.__swift5_reflstr` | `0x360d` | `0x35bd` | **`-0x50`** |
| `__AUTH.__data` | `0x20e8` | `0x20c8` | **`-0x20`** |
| `__TEXT.__swift5_proto` | `0x708` | `0x6e8` | **`-0x20`** |
| `__TEXT.__swift_as_cont` | `0x3b0` | `0x3d0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x36d0` | `0x36f0` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x24e5` | `0x24c7` | **`-0x1e`** |
| `__DATA_DIRTY.__common` | `0x168` | `0x150` | **`-0x18`** |
| `__TEXT.__swift5_assocty` | `0x6c0` | `0x6a8` | **`-0x18`** |
| `__TEXT.__swift_as_ret` | `0x1b0` | `0x1c0` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x11a4` | `0x1198` | **`-0xc`** |
| `__TEXT.__swift5_types` | `0x2f4` | `0x2e8` | **`-0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x1e0` | `0x1d8` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x118` | `0x120` | **`+0x8`** |

### Other Changes

```diff

-470.30.6.14.10
+470.30.6.14.19

-  Functions: 4952
+  Functions: 4929

-  CStrings:  902
+  CStrings:  897
CStrings:
+ "FMFFMLPreferencesStreamCtrl: Failed to fetch initial locationSharingCapableDevices: %s"
+ "FMFFMLPreferencesStreamCtrl: initial locationSharingCapableDevices fetched"
+ "FMFFMLPreferencesStreamCtrl: locationSharingCapableDevices changed"
+ "FMFMyLocationController: Resolving location: %{private}s"
+ "FMFMyLocationController: Updated adjusted location to %s"
+ "FMFRefreshGlobalConfig: FMFDimplekeyGlobalConfigStore=%s"
+ "FMFRefreshGlobalConfig: FMFGlobalConfigStore=%s"
+ "FMFRefreshGlobalConfig: FMFWaldoGlobalConfigStore=%s"
+ "FMFRefreshGlobalConfig: applying FindMyLocate clientConfiguration: %s"
- " distanceThreshold: "
- ") accuracyThreshold: "
- "FMFCore.FMFMyLocationController"
- "FMFDemoInteractionController: Forwarding %s to real server interaction controller."
- "FMFDemoInteractionController: Received %s, (error: %s) from real server interaction controller."
- "FMFMyLocationController: Updated non-server adjusted location to %s"
- "FMFMyLocationController: Updated server adjusted location to %s"
- "FMFMyLocationResponse: initialized with coder"
- "FMFServerInteractionController: didn't complete because of error: %s"
- "FMFServerInteractionController: received response?: %s"
- "Optional<FMFMyLocationResponse>"
- "accuracyThreshold"
- "distanceThreshold"
- "myLocationChanged"
```
