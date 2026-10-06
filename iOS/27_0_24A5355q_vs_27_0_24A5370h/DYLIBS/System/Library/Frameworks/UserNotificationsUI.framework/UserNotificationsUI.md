## UserNotificationsUI

> `/System/Library/Frameworks/UserNotificationsUI.framework/UserNotificationsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa9d0` | `0xaa40` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x1590` | `0x15d0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x7e5` | `0x80e` | **`+0x29`** |
| `__AUTH_CONST.__cfstring` | `0x200` | `0x220` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xc98` | `0xca8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x12c8` | `0x12d8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xb4` | `0xb8` | **`+0x4`** |

### Other Changes

```diff

-1053.0.0.0.0
+1061.0.0.0.0

-  Functions: 399
-  Symbols:   743
-  CStrings:  87
+  Functions: 401
+  Symbols:   746
+  CStrings:  88
Symbols:
+ -[NSExtension(UserNotificationsUI) un_scrollsOwnContent]
+ -[_UNNotificationContentExtensionHostContainerViewController scrollsOwnContent]
+ _OBJC_IVAR_$__UNNotificationContentExtensionHostContainerViewController._scrollsOwnContent
Functions:
+ -[NSExtension(UserNotificationsUI) un_scrollsOwnContent]
~ -[_UNNotificationContentExtensionHostContainerViewController initWithExtension:notification:actions:] : 564 -> 592
~ -[_UNNotificationContentExtensionHostContainerViewController _flushQueuedRequests] : 628 -> 624
+ -[_UNNotificationContentExtensionHostContainerViewController notificationRequestIdentifier]
~ -[_UNNotificationContentExtensionCache registerExtensions:] : 516 -> 504
~ -[_UNNotificationContentExtensionCache _addExtension:] : 552 -> 548
~ -[_UNMediaPlayPauseButton _updateBackgroundForMovieStyle] : 728 -> 724
CStrings:
+ "UNNotificationExtensionScrollsOwnContent"
```
