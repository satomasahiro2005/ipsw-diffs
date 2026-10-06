## ValidUpdater

> `/usr/libexec/ValidUpdater`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5a80` | `0x60dc` | **`+0x65c`** |
| `__TEXT.__oslogstring` | `0x130` | `0x210` | **`+0xe0`** |
| `__TEXT.__auth_stubs` | `0x820` | `0x870` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x418` | `0x440` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x400` | `0x428` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x1ac` | `0x1c8` | **`+0x1c`** |
| `__DATA.__data` | `0x1d0` | `0x1e0` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x38` | `0x40` | **`+0x8`** |
| `__TEXT.__const` | `0x152` | `0x15a` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0xec` | `0xf4` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x230` | `0x238` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-116.0.0.0.2
+134.0.7.0.1

-  Functions: 111
-  Symbols:   176
-  CStrings:  70
+  Functions: 113
+  Symbols:   182
+  CStrings:  73
Symbols:
+ _$s11SwiftCRLite13ValidDatabaseC26defaultUpdateNotifyChannelSSvgZ
+ _$s11SwiftCRLite13ValidDatabaseC28areBackgroundUpdatesDisabledSbvg
+ _$s11SwiftCRLite13ValidDatabaseC8database15creationAllowed19updateNotifyChannel13configurationAC10Foundation3URLV_SbSSAA0C13ConfigurationVSgtKcfc
+ _$s11SwiftCRLite18ValidConfigurationV7defaultACvgZ
+ _$s11SwiftCRLite18ValidConfigurationVMa
+ _$s11SwiftCRLite18ValidConfigurationVMn
+ _$s11SwiftCRLite25ValidMetricCloudTelemetryC8isDaemon13configurationACSb_AA0C13ConfigurationVtcfc
+ _$s11SwiftCRLite41variant_allows_internal_security_policiesySbSSF
+ _objc_release_x27
+ _swift_release_x25
- _$s11SwiftCRLite13ValidDatabaseC8database15creationAllowedAC10Foundation3URLV_SbtKcfc
- _$s11SwiftCRLite25ValidMetricCloudTelemetryCACycfc
- _objc_release_x25
- _objc_retain_x21
CStrings:
+ "setDownloadInitialDatabaseTask: skipping — disable_background_updates is set"
+ "validDownload initial: skipping — disable_background_updates is set"
+ "validDownload: skipping — disable_background_updates is set"
```
