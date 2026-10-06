## ScreenTimeDiagnosticExtension

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/ScreenTimeDiagnosticExtension.appex/ScreenTimeDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b64` | `0x1e4c` | **`+0x2e8`** |
| `__TEXT.__oslogstring` | `0x153` | `0x1b3` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x420` | `0x470` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0xb8` | `0xf0` | **`+0x38`** |
| `__TEXT.__objc_methname` | `0x1fa` | `0x22b` | **`+0x31`** |
| `__DATA_CONST.__auth_got` | `0x218` | `0x240` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x220` | `0x240` | **`+0x20`** |
| `__TEXT.__cstring` | `0x45` | `0x63` | **`+0x1e`** |
| `__TEXT.__unwind_info` | `0xe8` | `0xf8` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xa0` | `0xa8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x5c` | `0x64` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-637.0.102.0.0
+640.0.100.0.0

+  - /System/Library/PrivateFrameworks/ScreenTimeSettingsServices.framework/ScreenTimeSettingsServices

-  Functions: 36
-  Symbols:   86
-  CStrings:  37
+  Functions: 40
+  Symbols:   87
+  CStrings:  41
Symbols:
+ _swift_release_x20
CStrings:
+ "Failed to collect ScreenTimeSettings database: %{public}@"
+ "ScreenTimeSettings"
+ "Successfully collected ScreenTimeSettings database"
+ "collectScreenTimeSettingsDatabaseAndReturnError:"
```
