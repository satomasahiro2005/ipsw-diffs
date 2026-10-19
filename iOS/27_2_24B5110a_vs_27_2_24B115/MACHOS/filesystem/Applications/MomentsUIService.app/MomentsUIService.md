## MomentsUIService

> `/Applications/MomentsUIService.app/MomentsUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2917ac` | `0x291874` | **`+0xc8`** |
| `__DATA_CONST.__cfstring` | `0x2140` | `0x21a0` | **`+0x60`** |
| `__TEXT.__cstring` | `0xa158` | `0xa1b8` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0xda03` | `0xda33` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x7730` | `0x7728` | **`-0x8`** |
| `__TEXT.__gcc_except_tab` | `0x22c` | `0x230` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  CStrings:  5003
+  CStrings:  5007
Functions:
~ -[MOSuggestionsUIServerManager listener:didReceiveConnection:withContext:] : 876 -> 972
~ +[MOPlatformInfo isSeedBuild] : 8 -> 112
CStrings:
+ "Endpoint received new connection request -- pid:%d"
+ "MODefaultsManager.m"
+ "MOSuggestionsUIServerManager.m"
+ "PlatformInfoOverrideIsSeedBuild"
```
