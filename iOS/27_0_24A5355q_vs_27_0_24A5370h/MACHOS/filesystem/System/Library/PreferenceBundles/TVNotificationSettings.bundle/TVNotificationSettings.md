## TVNotificationSettings

> `/System/Library/PreferenceBundles/TVNotificationSettings.bundle/TVNotificationSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4eb8` | `0x5614` | **`+0x75c`** |
| `__TEXT.__oslogstring` | `0x1bf` | `0x26f` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x25f` | `0x285` | **`+0x26`** |
| `__TEXT.__objc_stubs` | `0x260` | `0x280` | **`+0x20`** |
| `__TEXT.__const` | `0x174` | `0x184` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x286` | `0x296` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xd0` | `0xd8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xa8` | `0xb0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1138.0.0.0.2
+1143.0.0.0.2

-  Functions: 71
-  Symbols:   109
-  CStrings:  60
+  Functions: 72
+  Symbols:   110
+  CStrings:  65
Symbols:
+ _PSFooterAlignmentGroupKey
CStrings:
+ "Failed to create empty-state group specifier"
+ "Failed to create group specifier for topic %{public}s"
+ "Failed to create toggle specifier for topic %{public}s"
+ "NOTIFICATION_SETTINGS_NONE_AVAILABLE"
+ "initWithInteger:"
```
