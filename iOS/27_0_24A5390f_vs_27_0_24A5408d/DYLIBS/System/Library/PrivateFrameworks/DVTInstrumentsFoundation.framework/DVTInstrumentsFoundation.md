## DVTInstrumentsFoundation

> `/System/Library/PrivateFrameworks/DVTInstrumentsFoundation.framework/DVTInstrumentsFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe3084` | `0xe439c` | **`+0x1318`** |
| `__DATA.__bss` | `0x42f0` | `0x4800` | **`+0x510`** |
| `__TEXT.__cstring` | `0xef4c` | `0xf1bc` | **`+0x270`** |
| `__TEXT.__const` | `0x3dc2` | `0x4012` | **`+0x250`** |
| `__AUTH_CONST.__const` | `0x34f8` | `0x3620` | **`+0x128`** |
| `__TEXT.__swift5_fieldmd` | `0x11dc` | `0x1298` | **`+0xbc`** |
| `__TEXT.__oslogstring` | `0x5ddf` | `0x5e8f` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x9e80` | `0x9f20` | **`+0xa0`** |
| `__DATA.__data` | `0x2f60` | `0x3000` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0x18dc` | `0x1954` | **`+0x78`** |
| `__TEXT.__swift5_reflstr` | `0xf97` | `0xff7` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x3e20` | `0x3e80` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x1294` | `0x12d4` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0xe3c` | `0xe76` | **`+0x3a`** |
| `__TEXT.__swift5_proto` | `0x214` | `0x23c` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x2020` | `0x2038` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x6284` | `0x629c` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x90` | `0xa8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xd58` | `0xd68` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x12320` | `0x12328` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x34f8` | `0x3500` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x258` | `0x260` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x4210` | `0x4208` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x846c` | `0x8464` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x180` | `0x188` | **`+0x8`** |

### Other Changes

```diff

-64578.145.1.0.0
+64578.160.1.0.0

-  Functions: 4964
-  Symbols:   1875
-  CStrings:  2597
+  Functions: 5003
+  Symbols:   1877
+  CStrings:  2610
Symbols:
+ _CFStringGetTypeID
+ _DTProcessorTraceCapabilityDecodeCompression
CStrings:
+ "A Background Assets debug session is already active for this device. Stop it before starting another."
+ "Built-In Display %d"
+ "DTAssetService: BA session-start capture — prior value shape=%{public}s, stashed for restore=%{BOOL}d"
+ "DTAssetService: Refusing BA start — a session is already active"
+ "Experiments: %@, Loads: %@, Predictions: %@, Max Prediction Time: %@, Max Iteration Time: %@, Function Name: %@, Specialization Config: %@"
+ "Failed to encode the Background Assets override URL."
+ "Failed to start the Background Assets debug server."
+ "com.apple.dt.AssetService.BackgroundAssets"
+ "com.apple.dt.processor-trace.decode-compression"
+ "finalizePerfRunSetup: No function name specified."
+ "finalizePerfRunSetup: No specialization config found."
+ "none"
+ "other"
+ "specializationConfig"
- "Built-In Display"
```
