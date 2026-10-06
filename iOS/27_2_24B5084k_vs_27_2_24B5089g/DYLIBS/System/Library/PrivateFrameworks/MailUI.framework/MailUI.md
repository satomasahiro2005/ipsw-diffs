## MailUI

> `/System/Library/PrivateFrameworks/MailUI.framework/MailUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x35689c` | `0x357094` | **`+0x7f8`** |
| `__AUTH_CONST.__objc_const` | `0x144c0` | `0x14530` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x9efc` | `0x9f24` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x6670` | `0x6688` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x6bb0` | `0x6bc8` | **`+0x18`** |
| `__DATA.__data` | `0x7260` | `0x7270` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x3000` | `0x3010` | **`+0x10`** |
| `__TEXT.__const` | `0x11224` | `0x11234` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x3d73` | `0x3d83` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x36c4` | `0x36d0` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x3180` | `0x3178` | **`-0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x3048` | `0x3050` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x9a8` | `0x9ac` | **`+0x4`** |

### Other Changes

```diff

-3901.200.34.0.0
+3901.200.41.0.0

-  Functions: 15571
-  Symbols:   8737
+  Functions: 15585
+  Symbols:   8738
Symbols:
+ -[MUIMessageListViewController bucketBarPeekingEnabled]
+ -[MUIMessageListViewController setBucketBarPeekingEnabled:]
+ _OBJC_IVAR_$_MUIMessageListViewController._bucketBarPeekingEnabled
+ _keypath_get_selector_bucketBarPeekingEnabled
- +[UINavigationBar(DCI) mf_shouldUseDesktopClassNavigationBarForTraitCollection:windowScene:]
- -[UIWindowScene(MailUI) mui_isWide]
- __UIEnhancedLandscapeEnabled
```
