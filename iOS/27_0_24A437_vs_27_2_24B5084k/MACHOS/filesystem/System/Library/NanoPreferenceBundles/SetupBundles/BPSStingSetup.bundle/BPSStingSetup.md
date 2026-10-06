## BPSStingSetup

> `/System/Library/NanoPreferenceBundles/SetupBundles/BPSStingSetup.bundle/BPSStingSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3e34` | `0x4358` | **`+0x524`** |
| `__TEXT.__objc_methname` | `0x281b` | `0x2995` | **`+0x17a`** |
| `__DATA.__objc_const` | `0xd98` | `0xe28` | **`+0x90`** |
| `__DATA.__objc_selrefs` | `0xa30` | `0xa68` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0xac0` | `0xaf0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x308` | `0x330` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x360` | `0x380` | **`+0x20`** |
| `__TEXT.__const` | `0x40` | `0x60` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1740` | `0x1720` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x150` | `0x168` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x1b8` | `0x1c8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x5c` | `0x68` | **`+0xc`** |
| `__TEXT.__objc_methtype` | `0x106c` | `0x1076` | **`+0xa`** |
| `__DATA.__data` | `0x3c0` | `0x3c8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x168` | `0x160` | **`-0x8`** |
| `__TEXT.__cstring` | `0x42c` | `0x42d` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1359.9.0.0.0
+1370.0.0.0.0

-  Functions: 109
-  Symbols:   125
-  CStrings:  564
+  Functions: 114
+  Symbols:   130
+  CStrings:  578
Symbols:
+ _OBJC_CLASS_$_UILayoutGuide
+ _OBJC_CLASS_$_UIView
+ __dispatch_main_q
+ _objc_copyWeak
+ _objc_initWeak
CStrings:
+ "@\"UIView\""
+ "T@\"BPSSetupContentView\",&,N,V_animationContainer"
+ "T@\"NSLayoutConstraint\",&,N,V_collectionHeightConstraint"
+ "T@\"UIView\",&,N,V_localContentView"
+ "TB,N,V_widthPassPending"
+ "Td,N,V_lastLaidOutWidth"
+ "_animationContainer"
+ "_collectionHeightConstraint"
+ "_lastLaidOutWidth"
+ "_widthPassPending"
+ "addLayoutGuide:"
+ "animationContainer"
+ "centerYAnchor"
+ "collectionHeightConstraint"
+ "constraintEqualToConstant:"
+ "constraintLessThanOrEqualToAnchor:"
+ "constraintLessThanOrEqualToConstant:"
+ "dealloc"
+ "lastLaidOutWidth"
+ "removeObserver:forKeyPath:context:"
+ "setAnimationContainer:"
+ "setCollectionHeightConstraint:"
+ "setLastLaidOutWidth:"
+ "setPriority:"
+ "setWidthPassPending:"
+ "traitCollection"
+ "verticalSizeClass"
+ "viewDidLoad"
+ "widthPassPending"
- "T@\"BPSSetupContentView\",&,N,V_localContentView"
- "TB,N,V_doneSettingUpViews"
- "_applyScale"
- "_doneSettingUpViews"
- "_positionAnimationView"
- "doneSettingUpViews"
- "reloadData"
- "revalidateColumnLayoutIfNeeded"
- "setActive:"
- "setDoneSettingUpViews:"
- "setFrame:"
- "setupViews"
- "sizeToFit"
- "updateLocalViewSize"
- "watchViewBottomConstraint"
```
