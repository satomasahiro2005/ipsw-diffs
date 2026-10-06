## SideButtonSettings

> `/System/Library/Settings/SideButtonSettings.settings/SideButtonSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe57c` | `0xe7c0` | **`+0x244`** |
| `__TEXT.__objc_methname` | `0x729` | `0x779` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x4c0` | `0x500` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x1f8` | `0x210` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x19c` | `0x1b4` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x220` | `0x230` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.55.30.0.0
+3600.55.37.11.2

-  Functions: 346
-  Symbols:   167
-  CStrings:  149
+  Functions: 347
+  Symbols:   169
+  CStrings:  152
Symbols:
+ _OBJC_CLASS_$_NSDistributedNotificationCenter
+ _kSVASSideButtonSettingDidChange
CStrings:
+ "addObserver:selector:name:object:suspensionBehavior:"
+ "removeObserver:name:object:"
+ "siriStateDidChange"
```
