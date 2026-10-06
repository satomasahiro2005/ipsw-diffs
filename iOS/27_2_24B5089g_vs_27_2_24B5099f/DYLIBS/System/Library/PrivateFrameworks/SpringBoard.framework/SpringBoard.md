## SpringBoard

> `/System/Library/PrivateFrameworks/SpringBoard.framework/SpringBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb0fec4` | `0xb10b04` | **`+0xc40`** |
| `__TEXT.__cstring` | `0x8544f` | `0x855ed` | **`+0x19e`** |
| `__TEXT.__oslogstring` | `0x658b2` | `0x659af` | **`+0xfd`** |
| `__AUTH_CONST.__cfstring` | `0x74ca0` | `0x74d80` | **`+0xe0`** |
| `__TEXT.__gcc_except_tab` | `0x1864c` | `0x186e4` | **`+0x98`** |
| `__TEXT.__objc_methlist` | `0xbe040` | `0xbe090` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x4eb20` | `0x4eb60` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x2e658` | `0x2e668` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1da60` | `0x1da68` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xfca8` | `0xfca4` | **`-0x4`** |

### Other Changes

```diff

-4637.1.8.101.0
+4637.1.12.101.0

-  Functions: 73627
-  Symbols:   119477
-  CStrings:  23575
+  Functions: 73638
+  Symbols:   119483
+  CStrings:  23587
Symbols:
+ -[SBAppPlatterDragPreview pendingIconViewListLayoutProvider]
+ -[SBAppPlatterDragPreview setPendingIconViewListLayoutProvider:]
+ -[SBApplication(Identity) isFindMyFindingUI]
+ -[SBFluidSwitcherGestureManager gestureRecognizer:shouldReceiveEvent:]
+ -[SBHomeScreenService replaceApplicationIconsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:options:]
+ -[SBHomeScreenService swapApplicationIconsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:]
+ GCC_except_table159
+ _OBJC_IVAR_$_SBAppPlatterDragPreview._pendingIconViewListLayoutProvider
+ _SBFindingUIAngelBundleIdentifier
+ ___block_descriptor_48_e8_32s40r_e33_B16?0"FBSDisplayLayoutElement"8ls32l8r40l8
+ ___block_descriptor_56_e8_32s40r48r_e25_v28?0"NSString"8i16^B20lr40l8r48l8s32l8
+ ___block_descriptor_67_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
- GCC_except_table133
- _OBJC_IVAR_$_SBTransitionSwitcherModifier._fromAppLayout
- _OBJC_IVAR_$_SBTransitionSwitcherModifier._toAppLayout
- ___block_descriptor_40_e8_32r_e25_v28?0"NSString"8i16^B20lr32l8
- ___block_descriptor_40_e8_32s_e33_B16?0"FBSDisplayLayoutElement"8ls32l8
- ___block_descriptor_59_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
CStrings:
+ "%@ has a scene hosted by SpringBoard"
+ "%@ is on screen"
+ "%@ is presenting a remote alert"
+ "-[SBHomeScreenService replaceApplicationIconsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:options:]"
+ "-[SBHomeScreenService swapApplicationIconsWithBundleIdentifier:withApplicationIconsWithBundleIdentifier:]"
+ "Alert restriction: allowing %{public}@ to appear over %{public}@ because %{public}@."
+ "Drop cancelled but the platter's icon view could not be snapshotted; keeping the icon image view controller: %@"
+ "Error preparing for app replacement source lookup: %@"
+ "Not sending status bar tap to %{public}@: scene isn't active"
+ "Restricted to only appear over %@, and what is on screen is %@"
+ "com.apple.findmy.FindingUIAngel"
+ "display layout contains \"%@\", matching %@"
+ "homescreen is showing"
+ "no app"
- "Restricted to only appear over the following bundle ids: %@"
- "[ContainerBundleIdentifier debugging] checking widget = %@"
```
