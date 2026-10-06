## AskPermissionUI

> `/Applications/AskPermissionUI.app/AskPermissionUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xded8` | `0xe0e4` | **`+0x20c`** |
| `__TEXT.__objc_stubs` | `0x2420` | `0x2540` | **`+0x120`** |
| `__TEXT.__objc_methname` | `0x40a1` | `0x4178` | **`+0xd7`** |
| `__DATA_CONST.__cfstring` | `0x1460` | `0x1500` | **`+0xa0`** |
| `__DATA.__objc_selrefs` | `0xec8` | `0xf18` | **`+0x50`** |
| `__DATA.__objc_const` | `0x2658` | `0x2610` | **`-0x48`** |
| `__TEXT.__cstring` | `0xa58` | `0xa96` | **`+0x3e`** |
| `__DATA_CONST.__got` | `0x248` | `0x260` | **`+0x18`** |
| `__DATA.__bss` | `0x28` | `0x38` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x18df` | `0x18cf` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x1418` | `0x1424` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-130.0.29.0.0
+130.1.4.0.0

-  Functions: 263
-  Symbols:   167
-  CStrings:  1016
+  Functions: 267
+  Symbols:   170
+  CStrings:  1029
Symbols:
+ _NSCalendarIdentifierGregorian
+ _OBJC_CLASS_$_NSCalendar
+ _OBJC_CLASS_$_NSTimeZone
CStrings:
+ "UTC"
+ "_shouldRemoveViewFromHierarchyOnDisappear"
+ "askToBadgeIconBundleIdentifier"
+ "calendarWithIdentifier:"
+ "com.apple.Music"
+ "com.apple.iBooks"
+ "effectiveGeometry"
+ "en_US_POSIX"
+ "localeWithLocaleIdentifier:"
+ "setAllowsAlertStacking:"
+ "setCalendar:"
+ "setLocale:"
+ "setTimeZone:"
+ "subscription"
+ "timeZoneWithAbbreviation:"
+ "yyyy-MM-dd'T'HH:mm:ss.SZZZ"
- "@\"NSUUID\"16@0:8"
- "T@\"NSUUID\",R,N"
- "YYYY-MM-dd'T'HH:mm:ss.SZZZ"
```
