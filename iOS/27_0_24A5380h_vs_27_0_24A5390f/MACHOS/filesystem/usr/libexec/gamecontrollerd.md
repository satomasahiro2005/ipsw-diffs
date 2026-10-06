## gamecontrollerd

> `/usr/libexec/gamecontrollerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x248` | `0x308` | **`+0xc0`** |
| `__TEXT.__text` | `0x1fcc` | `0x207c` | **`+0xb0`** |
| `__DATA.__objc_const` | `0xbb8` | `0xc60` | **`+0xa8`** |
| `__TEXT.__objc_methtype` | `0x655` | `0x6e8` | **`+0x93`** |
| `__TEXT.__objc_methname` | `0xc4e` | `0xcd5` | **`+0x87`** |
| `__TEXT.__objc_methlist` | `0x494` | `0x4dc` | **`+0x48`** |
| `__TEXT.__objc_classname` | `0xc0` | `0xfb` | **`+0x3b`** |
| `__DATA.__objc_selrefs` | `0x3c8` | `0x3e8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xc8` | `0xd8` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x30` | `0x40` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x20` | `0x30` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x4c` | `0x54` | **`+0x8`** |
| `__TEXT.__cstring` | `0x315` | `0x316` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-14.0.19.0.0
+14.0.21.0.0

-  Symbols:   92
-  CStrings:  282
+  Symbols:   94
+  CStrings:  294
Symbols:
+ _OBJC_CLASS_$_GCSystemButtonArbitrationServer
+ _OBJC_CLASS_$_GCUserNotificationManager
Functions:
~ sub_10000187c : 856 -> 936
~ sub_100001d40 -> sub_100001d90 : 296 -> 352
~ sub_1000028c4 -> sub_10000294c : 344 -> 384
CStrings:
+ "@\"GCFuture\"24@0:8@\"<GCUserNotificationRequest>\"16"
+ "@\"GCSystemButtonArbitrationServer\""
+ "@\"GCUserNotificationManager\""
+ "B32@0:8@\"NSString\"16@\"NSString\"24"
+ "GCSystemButtonArbitrationService"
+ "GCUserNotificationService"
+ "_systemButtonArbitrationServer"
+ "_userNotificationManager"
+ "checkExceptionForApp:parent:"
+ "checkSystemGestureEnabled"
+ "performActions:"
+ "presentUserNotificationForRequest:"
+ "settingsGeneration"
+ "systemGestureAction"
+ "v24@0:8@\"NSArray\"16"
- "launchApplicationWithBundleIdentifier:"
- "togglePlatformGamesLibrary"
- "v24@0:8@\"NSString\"16"
```
