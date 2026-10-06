## UserNotificationsUIKit

> `/System/Library/PrivateFrameworks/UserNotificationsUIKit.framework/UserNotificationsUIKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x28c8` | `0x24d8` | **`-0x3f0`** |
| `__DATA_DIRTY.__objc_data` | `0x37d0` | `0x3bc0` | **`+0x3f0`** |
| `__TEXT.__text` | `0x1befd0` | `0x1bf2ec` | **`+0x31c`** |
| `__DATA_DIRTY.__data` | `0x1410` | `0x16f0` | **`+0x2e0`** |
| `__AUTH.__data` | `0x5d0` | `0x3d8` | **`-0x1f8`** |
| `__DATA.__bss` | `0x1670` | `0x14c8` | **`-0x1a8`** |
| `__DATA_DIRTY.__bss` | `0x18e8` | `0x1a88` | **`+0x1a0`** |
| `__DATA.__data` | `0x53c0` | `0x5248` | **`-0x178`** |
| `__TEXT.__oslogstring` | `0xfce3` | `0xfd69` | **`+0x86`** |
| `__AUTH_CONST.__objc_const` | `0x26c10` | `0x26bb8` | **`-0x58`** |
| `__TEXT.__objc_methlist` | `0x1ac9c` | `0x1ac4c` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x7468` | `0x7418` | **`-0x50`** |
| `__TEXT.__const` | `0x43a4` | `0x43e4` | **`+0x40`** |
| `__DATA.__common` | `0x78` | `0x60` | **`-0x18`** |
| `__DATA_DIRTY.__common` | `0x58` | `0x70` | **`+0x18`** |
| `__TEXT.__cstring` | `0x9fac` | `0x9fbd` | **`+0x11`** |
| `__DATA_CONST.__objc_selrefs` | `0xcb08` | `0xcb18` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x1ccc` | `0x1cd8` | **`+0xc`** |
| `__TEXT.__swift5_typeref` | `0x3d30` | `0x3d26` | **`-0xa`** |
| `__AUTH_CONST.__auth_got` | `0x1598` | `0x15a0` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x610` | `0x608` | **`-0x8`** |
| `__TEXT.__swift5_reflstr` | `0x12be` | `0x12c1` | **`+0x3`** |

### Same-size Content Changes

- `__TEXT.__ustring`

### Other Changes

```diff

-1061.0.0.0.0
+1065.0.0.0.0

-  Functions: 10972
-  Symbols:   14409
+  Functions: 10958
+  Symbols:   14404
Symbols:
+ -[NCNotificationShortLookViewController maximumContentWidthForExpandedPlatterViewController:]
+ -[NCNotificationStructuredListViewController _notificationListViewEdgeInsetsForOrientation:]
+ -[NCNotificationStructuredListViewController _overlayFooterViewEdgeInsetsForOrientation:]
+ -[NCNotificationStructuredListViewController _updateListEdgeInsets]
+ -[NCNotificationStructuredListViewController _updateVerticalSizeClass]
+ GCC_except_table139
+ __OBJC_$_CLASS_METHODS_NCNotificationRequest(Bulletin|CarPlay|ATXUserNotificationAdditions|NCUIAdditions)
+ __OBJC_$_INSTANCE_METHODS_NCNotificationRequest(Bulletin|CarPlay|ATXUserNotificationAdditions|NCUIAdditions)
+ __OBJC_CLASS_PROTOCOLS_$_NCNotificationRequest(Bulletin|CarPlay|ATXUserNotificationAdditions|NCUIAdditions)
+ __UIClamp
+ __UILerp
+ ___swift_destroy_boxed_opaque_existential_1
+ ___swift_project_boxed_opaque_existential_1Tm
+ _keypath_set.109Tm
+ _swift_retain_x8
+ _type_layout_string So6CGSizeV
- -[NCNotificationStructuredListViewController _notificationListViewEdgeInsetsForSize:]
- -[NCNotificationStructuredListViewController _overlayFooterViewEdgeInsetsForSize:]
- -[NCNotificationStructuredListViewController _updateListEdgeInsetsForSize:]
- -[NCNotificationStructuredListViewController _updateOrientationForSize:]
- GCC_except_table138
- GCC_except_table145
- __CLASS_METHODS_NCPlatterView
- __CLASS_PROPERTIES_NCPlatterView
- __OBJC_$_CLASS_METHODS_NCNotificationRequest(Bulletin|ATXUserNotificationAdditions|NCUIAdditions|CarPlay)
- __OBJC_$_INSTANCE_METHODS_NCNotificationRequest(Bulletin|ATXUserNotificationAdditions|NCUIAdditions|CarPlay)
- __OBJC_$_PROP_LIST_NCNotificationListDataProviding
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_NCNotificationListDataProviding
- __OBJC_$_PROTOCOL_METHOD_TYPES_NCNotificationListDataProviding
- __OBJC_$_PROTOCOL_REFS_NCNotificationListDataProviding
- __OBJC_CLASS_PROTOCOLS_$_NCNotificationRequest(Bulletin|ATXUserNotificationAdditions|NCUIAdditions|CarPlay)
- __OBJC_LABEL_PROTOCOL_$_NCNotificationListDataProviding
- __OBJC_PROTOCOL_$_NCNotificationListDataProviding
- ___swift_project_boxed_opaque_existential_0Tm
- _keypath_setTm
- _swift_retain_x28
- _type_layout_string So7CGPointV
CStrings:
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UserNotificationsUIKit/UserNotificationsUIKit/Notification Lists/Structured List/Structure/Modernization/NotificationRootModernList.swift"
+ "History-height latch: useActualHistoryHeight %{bool,public}d -> %{bool,public}d (offsetY=%{public}f lastPageMaxY=%{public}f)"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UserNotificationsUIKit/UserNotificationsUIKit/NotificationRootModernList.swift"
- "iOSNotificationCenter"
```
