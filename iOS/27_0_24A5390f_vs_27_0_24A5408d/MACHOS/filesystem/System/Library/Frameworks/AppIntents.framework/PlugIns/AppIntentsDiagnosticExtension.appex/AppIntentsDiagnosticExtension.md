## AppIntentsDiagnosticExtension

> `/System/Library/Frameworks/AppIntents.framework/PlugIns/AppIntentsDiagnosticExtension.appex/AppIntentsDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xebfc` | `0xf25c` | **`+0x660`** |
| `__DATA.__bss` | `0x540` | `0xb40` | **`+0x600`** |
| `__TEXT.__const` | `0x4b8` | `0x7c0` | **`+0x308`** |
| `__DATA.__data` | `0x240` | `0x2b0` | **`+0x70`** |
| `__TEXT.__objc_methname` | `0xfb1` | `0x1016` | **`+0x65`** |
| `__TEXT.__swift5_assocty` | `0x30` | `0x90` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x638` | `0x688` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0xc00` | `0xc50` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x37c` | `0x3c9` | **`+0x4d`** |
| `__TEXT.__constg_swiftt` | `0xb8` | `0xf8` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x3c0` | `0x400` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x7c` | `0xb4` | **`+0x38`** |
| `__TEXT.__swift5_proto` | `0x28` | `0x58` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x608` | `0x630` | **`+0x28`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x3c` | **`+0x28`** |
| `__TEXT.__cstring` | `0x44b` | `0x46b` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x378` | `0x390` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x390` | `0x3a0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x108` | `0x118` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__swift5_reflstr` | `0x6e` | `0x74` | **`+0x6`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-301.0.45.4.101
+301.0.51.1.102

-  Functions: 347
-  Symbols:   152
-  CStrings:  225
+  Functions: 374
+  Symbols:   156
+  CStrings:  228
Symbols:
+ _NSFileProtectionCompleteUntilFirstUserAuthentication
+ _NSFileProtectionKey
+ _objc_release_x26
+ _objc_retain_x27
CStrings:
+ "appintents-database"
+ "createDirectoryAtURL:withIntermediateDirectories:attributes:error:"
+ "setAttributes:ofItemAtPath:error:"
```
