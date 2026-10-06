## AskPermissionAskToResponseExtension

> `/System/Library/ExtensionKit/Extensions/AskPermissionAskToResponseExtension.appex/AskPermissionAskToResponseExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14c00` | `0x1540c` | **`+0x80c`** |
| `__TEXT.__objc_stubs` | `0x1d60` | `0x1e60` | **`+0x100`** |
| `__DATA_CONST.__cfstring` | `0x1180` | `0x1220` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x2905` | `0x29a5` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x116d` | `0x11dd` | **`+0x70`** |
| `__DATA.__data` | `0x520` | `0x580` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x54c` | `0x5ac` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0xa40` | `0xa80` | **`+0x40`** |
| `__DATA.__objc_data` | `0x3a0` | `0x3d8` | **`+0x38`** |
| `__TEXT.__const` | `0x4e2` | `0x512` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x2a8` | `0x2d8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x480` | `0x4a8` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x342` | `0x364` | **`+0x22`** |
| `__DATA.__bss` | `0x3b8` | `0x3d8` | **`+0x20`** |
| `__DATA.__objc_const` | `0x1418` | `0x1438` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0xe4` | `0x104` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x2b0` | `0x2c8` | **`+0x18`** |
| `__TEXT.__objc_classname` | `0x197` | `0x1a9` | **`+0x12`** |
| `__DATA_CONST.__objc_protolist` | `0x50` | `0x60` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1020` | `0x1030` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0xaba` | `0xaaa` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xc4` | `0xd0` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x820` | `0x828` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xb18` | `0xb1c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-130.0.29.0.0
+130.1.4.0.0

-  Functions: 351
-  Symbols:   241
-  CStrings:  764
+  Functions: 360
+  Symbols:   245
+  CStrings:  778
Symbols:
+ _NSCalendarIdentifierGregorian
+ _OBJC_CLASS_$_NSCalendar
+ _OBJC_CLASS_$_NSTimeZone
+ _os_transaction_create
CStrings:
+ "OS_os_transaction"
+ "UTC"
+ "_processAssertion"
+ "askToBadgeIconBundleIdentifier"
+ "calendarWithIdentifier:"
+ "com.apple.AskPermission.AskToResponseExtension.Approval"
+ "com.apple.Music"
+ "com.apple.iBooks"
+ "effectiveGeometry"
+ "en_US_POSIX"
+ "localeWithLocaleIdentifier:"
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
