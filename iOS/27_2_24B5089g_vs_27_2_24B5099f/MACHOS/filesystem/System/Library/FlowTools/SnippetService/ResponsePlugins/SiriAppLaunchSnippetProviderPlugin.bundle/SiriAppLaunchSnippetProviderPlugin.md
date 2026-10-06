## SiriAppLaunchSnippetProviderPlugin

> `/System/Library/FlowTools/SnippetService/ResponsePlugins/SiriAppLaunchSnippetProviderPlugin.bundle/SiriAppLaunchSnippetProviderPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7c2c` | `0x83d0` | **`+0x7a4`** |
| `__TEXT.__oslogstring` | `0x3f8` | `0x4d8` | **`+0xe0`** |
| `__TEXT.__auth_stubs` | `0x660` | `0x6b0` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x330` | `0x358` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x278` | `0x2a0` | **`+0x28`** |
| `__DATA_CONST.__got` | `0xe8` | `0xf0` | **`+0x8`** |
| `__TEXT.__const` | `0x1d0` | `0x1d8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1e0` | `0x1e8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3605.5.1.0.0
+3605.6.1.0.0

-  Symbols:   72
-  CStrings:  16
+  Symbols:   73
+  CStrings:  19
Symbols:
+ _objc_release_x8
Functions:
~ sub_2e44 : 2252 -> 4176
~ sub_4f34 -> sub_56b8 : 36 -> 68
CStrings:
+ "marketplaceApplicationEntity: display item carried no value"
+ "marketplaceApplicationEntity: type mismatch — bundleIdentifier=%{public}s typeName=%{public}s"
+ "marketplaceApplicationEntity: typedValue is not an entity"
```
