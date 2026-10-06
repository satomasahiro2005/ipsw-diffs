## BPSStingSetup

> `/System/Library/NanoPreferenceBundles/SetupBundles/BPSStingSetup.bundle/BPSStingSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41f8` | `0x3e34` | **`-0x3c4`** |
| `__TEXT.__oslogstring` | `0x3b7` | `0x22d` | **`-0x18a`** |
| `__DATA.__data` | `0x360` | `0x3c0` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x1700` | `0x1740` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x103f` | `0x106c` | **`+0x2d`** |
| `__DATA.__objc_const` | `0xd70` | `0xd98` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x191` | `0x1b3` | **`+0x22`** |
| `__TEXT.__const` | `0x60` | `0x40` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x2836` | `0x281b` | **`-0x1b`** |
| `__TEXT.__objc_methlist` | `0xaa8` | `0xac0` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x350` | `0x360` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xa28` | `0xa30` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x1b0` | `0x1b8` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x48` | `0x50` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x170` | `0x168` | **`-0x8`** |
| `__TEXT.__cstring` | `0x42b` | `0x42c` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1359.7.0.0.0
+1359.9.0.0.0

-  Symbols:   124
-  CStrings:  567
+  Symbols:   125
+  CStrings:  564
Symbols:
+ _CGRectIsEmpty
+ _OBJC_CLASS_$_BPSSetupContentView
- _OBJC_CLASS_$_UIView
Functions:
~ sub_2494 : 1500 -> 1100
~ sub_2a70 -> sub_28e0 : 244 -> 152
~ sub_2b64 -> sub_2978 : 180 -> 64
~ sub_2c18 -> sub_29b8 : 336 -> 124
~ sub_3150 -> sub_2e1c : 416 -> 444
~ sub_3378 -> sub_3060 : 156 -> 172
~ sub_3414 -> sub_310c : 428 -> 260
~ sub_35c0 -> sub_3210 : 64 -> 252
~ sub_3600 -> sub_330c : 416 -> 228
~ sub_3928 -> sub_3578 : 200 -> 180
CStrings:
+ "@\"BPSSetupContentView\""
+ "BPSSetupContentViewLayoutObserver"
+ "T@\"BPSSetupContentView\",&,N,V_localContentView"
+ "Td,N,V_animationIntrinsicHeight"
+ "_animationIntrinsicHeight"
+ "animationIntrinsicHeight"
+ "setAnimationIntrinsicHeight:"
+ "setFrame:"
+ "setLayoutObserver:"
+ "setNeedsLayout"
+ "setupContentViewDidLayoutSubviews:"
+ "v24@0:8@\"BPSSetupContentView\"16"
- "'"
- "@\"UIView\""
- "Safe insets are set, can now setup views"
- "Space for animation: %f scalefactor: %f availablecontentheight: %f collectionviewHeight: %f animationViewHeight: %f"
- "T@\"NSLayoutConstraint\",&,N,V_collectionViewHeightConstraint"
- "T@\"UIView\",&,N,V_localContentView"
- "_collectionViewHeightConstraint"
- "_positionAnimationView: skipped (visualH=%.1f)"
- "_positionAnimationView: visualH=%.0f container=%.0f center=(%.0f,%.0f)"
- "applyAnimationLayoutContraints"
- "collectionViewHeightConstraint"
- "constraintEqualToConstant:"
- "safeAreaInsets"
- "setCollectionViewHeightConstraint:"
- "updateLocalViewSize: animationHeight=%.0f collectionHeight=%.0f minContentHeight=%.0f availableHeight=%.0f result=%.0f"
```
