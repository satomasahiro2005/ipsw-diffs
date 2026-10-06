## SearchToolDiagnosticExtension

> `/System/Library/ExtensionKit/Extensions/SearchToolDiagnosticExtension.appex/SearchToolDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc08c` | `0xc7fc` | **`+0x770`** |
| `__DATA_CONST.__const` | `0x10a0` | `0x1258` | **`+0x1b8`** |
| `__DATA.__bss` | `0xfa0` | `0x1120` | **`+0x180`** |
| `__TEXT.__cstring` | `0xa15` | `0xb45` | **`+0x130`** |
| `__TEXT.__const` | `0xa54` | `0xb34` | **`+0xe0`** |
| `__DATA.__data` | `0x4e0` | `0x5a0` | **`+0xc0`** |
| `__DATA.__objc_const` | `0x200` | `0x290` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x2b8` | `0x320` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0x3ff` | `0x45f` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x770` | `0x7c0` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x478` | `0x4c0` | **`+0x48`** |
| `__TEXT.__objc_classname` | `0x7b` | `0xbb` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x274` | `0x2a0` | **`+0x2c`** |
| `__TEXT.__swift5_typeref` | `0x35d` | `0x383` | **`+0x26`** |
| `__DATA_CONST.__auth_ptr` | `0x188` | `0x1a0` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x16c` | `0x180` | **`+0x14`** |
| `__TEXT.__swift5_reflstr` | `0x1ab` | `0x1bb` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x7c` | `0x88` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x34` | `0x3c` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`

### Other Changes

```diff

-3600.56.27.0.0
+3600.56.32.11.4

+  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags

-  Functions: 429
-  Symbols:   184
-  CStrings:  160
+  Functions: 465
+  Symbols:   183
+  CStrings:  172
Symbols:
- _swift_release_x21
CStrings:
+ "/usr/local/bin/gstool"
+ "/usr/local/bin/photosctl"
+ "GLP feature enablement status"
+ "IntelligenceFlow"
+ "LWDebug"
+ "SearchToolDiagnostics: sensitive logging disabled; skipping transcript attachment."
+ "_TtC29SearchToolDiagnosticExtension18FeatureFlagService"
+ "feature-enablement"
+ "glp_enablement_status.txt"
+ "photo search summary"
+ "photoKitSearchExecuted"
+ "photo_search_summary.txt"
```
