## HomeFeedbackDiagnosticExtension

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeFeedbackDiagnosticExtension.appex/HomeFeedbackDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1fb` | `0x1a5` | **`-0x56`** |
| `__TEXT.__text` | `0x6834` | `0x687c` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0x4dd` | `0x50d` | **`+0x30`** |
| `__DATA_CONST.__got` | `0xd0` | `0xe0` | **`+0x10`** |
| `__TEXT.__const` | `0xe4` | `0xf4` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0xf2` | `0x102` | **`+0x10`** |
| `__DATA.__data` | `0x188` | `0x190` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x50` | `0x58` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_types`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1238.0.0.0.0
+1241.1.7.1.2

-  Symbols:   101
-  CStrings:  62
+  Symbols:   100
+  CStrings:  61
Symbols:
- _objc_retain_x21
Functions:
~ sub_100003464 : 13360 -> 13256
~ sub_100006894 -> sub_10000682c : 1592 -> 1780
~ sub_100006ecc -> sub_100006f20 : 528 -> 516
CStrings:
+ "HFDEFileFolderCountDescription"
+ "No attachments gathered, returning nil"
- "HFDEGroupClipsFolderDescription"
- "HFDEGroupFolderDescription"
- "HFDEGroupThumbnailsFolderDescription"
```
