## AccessibilityUIServer

> `/System/Library/CoreServices/AccessibilityUIServer.app/AccessibilityUIServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5d18` | `0x5f28` | **`+0x210`** |
| `__TEXT.__auth_stubs` | `0xa10` | `0xa90` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x259b` | `0x261b` | **`+0x80`** |
| `__TEXT.__objc_stubs` | `0xbe0` | `0xc60` | **`+0x80`** |
| `__TEXT.__cstring` | `0x261` | `0x2d7` | **`+0x76`** |
| `__DATA_CONST.__cfstring` | `0x1a0` | `0x200` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x390` | `0x3f0` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x518` | `0x558` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x7f8` | `0x818` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x160` | `0x178` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xaac` | `0xac4` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3234.5.0.0.0
+3237.1.0.0.0

-  Functions: 169
-  Symbols:   279
-  CStrings:  481
+  Functions: 174
+  Symbols:   290
+  CStrings:  489
Symbols:
+ _AXDeviceHasStaccato
+ _CFNotificationCenterAddObserver
+ _CFNotificationCenterGetDarwinNotifyCenter
+ _CFNotificationCenterRemoveObserver
+ _CFPreferencesAppSynchronize
+ _CFPreferencesGetAppBooleanValue
+ _CFPreferencesSetAppValue
+ _OBJC_CLASS_$_AXSpringBoardServer
+ __AXSVoiceOverTouchEnabled
+ _kAXSVoiceOverPreferenceDomain
+ _kCFBooleanTrue
CStrings:
+ "AXSHasShownActionButtonDescribeScenePromo"
+ "_registerForBuddyCompletionNotificationIfNeeded"
+ "_showActionButtonDescribeScenePromoIfNeeded"
+ "com.apple.purplebuddy.setupdone"
+ "kAXVOTBrailleSceneClientIdentifier"
+ "server"
+ "showAlert:withHandler:"
+ "v16@?0q8"
```
