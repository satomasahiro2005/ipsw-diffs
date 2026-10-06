## ShortcutsSettings

> `/System/Library/PreferenceBundles/ShortcutsSettings.bundle/ShortcutsSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4b58` | `0x4c28` | **`+0xd0`** |
| `__TEXT.__auth_stubs` | `0x560` | `0x5d0` | **`+0x70`** |
| `__TEXT.__objc_methname` | `0x144c` | `0x149e` | **`+0x52`** |
| `__TEXT.__objc_stubs` | `0x1340` | `0x1380` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x2b8` | `0x2f0` | **`+0x38`** |
| `__TEXT.__oslogstring` | `—` | `0x35` | **`+0x35`** |
| `__DATA_CONST.__const` | `0x1e8` | `0x208` | **`+0x20`** |
| `__TEXT.__cstring` | `0x521` | `0x53e` | **`+0x1d`** |
| `__DATA.__bss` | `0x110` | `0x120` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x690` | `0x6a0` | **`+0x10`** |
| `__TEXT.__const` | `0x150` | `0x158` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1b0` | `0x1b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-5034.0.12.100.0
+5037.103.100.0.0

-  Functions: 113
-  Symbols:   178
-  CStrings:  328
+  Functions: 114
+  Symbols:   183
+  CStrings:  332
Symbols:
+ __CFBundleCopyBundleURLForExecutableURL
+ __os_log_impl
+ _dladdr
+ _getWFGeneralLogObject
+ _objc_release_x9
+ _objc_retain_x21
+ _os_log_type_enabled
- _WFShortcutsSettingsLocalizedPluralString
- _WFShortcutsSettingsLocalizedString
CStrings:
+ "%s WFLocalizedString failed to locate current bundle"
+ "WFCurrentBundle_block_invoke"
+ "bundleWithURL:"
+ "initFileURLWithFileSystemRepresentation:isDirectory:relativeToURL:"
```
