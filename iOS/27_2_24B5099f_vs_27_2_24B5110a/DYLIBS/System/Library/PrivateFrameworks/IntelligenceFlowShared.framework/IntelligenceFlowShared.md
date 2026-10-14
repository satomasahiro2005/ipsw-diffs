## IntelligenceFlowShared

> `/System/Library/PrivateFrameworks/IntelligenceFlowShared.framework/IntelligenceFlowShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdc9f8` | `0xdfd84` | **`+0x338c`** |
| `__TEXT.__const` | `0x156e0` | `0x15a30` | **`+0x350`** |
| `__TEXT.__oslogstring` | `0xdf6` | `0xf96` | **`+0x1a0`** |
| `__TEXT.__eh_frame` | `0x569c` | `0x5804` | **`+0x168`** |
| `__AUTH_CONST.__const` | `0xcea8` | `0xcfe8` | **`+0x140`** |
| `__DATA.__bss` | `0x19090` | `0x19190` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0x5d50` | `0x5e18` | **`+0xc8`** |
| `__TEXT.__cstring` | `0x96aa` | `0x974a` | **`+0xa0`** |
| `__TEXT.__swift5_reflstr` | `0x3f4c` | `0x3fdc` | **`+0x90`** |
| `__AUTH_CONST.__auth_got` | `0x1548` | `0x15b0` | **`+0x68`** |
| `__TEXT.__swift5_fieldmd` | `0x5840` | `0x58a8` | **`+0x68`** |
| `__TEXT.__swift5_typeref` | `0x3ebc` | `0x3f1e` | **`+0x62`** |
| `__DATA.__data` | `0x23b0` | `0x2400` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x3a18` | `0x3a60` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x848` | `0x868` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0x41f8` | `0x4208` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x90` | `0xa0` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x8c` | `0x9c` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x580` | `0x588` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x390` | `0x398` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1408` | `0x1410` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x5e4` | `0x5ec` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x388` | `0x38c` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0xa8` | `0xa4` | **`-0x4`** |

### Other Changes

```diff

-3605.21.1.501.4
+3605.22.501.10.0

+  - /System/Library/Frameworks/VideoToolbox.framework/VideoToolbox

-  Functions: 9859
-  Symbols:   314
-  CStrings:  1172
+  Functions: 9941
+  Symbols:   318
+  CStrings:  1183
Symbols:
+ _CFDataCreateMutable
+ _VTCreateCGImageFromCVPixelBuffer
+ _kCGImageDestinationLossyCompressionQuality
+ _objc_retain_x28
CStrings:
+ "CVReadOnlyPixelBuffer+JPEG: Failed to create CGImage from pixel buffer"
+ "CVReadOnlyPixelBuffer+JPEG: Failed to create image destination"
+ "CVReadOnlyPixelBuffer+JPEG: Failed to create mutable data"
+ "CVReadOnlyPixelBuffer+JPEG: Failed to finalize image destination"
+ "Encoded screenshot for %{public}s: %{public}ld bytes"
+ "Failed to encode screenshot for %{public}s"
+ "HomeKit Accessory"
+ "PlannerToolboxTrainOverride"
+ "[IconServicesAppIconResolver] Resolved %{public}s %s (%ld bytes)"
+ "com.apple.podcasts"
+ "isMediaFallbackUser"
+ "resolve(_:isDark:)"
- "[IconServicesAppIconResolver] Resolved %{public}s (%ld bytes)"
```
