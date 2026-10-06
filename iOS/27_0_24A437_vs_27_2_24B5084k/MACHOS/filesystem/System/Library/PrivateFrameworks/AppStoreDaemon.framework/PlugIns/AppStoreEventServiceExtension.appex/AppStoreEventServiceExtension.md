## AppStoreEventServiceExtension

> `/System/Library/PrivateFrameworks/AppStoreDaemon.framework/PlugIns/AppStoreEventServiceExtension.appex/AppStoreEventServiceExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x160` | `0x114` | **`-0x4c`** |
| `__TEXT.__oslogstring` | `0x140` | `0x181` | **`+0x41`** |
| `__DATA_CONST.__cfstring` | `0x340` | `0x300` | **`-0x40`** |
| `__TEXT.__text` | `0xec0` | `0xee0` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x180` | `0x170` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0xc8` | `0xc0` | **`-0x8`** |
| `__TEXT.__const` | `0x60` | `0x68` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-557.1.33.0.0
+557.2.8.0.0

-  Symbols:   47
-  CStrings:  78
+  Symbols:   46
+  CStrings:  77
Symbols:
- _CreateDiagnosticReport
Functions:
~ sub_100001320 : 1816 -> 1848
CStrings:
+ "Proof of Purchase is nil for reportingConversionType: %{public}@"
- "OnDeviceConversion"
- "Proof of Purchase is nil for reportingConversionType: %@"
```
