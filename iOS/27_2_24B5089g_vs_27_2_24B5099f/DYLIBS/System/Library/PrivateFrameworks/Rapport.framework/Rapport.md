## Rapport

> `/System/Library/PrivateFrameworks/Rapport.framework/Rapport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x588` | `0x2660` | **`+0x20d8`** |
| `__DATA.__data` | `0x2218` | `0x678` | **`-0x1ba0`** |
| `__AUTH.__objc_data` | `0x1350` | `0x50` | **`-0x1300`** |
| `__DATA_DIRTY.__objc_data` | `0x1318` | `0x2618` | **`+0x1300`** |
| `__AUTH.__data` | `0x538` | `—` | **`-0x538`** |
| `__TEXT.__text` | `0xdffbc` | `0xe02f8` | **`+0x33c`** |
| `__AUTH_CONST.__cfstring` | `0x6160` | `0x5f40` | **`-0x220`** |
| `__TEXT.__cstring` | `0x14dfc` | `0x14eac` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x26fd` | `0x26bd` | **`-0x40`** |
| `__DATA_CONST.__const` | `0x28b0` | `0x28d8` | **`+0x28`** |
| `__AUTH_CONST.__objc_intobj` | `0x258` | `0x270` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xa190` | `0xa1a8` | **`+0x18`** |
| `__DATA.__bss` | `0x2ea0` | `0x2e90` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x4600` | `0x4610` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0xc8` | `0xd8` | **`+0x10`** |
| `__TEXT.__const` | `0x41b8` | `0x41a8` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x2f70` | `0x2f80` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1188` | `0x1190` | **`+0x8`** |
| `__AUTH_CONST.__objc_const` | `0x11670` | `0x11678` | **`+0x8`** |

### Other Changes

```diff

-751.200.41.0.0
+751.200.74.0.0

-  Functions: 5840
-  Symbols:   6867
-  CStrings:  3081
+  Functions: 5843
+  Symbols:   6872
+  CStrings:  3073
Symbols:
+ -[RPClient endpointContextForService:trustCircles:parameters:completion:]
+ ___73-[RPClient endpointContextForService:trustCircles:parameters:completion:]_block_invoke
+ ___73-[RPClient endpointContextForService:trustCircles:parameters:completion:]_block_invoke_2
+ ___block_descriptor_72_e8_32s40s48s56bs_e5_v8?0ls32l8s56l8s40l8s48l8
+ _nw_parameters_copy_dictionary
CStrings:
+ "### Specifying the trust flags using RPOptionStatusFlags for registering message '%@' is required."
+ "-[RPClient endpointContextForService:trustCircles:parameters:completion:]"
+ "-[RPClient endpointContextForService:trustCircles:parameters:completion:]_block_invoke"
+ "Access permitted for %~@ for %@"
+ "Access revoked for %~@ for %@"
+ "Failed to encode parameters"
+ "Failed to encode parameters %@ for %@: %{error}"
+ "MusicHandoffScan"
+ "No change in devices: "
+ "No context provided"
+ "Requesting endpoint context for %@ with %@ and %#ll{flags}\n"
- "### Specifying the trust flags using RPOptionStatusFlags for registering message '%@' is required. Please file a radar in 'Rapport | All' to get more information."
- "FaceTimeAgent"
- "GeneralKnowledgeAgent"
- "HomeKitAgent"
- "HomepodSystemAgent"
- "IMSHPApp"
- "IMSTVApp"
- "MediaAgent"
- "No change in devices: %@"
- "PhotosAgent"
- "ScreenSaverAgent"
- "SearchAgent"
- "SystemAgent"
- "acousticcalibrationd"
- "idac-client"
- "idacd"
- "idactool"
- "imsutil"
- "sgsutil"
```
