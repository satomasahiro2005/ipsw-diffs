## PSECollectionExtension

> `/System/Library/ExtensionKit/Extensions/PSECollectionExtension.appex/PSECollectionExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fac` | `0x1c64` | **`-0x348`** |
| `__TEXT.__eh_frame` | `0x158` | `0x108` | **`-0x50`** |
| `__TEXT.__oslogstring` | `0xdc` | `0x99` | **`-0x43`** |
| `__TEXT.__objc_stubs` | `0x40` | `—` | **`-0x40`** |
| `__TEXT.__objc_methname` | `0x2f` | `—` | **`-0x2f`** |
| `__TEXT.__auth_stubs` | `0x3e0` | `0x3c0` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x1f8` | `0x1e0` | **`-0x18`** |
| `__DATA.__objc_selrefs` | `0x10` | `—` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x40` | `0x30` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0x18` | `0x10` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x100` | `0xf8` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x1c` | `0x18` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-3600.52.1.0.0
+3605.15.1.0.0

-  - /System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration

-  Functions: 47
-  Symbols:   239
-  CStrings:  9
+  Functions: 44
+  Symbols:   228
+  CStrings:  6
Symbols:
- _$s22PSECollectionExtensionAAC20LighthouseBackground06MLHostB0AacDP9shouldRun7contextAC0E6ResultCAC0eB7ContextC_tYaFTWTQ1_
- _$s22PSECollectionExtensionAAC9shouldRun7context20LighthouseBackground12MLHostResultCAE0hB7ContextC_tYaFTQ0_
- _$s22PSECollectionExtensionAAC9shouldRun7context20LighthouseBackground12MLHostResultCAE0hB7ContextC_tYaFTf4ndd_n
- _$s22PSECollectionExtensionAAC9shouldRun7context20LighthouseBackground12MLHostResultCAE0hB7ContextC_tYaFTf4ndd_nTu
- _MCFeatureDiagnosticsSubmissionAllowed
- _OBJC_CLASS_$_MCProfileConnection
- _objc_msgSend
- _objc_msgSend$effectiveBoolValueForSetting:
- _objc_msgSend$sharedConnection
- _objc_release_x24
- _objc_retainAutoreleasedReturnValue
CStrings:
- "Diagnostics submission not allowed; skipping PSE collection"
- "effectiveBoolValueForSetting:"
- "sharedConnection"
```
