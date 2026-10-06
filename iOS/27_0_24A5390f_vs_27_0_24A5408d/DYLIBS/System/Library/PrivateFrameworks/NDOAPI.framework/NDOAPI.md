## NDOAPI

> `/System/Library/PrivateFrameworks/NDOAPI.framework/NDOAPI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdea78` | `0xdf61c` | **`+0xba4`** |
| `__TEXT.__cstring` | `0x1b54` | `0x1c04` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x11c0` | `0x1260` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x3200` | `0x31d8` | **`-0x28`** |
| `__TEXT.__swift5_typeref` | `0x213a` | `0x2130` | **`-0xa`** |
| `__TEXT.__swift5_capture` | `0x6d4` | `0x6cc` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x45b0` | `0x45b8` | **`+0x8`** |

### Other Changes

```diff

-624.0.4.0.0
+624.0.13.0.0

-  Functions: 6701
-  Symbols:   1289
-  CStrings:  267
+  Functions: 6705
+  Symbols:   1288
+  CStrings:  274
Symbols:
+ _symbolic xSdSpySuG_____Iegnyyd_ s5Int32V
- _symbolic _____yxGSgXw 6NDOAPI25NDOShowAlertActionHandlerC
- _symbolic _____yxGSgXwz_x_lXX 6NDOAPI25NDOShowAlertActionHandlerC
CStrings:
+ "%s.%s: isSignedIn=%{bool}d for request %{private}s"
+ "%s.%s: load completed with result %{private}s"
+ "%s.%s: loading warranty for serials %{private}s"
+ "NDOAPI/NDOAppleAccountSignedInUrlClient.swift"
+ "NDOAPI/NDOWarrantyLoader.swift"
+ "load(request:with:)"
+ "loadWarranty(forDeviceSerials:additionalHeaders:completion:)"
```
