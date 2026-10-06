## ContactsUI

> `/System/Library/AccessibilityBundles/ContactsUI.axbundle/ContactsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xce30` | `0xd360` | **`+0x530`** |
| `__TEXT.__oslogstring` | `0xa` | `0x32f` | **`+0x325`** |
| `__AUTH_CONST.__cfstring` | `0x33c0` | `0x3440` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x2c4` | `0x304` | **`+0x40`** |
| `__TEXT.__cstring` | `0x2982` | `0x29a8` | **`+0x26`** |
| `__TEXT.__const` | `0x20` | `0x38` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x778` | `0x788` | **`+0x10`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Symbols:   1346
-  CStrings:  440
+  Symbols:   1350
+  CStrings:  449
Symbols:
+ _AXAIWhiteGloveLoggingEnabled
+ _AXLogCommon
+ _NSStringFromClass
+ _objc_release_x28
Functions:
~ -[CNContactListCollectionViewCellAccessibility accessibilityLabel] : 472 -> 880
~ ___66-[CNContactListCollectionViewCellAccessibility accessibilityLabel]_block_invoke : 428 -> 1348
CStrings:
+ "_assetName"
+ "_symbolName"
+ "imageName"
+ "lock"
+ "rdar://166424765 CNContactListCollectionViewCell accessibilityLabel enter cellClass=%{public}@ accessoriesCount=%lu isEmergency=%d superLabel=%{private}@"
+ "rdar://166424765 CNContactListCollectionViewCell accessibilityLabel exit hasBlockedString=%d hasEmergencyString=%d superLabelLength=%lu superLabelContainsBlocked=%d"
+ "rdar://166424765 CNContactListCollectionViewCell accessory idx=%lu class=%{public}@ superclass=%{public}@ isCustomView=%d"
+ "rdar://166424765 CNContactListCollectionViewCell customAccessory idx=%lu customViewClass=%{public}@ customViewSuperclass=%{public}@ isImageView=%d"
+ "rdar://166424765 CNContactListCollectionViewCell imageView idx=%lu assetName=%{public}@ privateAssetName=%{public}@ underscoreAssetName=%{public}@ symbolName=%{public}@ imageName=%{public}@ hasImage=%d nosignMatch=%d"
```
