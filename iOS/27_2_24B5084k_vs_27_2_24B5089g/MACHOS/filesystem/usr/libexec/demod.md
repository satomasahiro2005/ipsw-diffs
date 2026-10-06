## demod

> `/usr/libexec/demod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf9684` | `0xf9cfc` | **`+0x678`** |
| `__TEXT.__oslogstring` | `0x1d56c` | `0x1d6bc` | **`+0x150`** |
| `__TEXT.__objc_stubs` | `0x1ba40` | `0x1bb80` | **`+0x140`** |
| `__TEXT.__objc_methname` | `0x21696` | `0x2174e` | **`+0xb8`** |
| `__TEXT.__cstring` | `0x11542` | `0x115b2` | **`+0x70`** |
| `__DATA_CONST.__cfstring` | `0xef00` | `0xef60` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x82f8` | `0x8348` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0xdc5c` | `0xdc8c` | **`+0x30`** |
| `__DATA_CONST.__got` | `0xf30` | `0xf58` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x3280` | `0x32a0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x3b40` | `0x3b58` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1871.40.45.0.0
+1871.40.52.0.0

-  Functions: 6139
-  Symbols:   1061
-  CStrings:  11047
+  Functions: 6148
+  Symbols:   1066
+  CStrings:  11064
Symbols:
+ _OBJC_CLASS_$_MSDKDemoState
+ _kSecAttrDescription
+ _kSecAttrGeneric
+ _kSecAttrIsInvisible
+ _kSecAttrType
CStrings:
+ "/var/mobile/Library/Preferences/com.apple.voicetrigger.plist"
+ "Disabled explicit music for the primary home's current user."
+ "EnableSiriAI"
+ "Failed to disable explicit music.  Could not find a primary home for where user belongs to."
+ "Failed to disable explicit music.  Error code: %ld, description: %{public}@"
+ "Failed to disable explicit music.  No '%s' setting in the current user's settings for the primary home."
+ "_findSettingWithKeyPath:inGroup:"
+ "currentUser"
+ "disableExplicitMusic"
+ "enableSiriAI"
+ "enableSiriAI:"
+ "groups"
+ "isPressDemoModeEnabled:"
+ "keyPath"
+ "root.music.allowExplicitContent"
+ "updateValue:completionHandler:"
+ "userSettingsForHome:"
```
