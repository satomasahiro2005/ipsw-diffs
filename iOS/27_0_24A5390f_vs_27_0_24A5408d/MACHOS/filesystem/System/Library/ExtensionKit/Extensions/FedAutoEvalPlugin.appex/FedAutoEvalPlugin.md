## FedAutoEvalPlugin

> `/System/Library/ExtensionKit/Extensions/FedAutoEvalPlugin.appex/FedAutoEvalPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10e14` | `0x10cec` | **`-0x128`** |
| `__TEXT.__eh_frame` | `0xc58` | `0xcc0` | **`+0x68`** |
| `__DATA.__objc_data` | `0xa0` | `0x50` | **`-0x50`** |
| `__TEXT.__auth_stubs` | `0xf70` | `0xf30` | **`-0x40`** |
| `__TEXT.__cstring` | `0x182` | `0x142` | **`-0x40`** |
| `__DATA.__data` | `0x4a8` | `0x480` | **`-0x28`** |
| `__DATA.__objc_const` | `0x1e0` | `0x208` | **`+0x28`** |
| `__TEXT.__oslogstring` | `0x2d6` | `0x2fa` | **`+0x24`** |
| `__DATA_CONST.__auth_got` | `0x7c0` | `0x7a0` | **`-0x20`** |
| `__TEXT.__const` | `0x8e0` | `0x8c0` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x3f5` | `0x3e5` | **`-0x10`** |
| `__TEXT.__constg_swiftt` | `0x1ac` | `0x1a0` | **`-0xc`** |
| `__TEXT.__swift5_fieldmd` | `0x220` | `0x214` | **`-0xc`** |
| `__TEXT.__objc_methname` | `0xac` | `0xb7` | **`+0xb`** |
| `__DATA.__common` | `0x40` | `0x38` | **`-0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x2b0` | `0x2b8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x430` | `0x428` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x1eb` | `0x1f1` | **`+0x6`** |
| `__TEXT.__swift_as_cont` | `0x84` | `0x88` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-38.0.0.0.0
+42.0.0.0.0

-  Functions: 230
-  Symbols:   128
+  Functions: 229
+  Symbols:   129
Symbols:
+ _swift_retain_x25
CStrings:
+ "Conflicting data sources from plugin parameters and recipe.\nTask parameters: %s\nRecipe: %s."
+ "preference"
- "Failed to decode DataSourceConfig from PluginPreference: %@"
- "com.apple.priml.PFLMLHostPlugins.FedAutoEvalPlugin."
```
