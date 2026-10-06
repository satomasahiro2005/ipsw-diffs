## ScreenTimeSettingsShield

> `/Applications/ScreenTimeSettingsShield.app/ScreenTimeSettingsShield`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17574` | `0x1a1c8` | **`+0x2c54`** |
| `__TEXT.__oslogstring` | `0x624` | `0x914` | **`+0x2f0`** |
| `__TEXT.__eh_frame` | `0x41c` | `0x5ac` | **`+0x190`** |
| `__TEXT.__swift5_typeref` | `0xf6a` | `0x103e` | **`+0xd4`** |
| `__TEXT.__const` | `0xb34` | `0xbf4` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x628` | `0x6c0` | **`+0x98`** |
| `__TEXT.__constg_swiftt` | `0x594` | `0x618` | **`+0x84`** |
| `__TEXT.__unwind_info` | `0x4a8` | `0x510` | **`+0x68`** |
| `__TEXT.__objc_methname` | `0x15c7` | `0x1617` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x360` | `0x3a0` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x26c` | `0x2a8` | **`+0x3c`** |
| `__DATA.__data` | `0xb70` | `0xba0` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x14b0` | `0x14e0` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x110` | `0x140` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x2a8` | `0x2d0` | **`+0x28`** |
| `__DATA.__objc_const` | `0x970` | `0x990` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1f7` | `0x217` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xa60` | `0xa78` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x3f8` | `0x410` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x14` | `0x28` | **`+0x14`** |
| `__DATA.__objc_selrefs` | `0x4b8` | `0x4c8` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x38` | `0x40` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x10` | `0x18` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-87.1.101.0.0
+91.1.0.0.0

+  - /System/Library/Frameworks/MarketplaceKit.framework/MarketplaceKit

-  Functions: 370
-  Symbols:   546
-  CStrings:  334
+  Functions: 398
+  Symbols:   554
+  CStrings:  347
Symbols:
+ _$s10Foundation3URLVSQAAMc
+ _$s10Foundation3URLVs23CustomStringConvertibleAAMc
+ _$s14MarketplaceKit14AppDistributorO18requestProductPage_6itemID07versionI0ySS_s6UInt64VAHSgtYaKFZ
+ _$s14MarketplaceKit14AppDistributorO18requestProductPage_6itemID07versionI0ySS_s6UInt64VAHSgtYaKFZTu
+ _$ss6UInt64VMn
+ _$syycWV
+ _objc_retain_x25
+ _swift_arrayDestroy
+ _swift_retain_x28
- _objc_retain_x28
CStrings:
+ "App is from distributor or web. No app store url: %{private}s"
+ "Cannot open in third party marketplace: distributor app is not installed"
+ "Cannot open in third party marketplace: fromDistributorOrWeb=%{bool,public}d, hasDistributorId=%{bool,public}d, hasBundleId=%{bool,public}d"
+ "Cannot open store page for %{private}s"
+ "Could not show product page for %{private}s: %{public}s"
+ "Could not show product page for record: %{private}s"
+ "Failed opening app store page for %{private}s,\nstoreUrl: %{public}s"
+ "Failed to load application record while opening Ask Permission flow: %{public}s"
+ "Invalid adamID for app: %{private}s"
+ "No application record to open"
+ "Opened third party product page for %{private}s"
+ "Opening app store page for %{private}s"
+ "Opening third party app details page for %{private}s"
+ "Requesting third party product page for %{private}s"
+ "applicationIsInstalled:"
+ "https://itunes.apple.com/app/id"
+ "isInstalledFromDistributorOrWeb"
+ "openInMarketplace"
- "Error fetching adamID for %s"
- "No App Store URL to open"
- "No adamID for %{public}s"
- "Unable to construct App Store URL for Adam identifier %{private}llu."
- "https://apps.apple.com/app/id"
```
