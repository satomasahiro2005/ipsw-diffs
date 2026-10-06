## localizationswitcherd

> `/System/Library/PrivateFrameworks/IntlPreferences.framework/Support/localizationswitcherd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa8a4` | `0xaa3c` | **`+0x198`** |
| `__TEXT.__oslogstring` | `0xa5c` | `0xaec` | **`+0x90`** |
| `__TEXT.__objc_stubs` | `0x980` | `0x9a0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x170` | `0x180` | **`+0x10`** |
| `__TEXT.__cstring` | `0x602` | `0x612` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0xce` | `0xdc` | **`+0xe`** |
| `__DATA.__data` | `0x1b8` | `0x1c0` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x348` | `0x350` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x48` | `0x50` | **`+0x8`** |
| `__TEXT.__const` | `0x13a` | `0x142` | **`+0x8`** |
| `__TEXT.__objc_methname` | `0x9bb` | `0x9b7` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-494.3.0.0.0
+494.6.0.0.0

-  Functions: 140
-  Symbols:   274
-  CStrings:  241
+  Functions: 143
+  Symbols:   275
+  CStrings:  244
Symbols:
+ _$s10Foundation6LocaleVMn
+ _swift_release_x24
- _swift_release_x26
CStrings:
+ "Description for language discovery follow-up notification. Variable is language name."
+ "Type in %@ and get content recommendations in supported apps."
+ "[LD] Failed to register Darwin observer for com.apple.language.change, status=%d"
+ "[LD] Registered Darwin observer for com.apple.language.change"
+ "copy"
+ "persistRejectedLanguage:"
+ "systemPreferredLanguagesChanged"
+ "systemPreferredLanguagesChanged — detecting removed languages"
- "Description for language discovery. Variable is language name."
- "You can add %@ to this device and also set it as your primary language."
- "preferredLanguagesChanged"
- "preferredLanguagesChanged — detecting removed languages"
- "rejectDiscoveredLanguage:clearFollowUp:"
```
