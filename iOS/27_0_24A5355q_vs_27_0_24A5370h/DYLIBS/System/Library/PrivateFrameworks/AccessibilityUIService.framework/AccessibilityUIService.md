## AccessibilityUIService

> `/System/Library/PrivateFrameworks/AccessibilityUIService.framework/AccessibilityUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1dfb8` | `0x1eb2c` | **`+0xb74`** |
| `__AUTH_CONST.__objc_const` | `0x2600` | `0x27f0` | **`+0x1f0`** |
| `__TEXT.__objc_methlist` | `0x1af4` | `0x1bec` | **`+0xf8`** |
| `__DATA_CONST.__objc_selrefs` | `0x17b8` | `0x1858` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x11bc` | `0x1216` | **`+0x5a`** |
| `__AUTH.__objc_data` | `0x4e0` | `0x530` | **`+0x50`** |
| `__TEXT.__cstring` | `0x1503` | `0x152e` | **`+0x2b`** |
| `__DATA_CONST.__const` | `0x8d0` | `0x8f8` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x4d0` | `0x4f8` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x170` | `0x18c` | **`+0x1c`** |
| `__TEXT.__unwind_info` | `0x888` | `0x898` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xc8` | `0xd0` | **`+0x8`** |
| `__TEXT.__const` | `0x838` | `0x840` | **`+0x8`** |

### Other Changes

```diff

-3229.1.6.0.0
+3232.3.0.0.0

-  Functions: 714
-  Symbols:   1422
-  CStrings:  209
+  Functions: 735
+  Symbols:   1462
+  CStrings:  212
Symbols:
+ +[AXUIDisplayManager activeReservedAvoidanceRegionsForView:]
+ -[AXUIContentVCAttachmentRecord .cxx_destruct]
+ -[AXUIContentVCAttachmentRecord sceneClientIdentifier]
+ -[AXUIContentVCAttachmentRecord service]
+ -[AXUIContentVCAttachmentRecord setSceneClientIdentifier:]
+ -[AXUIContentVCAttachmentRecord setService:]
+ -[AXUIContentVCAttachmentRecord setUserInteractionEnabled:]
+ -[AXUIContentVCAttachmentRecord setUserInterfaceStyle:]
+ -[AXUIContentVCAttachmentRecord userInteractionEnabled]
+ -[AXUIContentVCAttachmentRecord userInterfaceStyle]
+ -[AXUIDisplayManager _migrateContentViewControllersForSceneClientIdentifier:]
+ -[AXUIDisplayManager _preferredActiveWindowSceneForClientIdentifier:]
+ -[AXUIDisplayManager _sceneActivationStateDidChange:]
+ -[AXUIDisplayManager activeSceneTrackingIdentifiers]
+ -[AXUIDisplayManager lastActiveSceneByIdentifier]
+ -[AXUIDisplayManager setActiveSceneTrackingEnabled:forSceneClientIdentifier:]
+ -[AXUIDisplayManager setActiveSceneTrackingIdentifiers:]
+ -[AXUIDisplayManager setLastActiveSceneByIdentifier:]
+ -[AXUIDisplayManager setVcAttachmentRecords:]
+ -[AXUIDisplayManager vcAttachmentRecords]
+ GCC_except_table326
+ GCC_except_table327
+ GCC_except_table348
+ GCC_except_table356
+ GCC_except_table364
+ GCC_except_table369
+ GCC_except_table385
+ GCC_except_table414
+ GCC_except_table416
+ GCC_except_table431
+ _OBJC_CLASS_$_AXUIContentVCAttachmentRecord
+ _OBJC_CLASS_$_NSMapTable
+ _OBJC_IVAR_$_AXUIContentVCAttachmentRecord._sceneClientIdentifier
+ _OBJC_IVAR_$_AXUIContentVCAttachmentRecord._service
+ _OBJC_IVAR_$_AXUIContentVCAttachmentRecord._userInteractionEnabled
+ _OBJC_IVAR_$_AXUIContentVCAttachmentRecord._userInterfaceStyle
+ _OBJC_IVAR_$_AXUIDisplayManager._activeSceneTrackingIdentifiers
+ _OBJC_IVAR_$_AXUIDisplayManager._lastActiveSceneByIdentifier
+ _OBJC_IVAR_$_AXUIDisplayManager._vcAttachmentRecords
+ _OBJC_METACLASS_$_AXUIContentVCAttachmentRecord
+ _UISceneDidActivateNotification
+ _UISceneDidEnterBackgroundNotification
+ __OBJC_$_INSTANCE_METHODS_AXUIContentVCAttachmentRecord
+ __OBJC_$_INSTANCE_VARIABLES_AXUIContentVCAttachmentRecord
+ __OBJC_$_PROP_LIST_AXUIContentVCAttachmentRecord
+ __OBJC_CLASS_RO_$_AXUIContentVCAttachmentRecord
+ __OBJC_METACLASS_RO_$_AXUIContentVCAttachmentRecord
+ ___72-[AXUIDisplayManager _windowSceneDisconnected:forSceneClientIdentifier:]_block_invoke
+ ___NSArray0__struct
+ ___block_descriptor_48_e8_32s40s_e40_v32?0"NSString"8"UIWindowScene"16^B24ls32l8s40l8
- GCC_except_table311
- GCC_except_table312
- GCC_except_table333
- GCC_except_table334
- GCC_except_table341
- GCC_except_table354
- GCC_except_table370
- GCC_except_table394
- GCC_except_table396
- GCC_except_table411
CStrings:
+ "!"
+ "Active window scene for '%{public}@' changed from %p to %p; migrating tracked content VCs"
+ "v32@?0@\"NSString\"8@\"UIWindowScene\"16^B24"
```
